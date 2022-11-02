# area-data-hbky



河北省市区行政区划数据，用于 `JeecgBoot` 架构前端 `Antdv` 框架组件 `JAreaLinkage` 进行地区下拉联动展示。基于 `area-data` 模块改造，精确到区县级。

## v1.0.1

- 修复Bug：修复切换城市后，组件报错：“省份 13 不存在”的 bug

## v1.0.0

- 删除子模块 `pcaa.js`，仅保留展示河北省、市、区/县数据的简化版本。

## doc

[详见 area-data 文档页](https://github.com/dwqs/area-data#readme)

## Installation

Install the package with npm:

```
npm install area-data-hbky --save
```

or yarn

```
yarn add area-data-hbky
```

or bower

```
bower install area-data-hbky
```

## 获取数据

```javascript
// 引入方式
import { pca } from 'area-data-hbky';
// 可以根据需要按需引入：
import PCA from 'area-data-hbky/pca';

pca['86'] 
// 仅河北省：{'13': '河北省'}
```



## LICENSE

MIT
