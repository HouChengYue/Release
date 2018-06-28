**<h1>优师云项目历史包</h1>**

 最新版命名为 youshiyun.apk

  历史版本 XXX(版本号)_XXX(时间)

  最新版下载地址 https://106.14.38.102:8443/raw/Apks.git/master/youshiyun.apk
 <h2>updata.json</h2>
  格式如下
 <pre> <code> {
    &quot;code&quot;: 200,
    &quot;message&quot;: &quot;请求成功!&quot;,
    &quot;data&quot;: {
      &quot;versionCode&quot;: 30,
      &quot;versionName&quot;: &quot;1.0.2.20.30&quot;,
      &quot;isFous&quot;: false,
      &quot;date&quot;: &quot;2018-6-22&quot;,
      &quot;apkUrl&quot;:&quot;&quot;,
      &quot;size&quot;:&quot;31M&quot;,
      &quot;updataDetail&quot;: &quot;1、新功能：\n\t扫描二维码进项目（仅学员）\n\t项目中地理位置定位签到\n2、优化功能及bug修复\n\t我的个人资料优化\n\t注册码进入项目优化\n\t发布活动权限优化\n\t快速注册/登录及个人信息补全\n\t等若干bug&quot;
    }
  }
  </code></pre>
   含义
   <pre>{
     &quot;code&quot;: 200,                      //请求状态码
     &quot;message&quot;: &quot;请求成功!&quot;,           //请求状态
     &quot;data&quot;: {                         //更新数据
       &quot;versionCode&quot;: 30,              //版本号
       &quot;versionName&quot;: &quot;1.0.2.20.30&quot;,   //版本名
       &quot;isFous&quot;: false,                //是否强制更新
       &quot;date&quot;: &quot;2018-6-22&quot;,            //版本日期
       &quot;apkUrl&quot;:&quot;&quot;,                    //apk 地址 没有则默认最新下载地址
       &quot;size&quot;:&quot;31M&quot;,                   //包大小   最后是描述
       &quot;updataDetail&quot;: &quot;1、新功能：\n\t扫描二维码进项目（仅学员）\n\t项目中地理位置定位签到\n2、优化功能及bug修复\n\t我的个人资料优化\n\t注册码进入项目优化\n\t发布活动权限优化\n\t快速注册/登录及个人信息补全\n\t等若干bug&quot;
     }
   }
</pre>

