# Run the API

```
npm i
npm start
```

It will start the app at http://localhost:3000.

# Expose API Publicly

If you want API to be publicly available:

```
npm run start:withTunnel
```

To specify subdomain of your choice:

```
npm start
npm run start:tunnel -- --subdomain=example-subdomain
```
