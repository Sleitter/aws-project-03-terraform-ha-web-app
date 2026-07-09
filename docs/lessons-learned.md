# Lessons Learned

- Terraform allows cloud infrastructure to be created and destroyed using code.
- Terraform state tracks the resources managed by the project.
- The `.terraform/` directory should not be committed to GitHub.
- The `.terraform.lock.hcl` file should be committed to keep provider versions consistent.
- Outputs make it easier to retrieve important resource information.
- Infrastructure as Code makes cloud environments more repeatable and easier to manage.