https://registry.terraform.io/providers/newrelic/newrelic/latest/docs
https://developer.newrelic.com/automate-workflows/get-started-terraform/
https://github.com/newrelic/terraform-provider-newrelic



Before you begin
To use this guide, you should have some basic knowledge of both New Relic and Terraform. If you haven't deployed a New Relic open source agent yet, install New Relic for your application. Also, install the Terraform CLI.

# Install New Relic


# Install Terraform
The core Terraform workflow consists of three main steps after you have written your Terraform configuration:

`Initialize` prepares the working directory so Terraform can run the configuration.
`Plan` enables you to preview any changes before you apply them.
`Apply` makes the changes defined by your Terraform configuration to create, update, or destroy resources.




# Initialize Terraform
nano main.tf