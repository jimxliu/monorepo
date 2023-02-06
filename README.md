# monorepo
All my personal projects will be stored in this repo

## Installation
### Install Bazel ([reference](https://bazel.build/install/os-x#install-on-mac-os-x-homebrew))
#### Step 1: Install Homebrew on macOS
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
echo "export PATH=$PATH:/opt/homebrew/bin" >> ~/.zshrc && . ~/.zshrc
```
#### Step 2: Install Bazel via Homebrew
Install the Bazel package via Homebrew as follows:
```
brew install bazel@6
```
All set! You can confirm Bazel is installed successfully by running the following command:
```
bazel --version
```
[Optional] Once installed, you can upgrade to a newer version of Bazel using the following command:
```
brew upgrade bazel
```
### Install Buildifier
[buildifier](https://github.com/bazelbuild/buildtools/tree/master/buildifier) is a tool for formatting bazel BUILD and .bzl files with a standard convention.

After installing buildifier, install **Bazel** vscode extension (arthored by The Bazel Team)


