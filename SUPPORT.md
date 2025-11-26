## Asking For Help

1. Make sure your VVV is up to date, your problem might have been fixed already!
   - `vagrant status` will reveal the version you have installed 
2. Same goes for vagrant, you can check [Hashicorps vagrant install](https://developer.hashicorp.com/vagrant/install) for the latest version
3. Please check https://github.com/Varying-Vagrant-Vagrants/VVV/issues for any existing issues
4. If not either open a new issue or you can visit our slack instance.

Note that issues are only for VVV, we are not a general Vagrant help resource. All github issues for this organisation are centralised on the main VVV repo.

## Help With Vagrant Providers

Note that we officially support:

 - VirtualBox on x86/Amd64
 - Parallels Pro
 - Docker
 - Hyper-V

### Other Vagrant Providers

However you may see code for other providers, e.g. vmware or libvirt. We cannot guarantee these providers will work and we depend on users of those providers to help us. If you attempt to use an unsupported provider we can answer questions about VVV and provide some limited assistance but ultimately it is up to you to tell us what needs to change, short or becoming a fulltime maintainer responsible for that provider. Part of this is because the maintainers don't have access to those providers, or a means of reliably testing them when making changes.

### VirtualBox on Arm

We don't provide support for this provider, and at the time of writing VirtualBox under Arm64/Apple Silicon cannot be used with Vagrant and VVV. But if that changes and you manage to have some success we're open to hearing about it and accepting changes. Until that time we suggest Arm users rely on either Parallels Pro or the docker provider with docker desktop/podman/collima/etc.
