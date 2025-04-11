### Vouch API Authentication

```
Authorization: Bearer YOUR_VOUCH_API_KEY
Content-Type: application/json
```

```js
const axios = require('axios');

const VOUCH_API_KEY = process.env.VOUCH_API_KEY;

const client = axios.create({
  baseURL: 'https://api.vouchfor.co.uk/v1',
  headers: {
    Authorization: `Bearer ${VOUCH_API_KEY}`,
    'Content-Type': 'application/json'
  }
});
```

