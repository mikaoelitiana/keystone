## Keystone Tests

#### Server
to test the ssl configuration you must tell node to ignore certificate errors
```javascript
NODE_TLS_REJECT_UNAUTHORIZED=0 mocha lib/server.https.test.js 
```
