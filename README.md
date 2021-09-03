# Where the ISS at?

The objective is to practice, plan and automate [Where the ISS at?](https://wheretheiss.at/w/developer)  using [Postman](https://www.postman.com/).

### Test Design Guidelines
* No authentication required
* Delay requests
* As there is plan to add more satallites, plan and facelitate testing in future
* Parameterise to send requests as a user journey

### Scenarios to automate

## Getting started
1. install [npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
```npm install -g npm```
2. install [Newman CLI tool](https://learning.postman.com/docs/running-collections/using-newman-cli/command-line-integration-with-newman/#:~:text=Newman%20is%20a%20command%2Dline,directly%20from%20the%20command%20line.&text=Newman%20maintains%20feature%20parity%20with,the%20collection%20runner%20in%20Postman.)
``` npm install -g newman ```
3. clone the repository
4. cd to project directory
5. run tests 
```newman run collection.json```

## Next steps
