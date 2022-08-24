---
title: Linux 6.0-rc2
date: 2022-08-24
---

Linux 6.0-rc2 has been released as the new weekly test candidate by Linus Torvalds and is the second release candidate for the next major release of Linux. 

Linus wrote of the new release 6.0-rc2 in the release announcement:
> Nothing particularly interesting here, rc2 tends to be fairly calm with people taking a breather and not yet having found a lot of bugs. 

> The most noticeable fix in here is likely the virtio reverts that fixed the problem people had with running tests on the google cloud VMs, which was the "pending issue" that we had noticed just as the merge window was closing. And it's noticeable - and notable - mainly because that problem then kept people from running some of the automated tests and thus finding other issues. 

> But obviously there's a lot of other things in here too, as per the appended shortlog. The diffs are somewhat dominated by the amd gpu fixes - they missed the "drm fixes" pull during the merge window, so there were a bunch of fixes pending on that side. But there's some network driver fixes, some filesystem fixes (btrfs and a late ntfs3 half-fixes-half-updates pull), and the usual set of architecture fixes and other core code (mainly networking).

#### **Download the Linux 6.0-rc2 release for your x86_64 architecture machine running Archlinux**

[Kernel](https://github.com/Panchajanya1999/linux-mainline/releases/download/v6.0-rc2/linux-azure-6.0.0-3-x86_64.pkg.tar.zst)

[Kernel Headers](https://github.com/Panchajanya1999/linux-mainline/releases/download/v6.0-rc2/linux-azure-headers-6.0.0-3-x86_64.pkg.tar.zst)

#### **Steps to Install Linux 6.0-rc2 on Archlinux**
**Note:** This is a test kernel and is not recommended for daily use.
> 1. Download the kernel and kernel headers from the links above.
> 2. Install the kernel headers using `pacman -U linux-azure-headers-6.0.0-3-x86_64.pkg.tar.zst` command.
> 3. Install the kernel using `pacman -U linux-azure-6.0.0-3-x86_64.pkg.tar.zst` command.
> 4. Generate GRUB config using `grub-mkconfig -o /boot/grub/grub.cfg` command (If you are using GRUB as your bootloader). 
> 5. Reboot your system.

#### **Verify the Linux 6.0-rc2 kernel version**
> Run `uname -r` command to verify the kernel version.

You will see whether you are running the Linux 6.0-rc2 kernel or not.

#### **See Also**
* [Linux 6.0-rc2 on LKML [Linux Kernel Mailing List]](https://lkml.org/lkml/2022/8/21/359)