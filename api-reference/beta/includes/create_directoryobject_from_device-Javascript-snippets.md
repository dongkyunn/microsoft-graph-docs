
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const directoryObject = {
  directoryObject: {
  }
};

let res = await client.api('/devices/{id}/registeredUsers/$ref')
	.version('beta')
	.post({directoryObject : directoryObject});

```