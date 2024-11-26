# .github

存储库命名规则（后续）：

主体.项目名称.分类.Main/扩展名称

第一段主体：
  SQC
第二段项目名称：
  类似JMQX\SCM等
第三段分类：
  接口=Api
  APP=APP
      AndroidApp
      IosApp
  微信小程序=WXMP
  H5端=H5
  管理后台=Admin
  页面前台=Web
第四段：
  主要的=Main
  扩展的=XXXExt，例如AiExt，默认的扩展H5Ext等
  游戏的可以用Game开头

例如肌秘星球
主API：SQC.JMXQ.Api.Main
AI API服务：SQC.JMXQ.Api.Ai
主APP框架：SQC.JMXQ.IosApp.Main      如果划分IOS和安卓
          SQC.JMXQ.AndroidApp.Main
          SQC.JMXQ.App.Main         如果不划分
APP H5扩展：
          SQC.JMXQ.App.H5Ext        默认的扩展
          SQC.JMXQ.App.xxxExt       特定的扩展
微信小程序主框架：
          SQC.JMXQ.WXMP.Main
          SQC.JMXQ.WXMP.GameXXL     消消乐游戏
