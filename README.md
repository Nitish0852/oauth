# oauth
 a secure web application that uses GitHub OAuth login. A GitHub user to see his/her activity in an infinite scroll fashion.

###Working
Download the repo and switch to the downloaded directory.

Register your new application on Github : https://github.com/settings/applications/new. In the "callback URL" field, enter "http://localhost:8080/oauth-callback". Once you register, you will get a client ID and client secret.

Create a `.env` file the working directory and save 
```
PORT=8080
GITHUB_CLIENT_ID='client_id'
GITHUB_SECRET='<client_secret>'
```


To Download Dependencies
```
npm install
```

To run 
```
node server.js
```

Lastly Navigate to http://localhost:8080 on your browser.
