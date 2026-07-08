# 前言

随着新冠病毒的蔓延，各国政府和机构都在努力应对疫情。为响应国家号召，我们开发了一套适用于校园的疫情防控系统，旨在协助校园进行疫情防控管理。本项目使用Java语言，基于Spring Boot框架开发，前端采用JS、Vue、css3等技术。现将项目分享至Gitee，希望能为广大师生提供便利。

## 内容介绍

本项目主要包括以下功能模块：个人信息管理、健康信息上报、疫情动态展示、防疫知识普及等。系统通过实时收集、分析用户健康数据，为校园疫情防控提供数据支持。同时，通过疫情动态展示和防疫知识普及，提高师生的防疫意识。

## 技术介绍

- 语言：Java
- 使用框架：Spring Boot
- 前端技术：JS、Vue、css3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven: apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下是本项目中的一段核心代码，用于实现用户健康信息上报功能：

```java
@RestController
@RequestMapping("/api/health")
public class HealthController {

    @Autowired
    private HealthService healthService;

    @PostMapping("/report")
    public ResponseEntity<String> reportHealth(@RequestBody Health health) {
        boolean result = healthService.reportHealth(health);
        if (result) {
            return new ResponseEntity<>("上报成功", HttpStatus.OK);
        } else {
            return new ResponseEntity<>("上报失败", HttpStatus.INTERNAL_SERVER_ERROR);
        }
    }
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img11.360buyimg.com/ddimg/jfs/t1/294247/9/10427/121454/689e9a46F60c426da/ff98d9a5d5309dc6.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/307703/17/26527/20889/689e9a24Fef8885f4/fbd6f1f836e378ca.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/313558/16/26481/50756/689e9a24F9d231e9c/08e038f15f483b0a.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/310621/5/26463/35009/689e9a25F81aa40d5/7b6e788ce58e9773.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/323560/7/4979/38873/689e9a26Ff635a4e6/f7d12ac0b3058dca.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/316019/2/26484/35435/689e9a27F322d0471/ff873f323ea9a57e.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/321197/15/25241/24649/689e9a27F2a107072/bbb10b5b21dbb223.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/323958/36/4776/19587/689e9a28F9e505981/d785156e736cc8fd.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/318045/16/24181/63024/689e9a28F71550fd1/f3e99c451317b850.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/291739/14/18350/154716/689e9a29F8a8e1c62/3dc13ed6f64bcbea.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
