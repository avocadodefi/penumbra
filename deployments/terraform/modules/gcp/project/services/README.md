# Project Services

Your text is mostly clear, but I'll suggest a few minor revisions for clarity and correctness:

Project Services
This feature allows you to enable one or several Google APIs. It requires that your project has billing set up, as enabling services may fail without it.

To see all available services, use the following command:

gcloud services list --available

Note: Services are never disabled automatically. You must disable them manually outside of Terraform.
