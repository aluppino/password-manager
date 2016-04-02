# password-manager
Node.js based password manager with encryption

## Usage
Create a new account/password entry:
```
node app.js create -n accountName -u userName -p accountPassword -m masterPassword
```
Get an existing account/password entry:
```
node app.js get -n accountName -m masterPassword
```
