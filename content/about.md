---
title: "About"
date: 2022-07-29
---
Hi!
I'm a 22 year old Data Science student, currently pursuing my Master's of Science degree from [Central University of Rajasthan](curaj.ac.in) [2021-2023]. I completed my Bachelor of Science in Computer Science and Mathematics from Vidyasagar University in 2020. I am interested in Photography, Compilers, Linux kernel and operating systems.

Since 2017, I have been working mainly on Linux Kernel and Operating Systems. Below are some of the projects I have worked on. If you have any questions, feel free to contact me.

## Linux Kernels

I first started working with Linux Kernels on 2019 under the name [Azure](https://en.wikipedia.org/wiki/Azure_(color)) and I have supported the following Android Devices:

> - YU Yureka/+ (tomato) [EOL-2018]
>  - Asus Zenfone Max Pro M1 (zoot) {EOL-2019}
>  - Redmi Note 7 Pro (violet)

and also for my x86-64 PC
>  - [Archlinux](https://github.com/Panchajanya1999/linux-mainline)

My kernels are focused on stability and perfomance. Each one was built with latest compilers available at the time, keeping in mind to fix warning during compilation.

## Docker - Archlinux
[Archlinux Docker](https://hub.docker.com/r/panchajanya1999/archlinux/tags), used in CI for Kernel and ToolChain compilation. It has all the necessary packages to build a Linux Kernel and it is updated daily.

## Compilers
I actively maintain a [LLVM/Clang](https://llvm.org/) and a [GCC](https://gcc.gnu.org/) compiler for my personal usage.
The binaries are built from personal forks of [ClangBuiltLinux/tc-build](https://github.com/ClangBuiltLinux/tc-build) and [mvaisakh's gcc-build](https://github.com/mvaisakh/gcc-build).

> Clang [\[Source\]](https://github.com/Panchajanya1999/tc-build) [\[Binary\]](https://gitlab.com/Panchajanya1999/azure-clang)

> GCC [\[Source}](https://github.com/Panchajanya1999/gcc-build)

## Miscellaneous Works

### [myscripts - Formative Kernel Building Script](https://github.com/Panchajanya1999/myscripts)
This is a script which I use to compile custom kenel for my devices. It was written keeping in mind about compiling a standalone kernel in CI Deployments.