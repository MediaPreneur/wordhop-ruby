# [Wordhop](https://www.wordhop.io) Messenger Bot Ruby Example

This is a simple Messenger bot with Wordhop integration example based on [facebook-messenger](https://github.com/hyperoslo/facebook-messenger)

### Sign Up With Wordhop

You'll need an API key from Wordhop, as well as a Client Key for each Chatbot.  You can get both of those (free) when you add [Wordhop for Slack](https://slack.com/oauth/authorize?scope=users:read,users:read.email,commands,chat:write:bot,channels:read,channels:write,bot&client_id=23850726983.39760486257) via through a conversation with the Wordhop bot. 

### Register for an Access Token

You'll need to setup a [Facebook App](https://developers.facebook.com/apps/), Facebook Page, get the Page Access Token and link the App to the Page before you can really start to use the Send/Receive service.
[This quickstart guide should help](https://developers.facebook.com/docs/messenger-platform/quickstart)

### Installation

```bash
$ gem install facebook-messenger ; gem install wordhop
```

### Usage

Set your environmental variables for `WORDHOP_API_KEY`, `WORDHOP_CLIENT_KEY`, `ACCESS_TOKEN`.

```bash
$ export WORDHOP_API_KEY=xxxxxxxxxxxxxxxxxxxx
$ export WORDHOP_CLIENT_KEY=xxxxxxxxxxxxxxxxxxxx
$ export ACCESS_TOKEN=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```

Run the following command to get your bot online:

```bash
$ rackup
```
