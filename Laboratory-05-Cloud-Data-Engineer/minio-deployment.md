# MinIO Deployment Documentation

## Docker Command Used
```bash
docker run -d -p 9000:9000 -p 9001:9001 --name minio-server \
-e "MINIO_ROOT_USER=cloudadmin" \
-e "MINIO_ROOT_PASSWORD=CloudNova2026!" \
pgsty/minio:RELEASE.2026-06-18T00-00-00Z server /data --console-address ":9001"
```

## Access Details
- **Web Console Port:** 9001
- **API Port:** 9000
- **Bucket Created:** client-photos

## Environment Variables Explained
- `MINIO_ROOT_USER`: Sets the admin username used to log in to the MinIO console/API. Acts as the root access key.
- `MINIO_ROOT_PASSWORD`: Sets the admin password (secret key) paired with the root user for authentication.

These environment variables configure the root credentials at container startup, securing access to the storage server and its web console.

## Note on Image Source
The official `minio/minio` Docker image was discontinued after MinIO Inc. stopped publishing new images in October 2025 and archived the upstream repository in February 2026. This deployment uses `pgsty/minio`, an actively maintained community fork that serves as a drop-in replacement (same environment variables, same server command, same on-disk data format).
