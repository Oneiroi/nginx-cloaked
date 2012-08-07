nginx-cloaked
=============

Custom nginx build, intended to provide some security hardening through config and source changes.

This follows on from my [blog post](http://blog.oneiroi.co.uk/hacking/linux/security/nginx/cloaking-your-web-apps-the-stealth-engine-x/).

This project repackages SRC rpms from [upstream](http://nginx.org/packages/) focusing on the RHEL6 packages.

As this project maintains simply .patch files to make the required modifications they can be applied in theory to any distro package;
el6 rpms will be made available [from here](http://oneiroi.fedorapeople.org)



