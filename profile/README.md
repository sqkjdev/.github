## Hi there 👋

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
# 存储库命名规则

### 格式主体.项目名称.分类.Main/扩展名称
- 第一段主体：SQC
- 第二段项目名称：
  类似JMQX\SCM等
- 第三段分类：
    - 接口=Api
    - APP=APP、AndroidApp、IosApp
    - 微信小程序=WXMP
    - 支付宝小程序=ZFBMP
    - 支付宝、微信等公用小程序=MP
    - H5端=H5
    - 管理后台=Admin
    - 页面前台=Web
- 第四段：
      主要的=Main
      扩展的=XXXExt，例如AiExt，默认的扩展H5Ext等
      游戏的可以用Game开头

### 例如肌秘星球

- 主API：SQC.JMXQ.Api.Main
- AI API服务：SQC.JMXQ.Api.Ai
- 主APP框架：
  - SQC.JMXQ.IosApp.Main      如果划分IOS和安卓
  - SQC.JMXQ.AndroidApp.Main
  - SQC.JMXQ.App.Main         如果不划分
- APP H5扩展：
  - SQC.JMXQ.App.H5Ext        默认的扩展
  - SQC.JMXQ.App.xxxExt       特定的扩展
- 微信小程序主框架：
  - SQC.JMXQ.WXMP.Main
  - SQC.JMXQ.WXMP.GameXXL     消消乐游戏
  - SQC.
