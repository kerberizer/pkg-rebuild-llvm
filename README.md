# pkg-rebuild-llvm

This script is used to build the [llvm-svn](https://github.com/kerberizer/llvm-svn) and [lib32-llvm-svn](https://github.com/kerberizer/lib32-llvm-svn) packages that I maintain for the [Arch User Repository](https://wiki.archlinux.org/index.php/Arch_User_Repository). The script runs every 6 hours (see the included systemd service and timer) and populates the [llvm-svn](https://wiki.archlinux.org/index.php/Unofficial_user_repositories#llvm-svn) unofficial repo.

The code is likely crude and is not documented at all. It's released in the public domain under the [CC0](http://creativecommons.org/publicdomain/zero/1.0/) license.
