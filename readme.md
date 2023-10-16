# Set up local environment

1. Download and install [VS Code](https://code.visualstudio.com/).
2. Install the REST Client extension for VS Code from the [marketplace](https://marketplace.visualstudio.com/items?itemName=humao.rest-client).
3. Adjust the environment variables in the [settings.json](./.vscode/settings.json) file.
4. Set the environment for the REST Client extension to "dev":
   1. Open the VS Code command palette by using the shortcut `Cmd+Shift+P` or by navigating to `View -> Command Palette`.
   2. Type "Rest Client: Switch Environment" in the command palette search bar and select it.
   3. Choose the "dev" environment from the available options.
5. Now you can run any requests using the REST Client extension.
![Alt text](.docs/sendrequest.png)

# Import from a Postman collection
To convert a Postman Collection to a REST Client, you can use the tool available at https://github.com/alfathdirk/postman-to-vscode-rest-client. Follow these steps to achieve it:

1. Install the tool globally by running the command `npm -g i vsrest-postman-generator`.
2. Execute the following command: `vsrest {file-postman}.json`, where `{file-postman}` is the name of your Postman Collection file.