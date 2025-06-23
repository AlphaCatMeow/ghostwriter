# ghostwriter (影子作家)

## 项目描述

本项目 "ghostwriter" (影子作家) 包含一系列 JSON 文件。每个 JSON 文件代表从各种来源提取的语言特征。这些 JSON 文件的命名约定是 `数据来源_被提取者名字简写.json` (例如, `Weibo_Hu.json`)。

本项目会持续更新，更新时间不固定，会根据大家的需求和提供的分析数据进行特征提取，并评估后公开。

## 许可证

本项目采用 [知识共享署名-非商业性使用-禁止演绎 4.0 国际公共许可证 (CC BY-NC-ND 4.0)](LICENSE) 进行许可。

这意味着：
-   **署名** — 您必须给出适当的署名，提供指向本许可证的链接，同时标明是否（对原始作品）作了修改。您可以用任何合理的方式来署名，但是不得以任何方式暗示许可人为您或您的使用背书。
-   **非商业性使用** — 您不得将本作品用于商业目的。
-   **禁止演绎** — 如果您再混合、转换、或者基于本作品创作，您不可以分发修改作品。

请查阅 [LICENSE](LICENSE) 文件了解完整的条款和条件。

## 使用方法

`data/` 目录中的 JSON 文件包含结构化的语言特征数据。您可以将这些文件用于研究、分析或任何符合许可条款的非商业目的。

每个文件根据数据来源和数据提取对象的姓名首字母进行命名。例如，`Weibo_Hu.json` 表示从微博提取的、与姓名首字母为 "Hu" 的个人相关的数据。

结合长上下文大模型使用，有较好的输出结果。

## 贡献

如果您有建议或发现问题，可以提出，但不保证会得到回应或采取行动。

如果您有需要的语言特征提取，可以发送特征明显的数据，并等待处理。


## 联系方式

Email: [null@linux.do](mailto:null@linux.do)

## 项目结构

```
ghostwriter/
├── .gitignore
├── LICENSE
├── README.md
└── data/
    └── Weibo_Hu.json
    └── ... (其他数据文件)
```

## 更新情况

|更新日期|文件名|特征介绍|特征框架版本|
|----|----|----|----|
|20250512|Weibo_Hu.json|基于微博用户胡锡进100条原创提取的语言特征|1.0|
|20250513|Tiandao_DingYuanying.json|基于《天道》（《遥远的救世主》）提取的丁元英思维和语言特征|1.0|
|20250513|Tiandao_RuiXiaodan.json|基于《天道》（《遥远的救世主》）提取的芮小丹思维和语言特征|1.0|
|20250513|Honglou_LinDaiyu.json|基于《红楼梦》提取的林黛玉思维、性情及语言特征|1.0|
|20250513|Renmindemingyi_QiTongwei.json|基于《人民的名义》提取的祁同伟思维、性情及语言特征|1.0|
|20250514|Xianjianqixiazhuan_Linyueru.json|基于《仙剑奇侠传》提取的林月如思维、性情及语言特征|1.0|
|20250515|Ribendongman_Lingboli.json|根据朋友愿望，基于互联网数据提取的绫波丽思维及语言特征|1.0|
|20250515|Tianmuhongchen_YeZinong.json|基于《天幕红尘》提取的叶子农思维和语言特征|1.1|
|20250515|Public_LuXun.json|基于公共数据中鲁迅的作品、信件等内容，提取的鲁迅先生的语言特征，与大众想象的鲁迅先生有偏差，可能会更接近真实的鲁迅先生|1.0|
|20250519|Speaker_Lei.json|基于雷布斯最近4次演讲内容，提取雷布斯演讲语言特征|0.8|
|20250519|Liangjian_LiYunlong.json|基于小说《亮剑》提取的李云龙思维和语言特征，测试新版特征框架|2.1|
|20250522|Public_ZhangYi.json|基于史料和《大秦帝国》小说内容，提取的秦相张仪的语言特征|1.0|
|20250528|Aiqinggongyu_LvZiqiao.json|基于《爱情公寓》提取的吕子乔思维和语言特征，偏人生导师吕小布人设|2.1|
---

# ghostwriter (影子作家) - English Version

## Project Description

This project, "ghostwriter" (影子作家), contains a collection of JSON files. Each JSON file represents extracted linguistic features from various sources. The naming convention for these JSON files is `source_authorinitials.json` (e.g., `Weibo_Hu.json`).

This project will be continuously updated. The update schedule is not fixed and will be based on community needs and provided analytical data for feature extraction, which will be evaluated and then made public.

## License

This project is licensed under the [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International Public License (CC BY-NC-ND 4.0)](LICENSE).

This means:
-   **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
-   **NonCommercial** — You may not use the material for commercial purposes.
-   **NoDerivatives** — If you remix, transform, or build upon the material, you may not distribute the modified material.

Please review the [LICENSE](LICENSE) file for the full terms and conditions.

## Usage

The JSON files in the `data/` directory contain structured linguistic feature data. You can use these files for research, analysis, or any non-commercial purpose that complies with the license terms.

Each file is named according to the source of the data and the initials of the person/entity from whom the data was extracted. For example, `Weibo_Hu.json` indicates data extracted from Weibo, related to an individual with the initials "Hu".

When used in conjunction with large language models with long context capabilities, it yields better output results.

## Contributing

Currently, direct contributions to this project (e.g., pull requests for modifying existing data or adding new data) are not being accepted. The project is provided as-is.

If you have suggestions or find issues, you may raise them, but there is no guarantee of a response or action.

If you require specific linguistic feature extraction, you can send data with distinct features and await processing.

## Contact Information

Email: [null@linux.do](mailto:null@linux.do)

## Project Structure

```
ghostwriter/
├── .gitignore
├── LICENSE
├── README.md
└── data/
    └── Weibo_Hu.json
    └── ... (other data files)
```

## Star


<p style="text-align: center;">
    <a href="https://api.star-history.com/svg?repos=superzhang21/ghostwriter">
        <img alt="start" width=50% src="https://api.star-history.com/svg?repos=superzhang21/ghostwriter"/>
    </a>
</p>
