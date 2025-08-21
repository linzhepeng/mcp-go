# Contributing

Thank you for your interest in contributing to the MCP Go SDK! We welcome contributions of all kinds, including bug fixes, new features, and documentation improvements. This document outlines the process for contributing to the project.

## Development Guidelines

### Prerequisites

Make sure you have Go 1.23 or later installed on your machine. You can check your Go version by running:

```bash
go version
```

### Setup

1. Fork the repository
2. Clone your fork:
   
   **Using HTTPS:**
   ```bash
    git clone https://github.com/YOUR_USERNAME/mcp-go.git
    cd mcp-go
    ```
   
   **Using SSH:**
   ```bash
    git clone git@github.com:YOUR_USERNAME/mcp-go.git
    cd mcp-go
    ```

3. Install the required packages:

    ```bash
    go mod tidy
    ```

#### SSH Key Compatibility

SSH keys generated for GitLab can be used with GitHub and vice versa. SSH keys are platform-agnostic and follow standard cryptographic protocols. If you already have SSH keys set up for GitLab, you can:

1. Use the same public key with your GitHub account by adding it in GitHub Settings → SSH and GPG keys
2. Or generate a new SSH key specifically for GitHub following the [GitHub SSH key documentation](https://docs.github.com/en/authentication/connecting-to-github-with-ssh)

The SSH key format and cryptographic standards (RSA, Ed25519, ECDSA) are the same across Git hosting platforms.

### Workflow

1. Create a new branch.
2. Make your changes.
3. Ensure you have added tests for any new functionality.
4. Run the tests as shown below from the root directory:

    ```bash
    go test -v './...'
    ```
5. Submit a pull request to the main branch.

Feel free to reach out if you have any questions or need help either by [opening an issue](https://github.com/mark3labs/mcp-go/issues) or by reaching out in the [Discord channel](https://discord.gg/RqSS2NQVsY).
