This repo is an example showcasing a possible use case for the [create-github-app-token-aws](https://github.com/lepadatu-actions/create-github-app-token-aws/tree/main) action.

Terraform GitHub Provider authentication can be achieved in [2-ways](https://registry.terraform.io/providers/integrations/github/latest/docs#authentication), provided a GitHub app is installed with the appropriate permissions:
1. Using the app id, app installation id and app private key
2. Using a GitHub App Installation Access Token

The shortcomings of the first method is due to the requirement of the machine running the terraform code to access the private key directly.

This example focuses on the second approach, using the [create-github-app-token-aws](https://github.com/lepadatu-actions/create-github-app-token-aws/tree/main) action.
