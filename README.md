常用网盘API
=========

### 说明:

1.支持网盘: 天翼云盘,阿里云盘,蓝奏云盘,123云盘,夸克网盘,和彩云(中国移动云盘)   
2.为保证兼容性,降低复杂度,均以传递JSON数据操作

### 简单示例:

类: TianYiYunPan - 天翼云盘  
类: ALiYunPan - 阿里云盘  
类: LanZouYunPan - 蓝奏云盘  
类: YunPan123 - 123云盘  
类: KuaKeYunPan - 夸克网盘  
类: HeCaiYunPan - 和彩云(中国移动云盘)

```
TianYiYunPan.login(username,password).getInfoAsHome(); // 获取主页文件列表信息

YunPan123.login(auth).getStraight(fileInfo); // 根据JSON配置获取直链
```

## 鸣谢

感谢[**JetBrains**](https://www.jetbrains.com/zh-cn/community/opensource/#support)提供的开源开发许可证，JetBrains 通过为核心项目贡献者免费提供一套一流的开发者工具来支持非商业开源项目。

[<img src="https://www.jetbrains.com/icon.svg" width="200"/>](https://www.jetbrains.com/zh-cn/community/opensource/#support)
