# Coyote C++

**Coyote C++** is a tool that performs code coverage calculation and test case generation for source code fully automatically with just one click. This tool automatically generates test harness (test stubs, test drivers, test cases) for source code written in C/C++. **Coyote C++** creates test cases that can cover the maximum executable paths based on concolic execution and uses them to calculate coverage. You can view these results directly in the user interface or export them as reports (CSV, HTML) for inspection.

The version of **Coyote C++** provided on this page is available as shareware and can be used until **May 2024**.

# Requirements
**Coyote C++** is only available in environments with an internet connection, and it has been tested to operate on the X86_64 architecture with the following operating systems.
- Ubuntu 20.04
- Ubuntu 22.04

**Coyote C++** is provided in the form of a Snap package, so Snap installation on the operating system is a prerequisite. Additionally, **Coyote C++** is designed to calculate coverage for projects that can be built. In other words, basic package installation for building is required. And especially in Ubuntu 22.04, the .NET package needs to be installed. The necessary installation commands prior to operation vary depending on the operating system and are as follows:

## Ubuntu
1) Environment Setup for Building
```
sudo apt install -y build-essential
```
2) Install .NET package in Ubuntu 22.04
```
sudo apt-get update
sudo apt-get install -y apt-transport-https
sudo apt-get update
sudo apt-get install -y dotnet-sdk-6.0
```

# Download
The program for each operating system can be downloaded from the following addresses. Please note that these files are only compatible with AMD64. 

- Ubuntu 20.04: [Download](https://coyotemanager.blob.core.windows.net/coyote/COYOTE_4.6.1_ubuntu20.snap) [SHA-256: 222a8a0751a7e6d9af97e8a6f7a90c42861c52327bb87f03a1f291829dea05e7]

- Ubuntu 22.04: [Download](https://coyotemanager.blob.core.windows.net/coyote/COYOTE_4.6.1_ubuntu22.snap) [SHA-256: d92f834823f2f825e62f4a71d1b5fdc24eb48e8d1acc75fc20f2bd19dc307c74]

# How to install
**Coyote C++** downloaded snap package via the provided link addresses can be installed using the following command. 

## Ubuntu
```
snap install --dangerous --classic COYOTE_4.6.1_amd64.snap
```
>--dangerous: This option is need the package is not installed through the snap store.

# How to use
Detailed usage instructions can be found in the [User Guide](https://coyotemanager.blob.core.windows.net/coyote/COYOTE_C++_User_Guide.pdf).

# Support C/C++ language syntax
**Coyote C++** supports the C/C++ syntax based on Clang 12. A more detailed list of supported syntax can be found on the Clang homepage([C](https://clang.llvm.org/c_status.html), [C++](https://clang.llvm.org/cxx_status.html)).

# Contact
For bug reports, issues encountered during use, or any inquiries related to **Coyote C++**, please contact us at coyote@codemind.co.kr.
