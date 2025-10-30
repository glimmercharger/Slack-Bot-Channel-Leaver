# 🧹 Slack Bot Channel Leaver

A simple Python script that makes your Slack bot leave all channels in your workspace automatically.

(The script is located in the ```main``` folder.)

## ⚙️ Setup

- Clone repo 
  ```git clone https://github.com/glimmercharger/Slack-Bot-Channel-Leaver```
  
- Install dependencies
  Run the following commands to install the required packages:

```pip install slack slack_sdk```


- Add your Slack Bot Token
  Open ```Leave-Slack-Channels-bot-Script.py``` and replace the placeholder token in the configuration section with your own Slack Bot Token.
  _a ```.env``` file can be used to prevent tokens being stolen_

- Run the script
  Simply execute the file, and your bot will start leaving all channels in the workspace.

##💡 Notes

Make sure your bot has the necessary permissions (like ```channels:read``` and ```groups:write```) in your Slack app configuration.

You can modify the script to skip certain channels if you want your bot to stay in a few.

## 👤 Author

[Will K](https://github.com/glimmercharger)

Edited by [Freddie](https://github.com/hippogriff101)
