This plugin allows AKP48Squared to connect to Twitch chat servers.

# Installation

This plugin is included by default on new installations of AKP48Squared. No further installation is needed.

# Config

You'll need to add a new server to your configuration file for each Twitch bot you want to run. An example is shown below.

```
"servers": [
  {
    "plugin": "twitch",
    "config": {
      "connection": {
        "reconnect": true // should we reconnect automatically?
      },
      "identity": {
        "username": "twitch_bot", // See https://help.twitch.tv/customer/portal/articles/1302780-twitch-irc for more info.
        "password": "oauth:we2sm49se21ln6tfkxzvbco7z8uv1s"
      },
      "channels": [
        "#mytwitchchannel"
      ]
    }
  }
]
```

# Issues

If you come across any issues, you can report them on this GitHub repo [here](https://github.com/AKP48Squared/akp48-plugin-discord-server/issues).
