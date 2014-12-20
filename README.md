# Slack API client [![License](https://poser.pugx.org/cleentfaar/slack/license.svg)](https://packagist.org/packages/cleentfaar/slack)

Access your Slack Team's API through PHP.

*If your project is built on top of the Symfony Framework, consider using the bundle I created for it: [SlackBundle](https://github.com/cleentfaar/CLSlackBundle).
*If you would like to access the Slack API from the command-line, consider installing the [slack-cli](https://github.com/cleentfaar/slack-cli) package.*

[![Build Status](https://secure.travis-ci.org/cleentfaar/slack.svg)](http://travis-ci.org/cleentfaar/slack)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/cleentfaar/slack/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/cleentfaar/slack/?branch=master)
[![Code Coverage](https://scrutinizer-ci.com/g/cleentfaar/slack/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/cleentfaar/slack/?branch=master)<br/>
[![Latest Stable Version](https://poser.pugx.org/cleentfaar/slack/v/stable.svg)](https://packagist.org/packages/cleentfaar/slack)
[![Total Downloads](https://poser.pugx.org/cleentfaar/slack/downloads.svg)](https://packagist.org/packages/cleentfaar/slack)
[![Latest Unstable Version](https://poser.pugx.org/cleentfaar/slack/v/unstable.svg)](https://packagist.org/packages/cleentfaar/slack)


### Documentation

- [Getting started](Resources/doc/getting-started.md) - Before you use this library, you need to generate a token or setup oAuth.
- [Installation](Resources/doc/installation.md) - Information on installing this library through composer or as a git submodule.
- [Usage](Resources/doc/usage.md) - A few simple examples on how to access the Slack API using this library
- [API methods](Resources/doc/methods/index.md) - Detailed information on each of Slack's API methods and how to access them using this library's `Payload` classes.


### Features
- Access all of Slack's API methods with just a few lines of code (see [usage documentation](Resources/doc/usage.md))
- Classes follow the same definitions as described in the [official documentation](https://api.slack.com) (with a few exceptions where I think it would make a better distinction).
- Data between you and Slack is serialized using the [JMS Serializer](https://github.com/jms/serializer) package,
allowing for complex objects to be sent while maintaining an OO-approach.
- Code has been highly abstracted to support re-use in more specific implementations (see [SlackBundle](https://github.com/cleentfaar/CLSlackBundle))


### Further reading

I've done my best to include links to the official documentation in the code where appropriate.

Still, you should really check out the [API documentation](https://api.slack.com/) of Slack yourself to get a better
understanding of exactly what each API method does and what data it will return.

If you feel there is some part of this package that you would like to see documented in more detail, please don't hesitate
to create an issue for it.


### Contributing

Got a good idea for this project? Found a nasty bug that needs fixing? That's great!
Before submitting your PR though, make sure it complies with the [contributing guide](Resources/doc/contributing.md) to
speed up the merging of your code.


### Related packages

- [SlackCli](https://github.com/cleentfaar/slack) - CLI application for all of the Slack API methods.
- [SlackBundle](https://github.com/cleentfaar/CLSlackBundle) - Symfony Bundle providing integration with this library package.


### Attributions

- The [Slack](https://slack.com/) staff, for making an awesome product and very clean API documentation.