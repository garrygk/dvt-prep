
# backend
The tf state mentioned in the backend 'my-terraform-state-dvt' lives in an s3 bucket.
To sync it with the local config:
Run:
terraform init -migrate-state