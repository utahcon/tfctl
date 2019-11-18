# tfctl
Bash script for managing multiple Terraform versions

## Installs
Script installs terraform binaries as `terraform_${VERSION}` in `$HOME/.local/bin` and then 
symlinks the binary to `$HOME/.local/bin/terraform`

To install a version of Terraform simply pass the flag `-i`, you will be presented with a list
of available versions, select a version and tfctl will download, install, and symlink the binary.


