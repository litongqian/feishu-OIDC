- "Application name" field, enter any name you like.
- "Homepage URL" field, enter "http://localhost:8080/ ".
- "callback URL" field, enter "http://localhost:8080/oauth/redirect ".

Once register, you will get a client ID and a client secret.

## Step two: get the code

First, clone the repo.

```bash
$ git clone git@github.com:ruanyf/node-oauth-demo.git
$ cd node-oauth-demo
```

Second, modify the config.

- `index.js`: replace the values of the `clientID` and `clientSecret` variables.
- `public/index.html`: replace the values of the `client_id` variable.

install the dependencies.

```bash
$ npm install
```

## Step three: run the server

Now, run the server.

```bash
$ node index.js
```

Visit http://localhost:8080 in your browser, and click the link to login GitHub.

