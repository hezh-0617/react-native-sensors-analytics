<img src="https://ow-file.sensorsdata.cn/www/home/header/sensors_header_icon.svg" width="200" >

[![License](https://img.shields.io/github/license/sensorsdata/react-native-sensors-analytics.svg)](https://github.com/sensorsdata/react-native-sensors-analytics/blob/master/LICENSE)
[![GitHub release](https://img.shields.io/github/tag/sensorsdata/react-native-sensors-analytics.svg?label=release)](https://github.com/sensorsdata/react-native-sensors-analytics/releases)
[![GitHub release date](https://img.shields.io/github/release-date/sensorsdata/react-native-sensors-analytics.svg)](https://github.com/sensorsdata/react-native-sensors-analytics/releases)

## 神策简介

[**神策数据**](https://www.sensorsdata.cn/)
（Sensors Data），隶属于神策网络科技（北京）有限公司，是一家专业的大数据分析服务公司，大数据分析行业开拓者，为客户提供深度用户行为分析平台、以及专业的咨询服务和行业解决方案，致力于帮助客户实现数据驱动。神策数据立足大数据及用户行为分析的技术与实践前沿，业务现已覆盖以互联网、金融、零售快消、高科技、制造等为代表的十多个主要行业、并可支持企业多个职能部门。公司总部在北京，并在上海、深圳、合肥、武汉等地拥有本地化的服务团队，覆盖东区及南区市场；公司拥有专业的服务团队，为客户提供一对一的客户服务。公司在大数据领域积累的核心关键技术，包括在海量数据采集、存储、清洗、分析挖掘、可视化、智能应用、安全与隐私保护等领域。 [**More**](https://www.sensorsdata.cn/about/aboutus.html)


## SDK 简介

SensorsAnalytics SDK 是国内第一家开源商用版用户行为采集 SDK，目前支持代码埋点、全埋点、App 点击图、可视化全埋点等。目前已累计有 1500 多家付费客户，2500+ 的 App 集成使用，作为 App 数据采集利器，致力于帮助客户挖掘更多的商业价值，为其精准运营和业务支撑提供了可靠的数据来源。其采集全面而灵活、性能良好，并一直保持稳定的迭代，经受住了时间和客户的考验。

## 基本要求
App 元素点击事件要求 React Native 0.23 ~ 0.66；  
App 页面浏览事件要求 React Navigation ^2.0 ~ ^5.0；  
App 可视化全埋点要求 React Native 0.46 ~ 0.66；  
App 点击事件自定义属性要求 React Native 0.46 ~ 0.66。

## 集成方式
### 安装 React Native 模块

#### 1. npm 安装 sensorsdata-analytics-react-native 模块

```sh
npm install sensorsdata-analytics-react-native
```

#### 2. `link` sensorsdata-analytics-react-native 模块（React Native 0.60 以下版本）

```sh
react-native link sensorsdata-analytics-react-native
```
#### 3. 配置 package.json
在 package.json 文件增加如下配置:
```sh
"scripts": {
      "postinstall": "node node_modules/sensorsdata-analytics-react-native/SensorsDataRNHook.js -run"
}
```

#### 4. 执行 npm 命令
   ```sh
   npm run-script postinstall
   ```

### 详细文档请参考：[集成文档（React Native）](https://manual.sensorsdata.cn/sa/docs/tech_sdk_client_rn_install)


## 新书推荐

| [《数据驱动：从方法到实践》](https://item.jd.com/12322322.html) | [《Android 全埋点解决方案》](https://item.jd.com/12574672.html) | [《iOS 全埋点解决方案》](https://item.jd.com/12867068.html)
| ------ | ------ | ------ |

## License
[License 协议](https://github.com/sensorsdata/react-native-sensors-analytics/blob/master/LICENSE)
