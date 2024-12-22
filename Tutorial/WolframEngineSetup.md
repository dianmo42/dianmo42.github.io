# Setup Wolfram Engine in VSCode

1. Install the [Wolfram Language](https://marketplace.visualstudio.com/items?itemName=WolframResearch.wolfram) extension
2. Open command palette with `Ctrl+Shift+P` or `F1`, and run `> Wolfram Language: Download Wolfram Engine`. This should open the [download page](https://www.wolfram.com/engine/) of the engine.
3. Download and install Wolfram Engine. To activate it, you will need to register an account.
4. Enable Wolfram kernel in `Settings > Extensions > Wolfram`, or simply add `"wolfram.notebook.kernelEnabled": true` in `settings.json`.
5. Restart VSCode, and you should be able to use the powerful Wolfram Engine now (reboot you PC if restart vscode doesn't working).