# 登录资料


## 1、资料接口

- Host
线上：101.201.224.12:8035
- Req
Post /duidui/userinfo/mg

- 请求参数

| 错误码 | 返回msg | 详细描述 |
| ---- | ----|
| 400 | 系统错误，请稍候再试 | 请求参数有误 |


- 请求示例
```js
{
    'ids':[
        100012, 100013
    ]
}
```

- 返回示例
```js
{
    "dm_error": 0,
    "error_msg":"ok"
    "infos":
    [
        {
            "uid": 100012,
            "nick": "asdasdasd",
            "gender":0,
            "portrait":"http://...",
            "share_url":"http://..."
        },
        {
            "uid": 100013,
            "nick": "asdasdasd",
            "gender":0,
            "portrait":"http://...",
            "share_url":"http://..."
        }
    ]
}
```

## 错误码
---

| 错误码 | 返回msg | 详细描述 |
|:-------------:|:-------------|
| 400 | 系统错误，请稍候再试 | 请求参数有误 |
