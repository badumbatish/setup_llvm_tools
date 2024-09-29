# setup_llvm_tools

## Overview
A GitHub Action to fetch LLVM toolings for your CI/CD. 


Given:
- A download link (that includes something like *****.tar.xz)
- Destination for installation (such as /usr/local)

It will
- Download the llvm package.
- Extract to the correct folder
- Set up environment variables such as: LLVM_ROOT_DIR, PATH, LD_LIBRARY_PATH

The action is set up since I couldn't find a way to install mlir-tblgen via apt install or anything like that

Example usage can be found in: .github/workflows

The Action is run with "composite" mode.
## Contributing & Discussions

Please open an issue/pr for feature requests and questions. Every issue will gladly be taken a look at.

