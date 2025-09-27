# Terraform S3 Bucket Example

This Terraform configuration provisions an **AWS S3 bucket** with:

- Bucket name: `zohort-devops-yourname`
- Versioning enabled
- Public access blocked
- Outputs the bucket name after apply

## Usage

```bash
terraform init
terraform apply -auto-approve
```

Replace `yourname` in the bucket name with your actual name.
