# vscode-chatgpt

This is a fork of the original version that enables local vsix builds and API
usage of GPT4.

Tons of props to @gencay for originally shipping the project!

# How to run

- Clone the repository to your local machine
- On the root directory, run `yarn` command to install the dependencies listed in `package.json`
- Install `vsce`: `npm install -g @vscode/vsce`
- Create package: `npm run release`
- Install the extension: `code --install-extension  vscode-chatgpt-6.0.0.vsix`
- Set your API key with the setting `chatgpt.gpt3.apiKey`
- Set API key auth: `"chatgpt.method": "GPT3 OpenAI API Key"`
- Enjoy GPT4 :)
