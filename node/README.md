### smartcar-node demo
[Running our demo app](https://support.smartcar.com/getting-started/run-our-demo-app)

To run the demo:
```bash
git clone https://github.com/smartcar/demo.git
cd demo/node
npm install
```

For security, you must configure http://localhost:8000/callback as a redirect uri in Smartcar's developer portal.
```
export SMARTCAR_CLIENT_ID=<your-client-id>
export SMARTCAR_SECRET=<your-client-secret>
node app.js
```

Navigate to http://localhost:8000
```
