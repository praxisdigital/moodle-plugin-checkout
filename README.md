# moodle-plugin-checkout

This action checks out a Moodle plugin repository and install it to correct location in Moodle directory.

# What's new

Please refer to the [release page](https://github.com/praxisdigital/moodle-plugin-checkout/releases/latest) for the latest release notes.

# Usage

<!-- start usage -->
```yaml
- uses: praxisdigital/moodle-test-action@test
  with:
    # Plugin repository & reference
    # Format: 'repo', 'owner/repo'
    repo: ${{ github.repository }}

    # Repository reference (branch, tag, commit)
    ref: 'HEAD'

    # Moodle directory
    # Default: ${{ github.workspace }}
    moodle_dir: ${{ github.workspace }}

    # Token for private repositories
    token: ${{ github.token }}
```
<!-- end usage -->
