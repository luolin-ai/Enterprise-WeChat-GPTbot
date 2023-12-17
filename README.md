# Enterprise-WeChat-GPTbot
基于最新企业微信发布的的4.1.13.6002版本外部群的微信机器人，支持FASTgpt

重要的事情说三遍，
运行脚本请退出梯子
运行脚本请退出梯子
运行脚本请退出梯子


# 企业微信机器人使用教程：
1.打开项目下载最新企业微信发布的的4.1.13.6002版本 下载：https://dldir1.qq.com/wework/work_weixin/WeCom_4.1.13.6002.exe

### 功能介绍：
记录活动: 这个机器人会记下它所做的所有事情，就像写日记一样，这样如果出了问题，可以回头查看它写的日记找出问题所在。
读取设置: 这个机器人在开始工作之前会查看一个叫做“config.ini”的文件，这个文件就像是它的指令手册，告诉它需要什么信息和规则来工作。
设置工作环境: 机器人为自己设置一个工作环境，这样它知道在什么情况下应该报告错误。
学习语言工具: 机器人会下载一些学习材料，以便更好地理解和处理人类的语言。
发送消息: 机器人有能力向某个地方（API）发送消息，并从那里得到答复，就像发短信给一个朋友并等待他的回复。
打开企业微信: 机器人会自动打开一个叫企业微信的程序，并等待你用账号登录。
处理聊天: 当机器人在企业微信中收到消息时，它会根据它的指令手册（config.ini文件）来决定如何回应，比如它可能只回应来自特定好友的消息。
检查消息长度: 如果收到的消息太长（超过200个字符），机器人会回复说消息太长了。
记住聊天内容: 机器人会记得和你聊天的内容，这样它可以根据之前的聊天回复，而不是每次都从头开始。
回复消息: 当机器人收到消息时，它会想出一个回复，然后发送给发消息的人。
保持警觉: 机器人会一直保持开启状态，随时准备接收和回复消息，除非你告诉它停止。

群管理配置：当自己在群发消息的时候还会脚本提示窗里有”r“开头的一串数字，这是群的id
![c19c0448b894ae36253c343ef82f9c2](https://github.com/luolin-ai/Enterprise-WeChat-GPTbot/assets/135555634/983c4ed8-0eda-4e28-bf1c-243585e33764)

### 功能介绍：

[API]
api_key：这是您用来访问某些在线服务的密钥。例如，如果您的机器人使用在线AI服务来生成回复，您需要将其API密钥填写在这里。
app_id：如果API服务要求一个应用ID，可以在此填写。
[PrivateChat]
whitelist：您可以设置机器人只回复来自特定好友的消息。将好友的用户名或昵称以逗号分隔列出。如果您希望机器人回复所有好友的消息，请填写 all。
ad_signature：这是机器人在私聊消息中自动添加的签名或广告。例如，“回复由机器人提供”。
interactions_limit：设置机器人在私聊中每个对话的回复次数限制。
[GroupChat]
whitelist：您可以设置机器人只回复来自特定群组的消息。将群组ID以逗号分隔列出。如果您希望机器人回复所有群组的消息，请填写 all。
ad_signature：这是机器人在群聊消息中自动添加的签名或广告。例如，“回复由机器人提供”。
interactions_limit：设置机器人在群聊中每个对话的回复次数限制。
trigger_word：设置触发词，当群聊消息中包含此词时，机器人才会回复。
[Conversation]
use_common_conversation：设置是否在不同的对话中使用共同的对话历史。True 表示共享历史，False 表示每个对话有其独立的历史。


# 开始
2.配置，
打开 https://ai.aiwis.cn/ 网站，点击创建ai
![image](https://github.com/luolin-ai/Enterprise-WeChat-GPTbot/assets/135555634/49b7e76a-2908-4431-a9e1-26ceb1702ebb)
进入网站点击新建应用，点击生成key
![微信截图_20230703101749](https://github.com/luolin-ai/Enterprise-WeChat-GPTbot/assets/135555634/2d4fbf96-879d-4c71-aae8-04e152616829)
![image](https://github.com/luolin-ai/Enterprise-WeChat-GPTbot/assets/135555634/bb9e7f3c-0e91-4cd2-ab2f-13d35a92b3e3)
![image](https://github.com/luolin-ai/Enterprise-WeChat-GPTbot/assets/135555634/a3987928-8271-4fd2-8b5f-c7af94360ecc)

# 扫码入交流群
![wxqun jpg](https://github.com/luolin-ai/FastGPT-Enterprise-WeChatbot/assets/135555634/a7b43983-bf71-4c29-b4e1-c0f15a039cf1)

