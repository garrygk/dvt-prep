# dvt-prep
Preparing for dvt by doing some refresher stuff in this repo

The tf state mentioned in the backend 'my-terraform-state-dvt' lives in an s3 bucket.
To sync it with the local config:
Run:
terraform init -migrate-state