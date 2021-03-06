---
name: "\U0001F41B Bug Report"
about: "If something isn't working as expected \U0001F914."
title: ''
labels: bug

---

<!---
Please note the following potential times when an issue might be in Terraform core:

* [Configuration Language](https://www.terraform.io/docs/configuration/index.html) or resource ordering issues
* [State](https://www.terraform.io/docs/state/index.html) and [State Backend](https://www.terraform.io/docs/backends/index.html) issues
* [Provisioner](https://www.terraform.io/docs/provisioners/index.html) issues
* [Registry](https://registry.terraform.io/) issues
* Spans resources across multiple providers

If you are running into one of these scenarios, we recommend opening an issue in the [Terraform core repository](https://github.com/hashicorp/terraform/) instead.
--->

<!--- Please keep this note for the community --->

### Community Note

* Please vote on this issue by adding a 👍 [reaction](https://blog.github.com/2016-03-10-add-reactions-to-pull-requests-issues-and-comments/) to the original issue to help the community and maintainers prioritize this request
* Please do not leave "+1" or other comments that do not add relevant new information or questions, they generate extra noise for issue followers and do not help prioritize the request
* If you are interested in working on this issue or have submitted a pull request, please leave a comment

<!--- Thank you for keeping this note for the community --->

### Terraform Version

<!---
Run `terraform -v` to show the version. If you are not running the latest
version of Terraform, you can try upgrading, depending on if your problem is
with the provider or with Terraform core itself. --->

### vSphere Provider Version

<!--- Run `terraform providers` to show the list of providers in use and locate the
vSphere provider in the output (normally will show something like
`provider.vsphere`). If a version is not reported here, more than likely you are
not using a version lock. In this case, you can find the version number in the
`.terraform` data directory, usually the `.terraform/plugins/ARCH/` directory,
where `ARCH` is your system architecture (ie: `linux_amd64`, `windows_amd64`,
`darwin_amd64`, etc). In this directory, there will be a cached vSphere plugin
named something similar to terraform-provider-vsphere_v0.4.1_x4. Here, `0.4.1`
is the version number.

If you are running an older version of the plugin than the most recent version
(check the
[CHANGELOG](https://github.com/terraform-providers/terraform-provider-vsphere/blob/master/CHANGELOG.md)),
first try upgrading to make sure that you issue still persists, as it may have
been fixed in a later release. --->

### Affected Resource(s)

<!--- Please list the resources as a list, for example:
- `vsphere_virtual_machine`
- `vsphere_distributed_port_group`

If this issue appears to affect multiple resources, it may be an issue with
Terraform's core, so please mention this.
--->

### Terraform Configuration Files

<!--- Information about code formatting: https://help.github.com/articles/basic-writing-and-formatting-syntax/#quoting-code --->

```hcl
# Copy-paste your Terraform configurations here - for large Terraform configs,
# please use a service like Dropbox and share a link to the ZIP file. For
# security, you can also encrypt the files using our GPG public key.
```

### Debug Output

<!---
Please provide a link to a GitHub Gist containing the complete debug output. Please do NOT paste the debug output in the issue; just paste a link to the Gist.
--->

### Panic Output

<!--- If Terraform produced a panic, please provide a link to a GitHub Gist containing
the output of the `crash.log`.--->

### Expected Behavior

<!--- What should have happened? --->

### Actual Behavior

<!--- What actually happened? --->

### Steps to Reproduce

<!--- Please list the steps required to reproduce the issue, for example:
1. `terraform apply`--->

### Important Factoids

<!--- Are there anything atypical about your infrastructure that we should know? --->

### References

<!---
Information about referencing Github Issues: https://help.github.com/articles/basic-writing-and-formatting-syntax/#referencing-issues-and-pull-requests

Are there any other GitHub issues (open or closed) or pull requests that should be linked here? Vendor documentation? For example:
--->

* #0000
