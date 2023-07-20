# 世界各国信息数据
> 截止 2019 年，世界上共有 233 个国家和地区，其中国家有 195 个，地区有 38 个

此项目整理的各个国家的中文名、英文名、字母缩写、经纬度、国旗 emoji 字符 🇨🇳 、国旗 png 图片等，共计 `117` 个国家

数据来源自：[wyq2214368/country-info: 国家-中文名-英文名-经纬度坐标-国旗emoji字符🇨🇳数据集 (github.com)](https://github.com/wyq2214368/country-info/tree/master)


基本格式如下：
```json
[
    {
        "code": 86, // 地区码
        "tw": "中國", // 繁体中文名
        "en": "China", // 英文名
        "locale": "CN", // 缩写
        "zh": "中国", // 简体中文名
        "lat": 35.86166, // 纬度 latitude
        "lng": 104.195397, // 经度 longitude
        "emoji": "🇨🇳", // emoji 字符
        "flag"："base64" // 国旗 png
    }
]
```

同时项目已上传至 npm 库，也可通过 npm i country-options 或者 yarn add country-options 引入模块并在项目中使用

我也将长期维护优化，以便提升其可使用性。

欢迎提出建议或者需求，采纳后将新增至库中