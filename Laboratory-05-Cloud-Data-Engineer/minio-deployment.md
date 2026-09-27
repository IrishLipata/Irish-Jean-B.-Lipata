# MinIO Deployment

## Deployment Overview

MinIO was deployed using Docker in a KillerCoda Ubuntu Playground. MinIO provides S3-compatible object storage for storing unstructured data such as images and other files.

## Docker Command Used

The following Docker command was used to deploy the MinIO server:

```bash
docker run -d \
  -p 9000:9000 \
  -p 9001:9001 \
  --name minio-server \
  --user 0 \
  -v minio-data:/data \
  -e "MINIO_ROOT_USER=cloudadmin" \
  -e "MINIO_ROOT_PASSWORD=CloudNova2026!" \
  alpine/minio:RELEASE.2025-10-15T17-29-55Z \
  server /data --console-address ":9001"
