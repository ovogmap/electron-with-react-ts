### Package Manager

`npm`, `yarn`

### Run Electron with Development Mode

Run `npm run start` or `yarn start` electron app.

```json
{
  "scripts": {
    "start": "concurrently \"cross-env NODE_ENV=development BROWSER=none yarn react-start\" \"wait-on http://localhost:3000 && electron .\""
  }
}
```
