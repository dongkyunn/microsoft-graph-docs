---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let res = await client.api('/users/delta')
	.header('Prefer','return=minimal')
	.select('displayName,jobTitle,mobilePhone')
	.get();

```