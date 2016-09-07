# aurelia-registry

[![ZenHub](https://raw.githubusercontent.com/ZenHubIO/support/master/zenhub-badge.png)](https://zenhub.io)
[![Join the chat at https://gitter.im/aurelia/discuss](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/aurelia/discuss?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

A registry of Aurelia plugins, cli plugins, gists and other awesome goodies you can use with Aurelia and its tools.

> To keep up to date on [Aurelia](http://www.aurelia.io/), please visit and subscribe to [the official blog](http://blog.aurelia.io/) and [our email list](http://durandal.us10.list-manage1.com/subscribe?u=dae7661a3872ee02b519f6f29&id=3de6801ccc). We also invite you to [follow us on twitter](https://twitter.com/aureliaeffect). If you have questions, please [join our community on Gitter](https://gitter.im/aurelia/discuss). If you would like to have deeper insight into our development process, please install the [ZenHub](https://zenhub.io) Chrome or Firefox Extension and visit any of our repository's boards. You can get an overview of all Aurelia work by visiting [the framework board](https://github.com/aurelia/framework#boards).

## How does it work?

The registry is a list of plugins that can be used with Aurelia.  They will be located and downloaded with JSPM on the registry / location that is specified.

## Adding to the registry

* Add your plugin in **alphabetical order** based on the name property
* Fork this registry and create a PR

To add your plugin to the registry, please make to follow the following JSON format -

```language-javascript
{
  "plugins": [
    {
      "name": "NAME-OF-YOUR-PLUGIN",
      "endpoint": "github", /* github, npm, etc... */
      "location": "aurelia/validation", /* where is it on that endpoint? */
    }
  ]
}
```
