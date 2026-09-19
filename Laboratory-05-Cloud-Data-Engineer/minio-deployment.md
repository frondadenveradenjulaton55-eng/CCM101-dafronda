# MinIO Object Storage Deployment

## Overview

For this laboratory activity, I deployed MinIO as an S3-compatible object storage server using Docker in the KillerCoda Ubuntu Playground. The purpose was to create an object storage environment, access its web console, create a bucket, and upload a test file.

## Docker Command

The Docker command I used to deploy MinIO was:

```bash
docker run -d -p 9000:9000 -p 9001:9001 --name minio-server -e "MINIO_ROOT_USER=cloudadmin" -e "MINIO_ROOT_PASSWORD=CloudNova2026!" quay.io/minio/minio server /data --console-address ":9001"
```

I used `quay.io/minio/minio` because the `minio/minio` image was not accessible from the Docker registry in my KillerCoda environment.

## Port Configuration

| Port | Purpose           |
| ---- | ----------------- |
| 9000 | MinIO API         |
| 9001 | MinIO Web Console |

Port **9001** was used to access the MinIO Web Console through the KillerCoda port access feature.

## Container Verification

After starting the MinIO container, I verified that it was running using:

```bash
docker ps
```

The container name was:

```text
minio-server
```

The container exposed ports 9000 and 9001.

## Environment Variables

The `-e` option in Docker is used to define environment variables inside the container.

The command used the following environment variables:

```text
MINIO_ROOT_USER=cloudadmin
MINIO_ROOT_PASSWORD=CloudNova2026!
```

`MINIO_ROOT_USER` configured the MinIO administrator username, while `MINIO_ROOT_PASSWORD` configured the administrator password.

## Bucket Created

I created the following bucket in the MinIO Web Console:

```text
client-photos
```

The bucket was used to store the test object uploaded during the activity.

## File Upload

After creating the `client-photos` bucket, I uploaded a sample image  into the bucket. The uploaded file confirmed that the MinIO object storage service was functioning.

## Screenshots

The MinIO deployment screenshot is stored at:

```text
screenshots/minio-deployed.png
```

The bucket and uploaded file screenshot is stored at:

```text
screenshots/minio-bucket-upload.png
```

