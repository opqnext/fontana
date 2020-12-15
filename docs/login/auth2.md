### URL
`/v2/login/auth2`

### 参数
|字段名|说明|示例|
|-|-|-|
|code | wx.login获取的code码 | r3NPRdgdTB03OCYG|

### 返回值
```
{
	"code": 0,
	"message": "success",
	"timestamp": 1608012806,
	"data": {
		"lu_id": "100000",                    //用户id
		"token": "46tCUDf8PlTIMtfSPqxTwA=="   //token
	}
}
```

### 参考:
auth.code2Session:
https://developers.weixin.qq.com/miniprogram/dev/api-backend/open-api/login/auth.code2Session.html

小程序登录:
https://developers.weixin.qq.com/miniprogram/dev/framework/open-ability/login.html
