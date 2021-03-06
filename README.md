# EVMSpec-VsCodeExtension README

VS.Code extension for syntax highlighting certora's specification files (.spec, .cvl).

Requires an VS.Code extension for solidity syntax highlighting to be already installed and enabled; tested with juanblanco.solidity from the marketplace.

Installation: 

Either
 - Download zip from github, copy the whole EVMSpec-VsCodeExtension folder into the VS.Code extensions folder, or
 - clone this repo into that folder (i.e., cd into the folder and run `git clone https://github.com/FormalContractVerification/EVMSpec-VsCodeExtension.git`) (for updating to the current version, just run `git pull`).

Depending on your operating system, the VS.Code extensions folder should be in one of the following places.
 * Windows %USERPROFILE%\.vscode\extensions
 * macOS ~/.vscode/extensions
 * Linux ~/.vscode/extensions

Note this is a very early version, it is supposed to provide some basic syntax highlighting; the highlighting might be "off" in some places, more robust versions are still to come.
