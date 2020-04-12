> 元项目: [isecret/Hola](https://github.com/isecret/Hola)
> 本项目对其进行简化。

**去除的功能:**
1. InstantClick
2. Gitment
3. tencent_analytics

**集成的功能:**

1. 添加阿鲁表情包(改功能是原项目作者在[其博客](https://blog.wangmao.me/alu-face.html)发布的表情包功能，我觉得好玩就添加到里面去了

2. 添加 Valine 评论系统，详细请到 _config.yml 文件中配置

   ```
   valine:
     enable: true
     app_id: #你的valine app_id
     app_key: #你的valine app_key
     notify: false   #邮件提醒设置
     verify: false   #验证码设置
     placeholder: ヾﾉ≧∀≦)o快来评论一下吧!
     avatar: monsterid  #头像设置
     pageSize: 10
     visitor: true
   ```

   
