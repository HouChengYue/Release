优师云项目历史包
       用于找到历史版本用的
       最新版命名为 youshiyun.apk
       历史版本 XXX(版本号)_XXX(时间)
       最新版下载地址 https://106.14.38.102:8443/raw/Apks.git/master/youshiyun.apk
      ** updata.json
       格式如下
       {
         "code": 200,
         "message": "请求成功!",
         "data": {
           "versionCode": 30,
           "versionName": "1.0.2.20.30",
           "isFous": false,
           "date": "2018-6-22",
           "apkUrl":"",
           "size":"31M",
           "updataDetail": "1、新功能：\n\t扫描二维码进项目（仅学员）\n\t项目中地理位置定位签到\n2、优化功能及bug修复\n\t我的个人资料优化\n\t注册码进入项目优化\n\t发布活动权限优化\n\t快速注册/登录及个人信息补全\n\t等若干bug"
         }
       }
        含义
        {
          "code": 200,                      //请求状态码
          "message": "请求成功!",           //请求状态
          "data": {                         //更新数据
            "versionCode": 30,              //版本号
            "versionName": "1.0.2.20.30",   //版本名
            "isFous": false,                //是否强制更新
            "date": "2018-6-22",            //版本日期
            "apkUrl":"",                    //apk 地址 没有则默认最新下载地址
            "size":"31M",                   //包大小   最后是描述
            "updataDetail": "1、新功能：\n\t扫描二维码进项目（仅学员）\n\t项目中地理位置定位签到\n2、优化功能及bug修复\n\t我的个人资料优化\n\t注册码进入项目优化\n\t发布活动权限优化\n\t快速注册/登录及个人信息补全\n\t等若干bug"
          }
        }
