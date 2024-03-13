# How To Use With Terraform

-   Fork this repository.
-   Clone your forked repository
-   Navigate to the terraform directory
-   Edit the `backend.tf` file. Add your own remote backend or use a local backend.
-   Execute `terraform plan`
-   If you are ok with the plan, run `terraform apply`
-   The DNS name is printed as output to your screen after you finish running `terraform apply`.
-   Paste this DNS name into a web browser to access your appplication.
