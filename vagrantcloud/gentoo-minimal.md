# gentoo-minimal

This is a minimal Gentoo install for both virtualbox and hyperv, based on systemd. Guest tools are installed and the kernel is optimised for running as a VM guest.

This is a rolling release, and the kernel for the current build is `{{kernel_version}}`.

`/usr/portage` is removed during cleanup to save space, so you will need to run the following to obtain the latest Portage snapshot if you want to install packages:


```
emerge-webrsync && emerge --sync
```

See https://github.com/symbols-worldwide/gentoo-packer/