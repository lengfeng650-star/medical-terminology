---
pretty_name: 医学术语数据集
license: other
license_name: source-specific
license_link: LICENSE
language:
- zh
- en
tags:
- medical
- terminology
configs:
- config_name: default
  data_files:
  - split: train
    path: data/terms.jsonl
---

# 医学术语数据集

## 直接下载

- [下载 terms.jsonl](https://github.com/lengfeng650-star/medical-terminology/raw/refs/heads/main/data/terms.jsonl)

共 1,000 条术语，覆盖 10 类。

| 类别 | 条数 |
| --- | ---: |
| 疾病与手术编码 | 100 |
| 疾病与症状 | 100 |
| 解剖与表型 | 100 |
| 检验与生物医学 | 100 |
| 临床研究与公共卫生 | 100 |
| 药物与干预 | 100 |
| 医疗器械 | 100 |
| 医学影像 | 100 |
| 中文医学术语 | 100 |
| 综合医学术语 | 100 |

[来源与许可](LICENSE)

## 后续新增

中文语料实体、中医证候与治法、罕见病、肿瘤分类、临床遗传与变异、疫苗接种、药物基因组学、细胞系。
