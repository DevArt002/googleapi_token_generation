### Google APIs token generation

1. Run `npm i` to install the required Node packages.
2. Check `SCOPES` from `./src/index.js`. Currently, supporting `/auth/documents`, `/auth/drive` and `/auth/drive.file` scopes which are needed for google file and google doc manipulation.
3. Get `credentials.json` by following step 1 on `https://developers.google.com/gmail/api/quickstart/nodejs`. Then move it into root folder of this project.
4. Run `node src/index.js`.

    a. Browse to the provided URL in your web browser.

     If you are not already logged into your Google account, you will be prompted to log in. If you are logged into multiple Google accounts, you will be asked to select one account to use for the authorization.
     If you don't have a browser on the machine running the code, and you've selected "Desktop app" when creating the OAuth client, you can browse to the URL provided on another machine, and then copy the authorization code back to the running sample.

    b. Click the Accept button.
    
    c. Copy the code you're given, paste it into the command-line prompt, and press Enter
5. `token.json` file is generated.
