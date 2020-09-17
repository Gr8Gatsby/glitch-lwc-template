# Glitch Lightning Web Components base template
This utilizes the basic server solution provided in the `create-lwc-app` documented on [lwc.dev](https://lwc.dev).

The only major differences to the template to get the application running in glitch is:

* Deal with the proxies that Glitch utilizes and the host check on devServer within `lwc-services.config.js`
* Add in a `start` script which Glitch looks for when a `package.json` file is present
