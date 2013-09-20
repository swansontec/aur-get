# aur-get

This is a simple utility that downloads and unpacks build scripts from the [Arch User Repository](https://aur.archlinux.org/). While there are many AUR helpers that can automatically download, build, install, and update software from the AUR, there are times when it makes sense to build the software yourself. For example:

* You want to modify the package somehow
* You only want to download and build once, and then install the results on multiple computers
* You want to see how the build scripts work
* You want to verify that the build instructions are safe

If you already know the package name, the `aur-get` utility can download it directly from the command line, saving a trip to the web browser.
