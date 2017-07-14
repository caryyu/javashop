# Java Shop
社区开源版本JAVA B2C/CMS 系统，适合二次开发；An Community Open Source B2C/CMS system based on Java, Suitable for twice development.

## 描述
此项目从[原始2.4.0版本](https://github.com/zrqgood/javashop.git)基础上进行构建，感谢[zrqgood](https://github.com/zrqgood)贡献!需要注意的是JDK版本范围1.6 >= 1.7，不支持JDK 1.8。

## Description

## 运行方式
### 下载WAR包部署
参考Release描述进行部署，适用于JAVA熟练者的方式。
### 使用Docker运行
```
docker run -d -p 8080:8080 caryyu/javashop
```

## 访问方式
通过浏览器打开链接地址 http://localhost:8080/javashop/ 即可进入安装向导。

## 修改历史
1、Javascript脚本执行功能使用ScriptEngine，去除了（js.jar/js-14.jar）依赖；  
2、JPEG图片生成采用ImageIO类进行处理，去除了"com.sun.*"包的直接使用；  
3、把原始Eclipse项目进行重构为MAVEN进行管理，方便二次开发。  

## Fixed History

## 贡献者/开发者
有兴趣的可以一起维护此份代码，有好的解决方案请提PR，我会及时进行校准并合并，谢谢！

## Contributors/Developers

## 版权声明
此份代码我完全从社区进行获取，并不知版权具体所属，如果进行商业目的使用并导致版权纠纷问题与作者本人无关。