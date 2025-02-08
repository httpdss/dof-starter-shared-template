# dof-starter-shared-template

DevOps Framework set of files to start out the shared repository

## Installation

To get started with this template, clone the repository:

```sh
git clone https://github.com/httpdss/dof-starter-shared-template.git
cd dof-starter-shared-template
```

## Usage

This template includes a set of predefined workflows and Terraform configurations to help you set up your shared DevOps environment quickly.

### GitHub Workflows

- `pre-commit`: Runs pre-commit hooks.
- `release-drafter`: Drafts new releases based on merged pull requests.
- `run-struct`: Executes struct commands.

### Terraform

- `terraform/apps/environments`: Contains environment-specific configurations.
- `terraform/apps/aws-accounts`: Manages AWS account configurations.
- `terraform/apps/init`: Initialization scripts for Terraform.
- `terraform/apps/github-organization`: Manages GitHub organization configurations.

## Contributing

We welcome contributions to improve this template. Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
