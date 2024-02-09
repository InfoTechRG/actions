# Reusable GitHub Actions

### Contents

- [SSH Create](#ssh-create)
  - [Usage](#usage)

## SSH Create

This action adds an SSH key to a GitHub Actions runner.

### Usage

Add the following step to any workflow:

```yaml
- name: Create SSH Config
  uses: InfoTechRG/actions/ssh-create
  with:
    ssh-key: ${{ secrets.SSH_KEY }}
    known-hosts: ${{ secrets.KNOWN_HOSTS }}
```

---

[⌂ README](../../README.md)
