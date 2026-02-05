# 前言

欢迎来到本项目的Gitee仓库！这是一个由数计学院学生设计与开发的综合素质评价系统。项目基于Java语言，使用Spring Boot框架，前端采用JS、Vue和CSS3技术，数据库为MySQL 5.7/8.0。下面将详细介绍项目内容、技术栈及核心代码等。

# 内容介绍

本项目旨在为学院提供一个便捷、高效的学生综合素质评价系统。通过该系统，教师可以轻松录入、查询和统计学生的各项评价指标，从而更好地关注学生成长。系统主要包括以下功能模块：学生信息管理、评价指标管理、成绩录入与查询、统计分析等。

# 技术介绍

- 语言：Java
- 使用框架：Spring Boot
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven: apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

# 核心代码

以下是项目中的一个核心代码片段，展示了如何实现学生信息的查询功能：

```java
@RestController
@RequestMapping("/student")
public class StudentController {

    @Autowired
    private StudentService studentService;

    @GetMapping("/getStudentById")
    public ResponseEntity<Student> getStudentById(@RequestParam("id") int id) {
        Student student = studentService.getStudentById(id);
        if (student != null) {
            return new ResponseEntity<>(student, HttpStatus.OK);
        } else {
            return new ResponseEntity<>(HttpStatus.NOT_FOUND);
        }
    }
}
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img10.360buyimg.com/ddimg/jfs/t1/315462/20/26284/130759/689e03d7F409216fb/c1bbb389dfb6ea35.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/288889/39/11021/48727/689e03beF8a7fa557/947890bed11dc0e1.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/301105/35/23694/74616/689e03beF8c2e6073/e6d7fff323c682ab.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/325808/20/4541/35643/689e03bfFc4ef541f/1ab0e16dad34ba6f.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/321086/19/24988/31986/689e03bfFe203c54c/133de65a43793e04.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/312068/13/26315/44085/689e03c0F580e9d6a/6c43023d313f5277.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/289059/7/16858/39870/689e03c0F5a1e4381/1de5c5a982c59463.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/319948/19/25493/34003/689e03c1Fc238870b/f6c7f9762fb220f1.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/313796/10/26349/33002/689e03c1F46471972/879e2d69a2e046da.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/320482/23/24601/47349/689e03c2F974e2892/c482e4212dbb575b.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
