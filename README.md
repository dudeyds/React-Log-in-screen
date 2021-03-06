# React-log-in-screen

A basic working example of a login screen using react components to make a single page app..

How to install / use

**Windows**

double click the Index.html file in the file browser for it to automatically open in your default web browser.

**Linux**

If you have a GUI installed, you can follow the same steps as windows to run the html file locally, alternatively you can use the terminal;

From terminal, if you have google chrome installed type:

```google-chrome <filename>.html```

Or if you have firefox:

```firefox  <filename>.html```

**Mac OSX**

double click the Index.html file in the file browser, it will open automatically in your default web browser.

## Test server

To install the test login server you will need to run `npm install` from the `fake-server` folder. This will install packages related to express.js

### Run the server

Run the server using the normal `npm start` command. You should see output like this:

```
C:\src\React-log-in-screen\fake-server>npm start

> fake-server@1.0.0 start C:\src\React-log-in-screen\fake-server
> node .

Fake login server listening at http://localhost:3000
```

When a user authenticates against the server, you should see output like this:

```
Fake login server listening at http://localhost:3000
{ username: 'freddy' }
Login failed for freddy
{ username: 'james' }
Login succeeded for james
```