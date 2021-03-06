# CCTC - Classical Chinese Translation Corpus

[中文文档](./README.md)

A classical Chinese translation corpus dataset.(Under construction)

## Describtion

Translated data of classical Chinese:

- Historical Records, by Sima Qian (29 for now)
- LunYu (20 articles)
- ZhongYong (33 chapters)

Data format

```json
[
    {
        "title": "",
        "contents": [
            {
                "source": "",
                "target": ""
            },
            {
                "source": "",
                "target": ""
            },
        ]
    }
]
```

Statement

|    |Samples|Max Length|Min Length|Average Length|Median Length|Standard Deviation|
|----|:---:|:------:|:-----:|:-------:|:-------:|:-------:|
|source|7841  |180    |1      |17.67    |15.0     |13.54    |
|target|7841  |280    |2      |29.20    |24.0     |23.28    |

## Contribution

- Welcome interested friends to contribute to this project.

- If you have part of the compiled classical Chinese translation corpus, and do not mind opening it, you can directly submit PR to contribute.

- If you think the project is very valuable and willing to support me to improve the project continuously, you can also sponsor 「[Alipay](./static/alipay.jpg)」 or 「[WeChat appreciation code](./static/wechat.jpg)」(with you email).

## Reference

If you want to use the dataset in your research,please indicate the source of the dataset,https://github.com/scagin/cctc

If you want to use this data set for training business algorithm models, or for other purposes, it is allowed.The open source dataset adopts [MIT license](.LICENSE), and all statements are in the license.

## Contact

- Mail：406493851@qq.com

- QQ：406493851
