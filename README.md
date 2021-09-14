# 网关接口
``咨询客服``
# 注册接口
``已关闭注册，请联系客服开通``
# 登录接口
``/user/login``
# 退出接口
``/user/logout``
# 分类目录
``/vod/type/1`` ##(1)为分类id##

``
[{"type":"1","typename":"\u5077\u62cd\u81ea\u62cd"},{"type":"2","typename":"\u5236\u670d\u8bf1\u60d1"},
{"type":"3","typename":"\u6e05\u7eaf\u5c11\u5973"},{"type":"4","typename":"\u8fa3\u59b9\u5927\u5976"},
{"type":"5","typename":"\u5973\u540c\u4e13\u5c5e"},{"type":"6","typename":"\u7d20\u4eba\u51fa\u6f14"},
{"type":"7","typename":"\u89d2\u8272\u626e\u6f14"},{"type":"8","typename":"\u6210\u4eba\u52a8\u6f2b"},
{"type":"9","typename":"\u4eba\u59bb\u719f\u5973"},{"type":"10","typename":"\u53d8\u6001\u53e6\u7c7b"},
{"type":"10","typename":"\u7ecf\u5178\u4f26\u7406"}]
``
# 分类内容
``{"msg":"ok"}`` ##ok为正常访问，非json格式，如果报错msg内容会以中文方式返回提示##

``<a href="/vod/detail/id/10825/">`` ##正常获取内容页面，以火车头为例会自动采取a标签herf内容##
# 分类页码
``/vod/type/1/2`` ##(2)为页码数##
## 分类页码总数

审查元素或查看源代码方式最底部``{"page":57}`` ##(57)为总页数##

# 获取内容
``vod/detail/id/8299/`` ##(8299)为内容id##
# 内容介绍
``{"msg":"ok"}`` ##ok为正常访问，非json格式，如果报错msg内容会以中文方式返回提示##

##内容详细以审查元素或查看源代码方式查看，以火车头为例只需正则或者前后匹配即可##


``
"title":"名称"
``

``
"coverpic":"图片链接"
``

``
"playurl":"视频链接"
``

``
"areaname":"地区"
``

``
"duration":"视频时长"
``

``
"yearname":"年代"
``

``
"updatetime":"更新时间"
``
