# goog
Command line Google Docs/Drive/Sheets/... access

### Configuration
For an application to access the Google API's, you must have an account with API access enabled.

1. Navigate to: https://console.developers.google.com
2. Create a project, the name is unimportant
3. Browse the API library and enable API's for Drive, Docs, and Sheets (at this time)
4. Click Credentials in the left frame, then create an Oauth2 client ID. Use the type Other, download it as credentials.json in the local goog repo
5. The first time you execute it, you will be provided with a link to open in a browser and login/allow access
6. Profit


Goog is a python app so we need to install the Google client libraries for python.

```pip3 install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib```

The command above is for Fedora, use the appropriate command for your system.

