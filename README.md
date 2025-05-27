{
    "id": "com.okcam.ookcam",
    "name": "小鹰看看-广告拦截",
    "groups": [
        {
            "key": 0,
            "name": "开屏广告",
            "activityIds": "com.okcam.ookcam.SplashActivity",
            "rules": [
                {
                    "key": 0,
                    "quickFind": true,
                    "matches": [
                        "[vid='adsFl']",
                        "[text^='跳过' && clickable=true]"
                    ],
                    "action": "click"
                }
            ]
        }
       
    ]
}
