To make remote containers work in VSCode you have to copy the `devcontainer.json.template` file in this folder to `devcontainer.json` and replace `<ABSOLUTE PATH TO YOUR REPO HERE>` with the absoulte to your git clone.
This is due to [issue $422](https://github.com/microsoft/vscode-remote-release/issues/442) of the vscode-remote plugin.