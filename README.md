# Check version
```bash
-> % terraform-docs --version                                 
terraform-docs version v0.20.0 darwin/arm64
```

# Generate `terraform-docs.md`
```bash
-> % terraform-docs markdown . --output-file terraform-docs.md
terraform-docs.md updated successfully
```

# Check for resources
```bash
-> % grep google_project terraform-docs.md 
| [google_project.terraform](https://registry.terraform.io/providers/hashicorp/google/latest/docs/resources/project) | resource |
```

`google_project.opentofu` is missing.
