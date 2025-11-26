# Security Policy

## Supported Versions

### VVV

We currently support the latest version of the 3.x branch of VVV. This includes the
latest `stable` and `develop` branches. Support for older versions generally assumes
we're trying to upgrade to a newer version but if an issue cannot be reproduced on
the supported branches then it's considered fixed.

#### Users with `customfile`

We do not provide support for custom files. This is provided as a power user feature
for legacy reasons. If you are using this feature it is because you are comfortable
with general vagrantfile modifications but don't want to cause conflicts that prevent
updating VVV.

### VVV Core Extension

We support the latest version of the core extension repository.

The VVV core extension repository needs to work across a wide number of versions, as
it was introduced in VVV 2.x and changes could break legacy local environments that
were forked from 2.x. This means if there is an issue in the latest version that causes
problems on older versions, we should fix that even if it's an unsupported version of VVV.
That does not mean however that newer provisioners and features will support those old
versions, or that it will run well. Just that it won't halt provisioning.

## Reporting a Vulnerability

Please report this privately to a project maintainer, ideally the project lead. This can
be via a slack DM or email.

Given that this is a local developer environment however, the security model for VVV
is very different to a production web host. VVV has known default passwords, and is
expected to only be accessible via local loopback. VVV should never be used as a
staging server on a LAN network, or exposed to the open web.
