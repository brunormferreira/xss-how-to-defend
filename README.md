# xss-how-to-defend

- Its about executing js code in others users devices.

- An example its submit a malicious js code script on inputs.

- Scripts added with ```innerHTML``` is not loaded.

- The big danger its to run an api call with the auth tokens from localStorage for buy a product or something like this.

- ```onerror``` property in ```<img>``` tags, that trigger error for image fails. So could be to run some ```alert('hacker')``` by example.

- Node ```sanitize``` for help with this on backend side.

- Frameworks already have a security for this.

- ```npm audit``` still help with this, to att all the dependencies.

- You should use the minimum of third party libraries.
