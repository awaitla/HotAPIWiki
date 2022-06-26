# 蓝奏云直链解析

- 接口地址：https://api.hotpe.top/netdisc/lanzou/
- 返回格式：link
- 请求方法：GET



---

参数：

> |   名称    |               描述               |
> | :-------: | :------------------------------: |
> | sharelink |             分享链接             |
> |    pwd    |               密码               |
> |   jump    | ture or false,直接跳转(直接下载) |



---

示例代码：

> 不跳转，有密码：https://api.hotpe.top/netdisc/lanzou/?sharelink=https://wwp.lanzouj.com/i4XYC04s853e&pwd=837i&jump=false
>
> 跳转（直接下载），带密码：https://api.hotpe.top/netdisc/lanzou/?sharelink=https://wwp.lanzouj.com/i4XYC04s853e&pwd=837i&jump=ture
>
> 无跳转，无密码：https://api.hotpe.top/netdisc/lanzou/?sharelink=https://magmastudio.lanzoum.com/i1xaDl373sh&pwd=&jump=false



示例返回：

```json
{
    "name":"VHB系统永久激活工具V1.21.4.exe ",
    "author":"18** ",
    "time":"2021-01-30 ",
    "size":" 7.8 M ",
    "url":"https://store9.lanzoug.com/062519bb/2021/01/30/22570eb82fc2d622e3b77d8d933a1649.exe?st=-_shBndPATRVyv83-ZNZbw&e=1656157970&b=UlYORlUXVrRXsVG8V_bAEu1acALpQ4VboBbJd6VbUV7NRvAyMBeMDslG_aA7AG4Q6vCLgO1wO1CloAYlp5BjNfbFIuDjpVe1Y2V3pRYg_c_c&fi=37148717&pid=127-0-0-1&up=2&mp=0&co=1"
}
```

