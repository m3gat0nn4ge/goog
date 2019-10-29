# goog
Command line Google Docs / Drive access

### Configuration
For an application to access the Google API's, you must have an account with API access enabled.

1. Navigate to: https://console.developers.google.com
2. Create a project, the name is unimportant
3. Browse the API library and enable API's for Drive, Docs, and Sheets (at this time)
4. Profit

Goog is a python app so we need to install the Google client libraries for python:

```pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib```


