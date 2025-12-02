# Homebrew Tap

Custom Homebrew tap for efortin projects.

## Installation

```bash
brew tap efortin/tap
```

## Available Formulas

### kubectl-auth-vault

A kubectl credential plugin that fetches OIDC tokens from HashiCorp Vault for Kubernetes authentication.

**Install:**

```bash
brew install efortin/tap/kubectl-auth_vault
```

**Features:**

- Fetches OIDC tokens from Vault using the official [vault-client-go](https://github.com/hashicorp/vault-client-go) SDK
- Caches tokens locally until expiration
- Configurable Vault address and token path
- Cross-platform support (Linux, macOS)
- Works as a kubectl plugin (`kubectl auth-vault`)

For more information, see the [kubectl-auth-vault repository](https://github.com/efortin/kubectl-auth-vault).

## License

MIT
