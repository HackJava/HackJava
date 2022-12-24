# 《Java安全-只有Java安全才能拯救宇宙》

![HackJava](https://socialify.git.ci/HackJava/HackJava/image?description=0&descriptionEditable=%E3%80%8AJava%E5%AE%89%E5%85%A8-%E5%8F%AA%E6%9C%89Java%E5%AE%89%E5%85%A8%E6%89%8D%E8%83%BD%E6%8B%AF%E6%95%91%E5%AE%87%E5%AE%99%E3%80%8B&font=Rokkitt&forks=1&issues=1&name=1&owner=0&pattern=Floating%20Cogs&pulls=1&stargazers=1&theme=Light)

本项目是记录自己在学习研究Java安全过程中遇到的优秀内容，包括Java代码审计资源以及Java开发的应用程序组件协议等的安全内容。一个不会Java攻击的黑客不是一个好师傅，一个不懂Java安全的师傅不是一个好黑客！深入理解Java安全，手握众多重点Java应用高危0day！作者：[0e0w](https://github.com/0e0w)

本项目创建于2021年7月8日，最近的一次更新时间为2022年12月24日。本项目会持续更新，直到海枯石烂。

- [01-Java安全研究资源](https://github.com/HackJava/HackJava#01-java%E5%AE%89%E5%85%A8%E7%A0%94%E7%A9%B6%E8%B5%84%E6%BA%90)
- [02-Java安全研究工具](https://github.com/HackJava/HackJava#02-java%E5%AE%89%E5%85%A8%E7%A0%94%E7%A9%B6%E5%B7%A5%E5%85%B7)
- [03-Java安全漏洞环境](https://github.com/HackJava/HackJava#03-java%E5%AE%89%E5%85%A8%E6%BC%8F%E6%B4%9E%E7%8E%AF%E5%A2%83)
- [04-Java安全漏洞分类](https://github.com/HackJava/HackJava#04-Java%E5%AE%89%E5%85%A8%E6%BC%8F%E6%B4%9E%E5%88%86%E7%B1%BB)
- [05-Java安全代码审计](https://github.com/HackJava/HackJava#05-Java%E5%AE%89%E5%85%A8%E4%BB%A3%E7%A0%81%E5%AE%A1%E8%AE%A1)
- [06-Java安全漏洞修复](https://github.com/HackJava/HackJava#06-java%E5%AE%89%E5%85%A8%E6%BC%8F%E6%B4%9E%E4%BF%AE%E5%A4%8D)
- [07-Java安全高危应用](https://github.com/HackJava/HackJava#07-java%E5%AE%89%E5%85%A8%E9%AB%98%E5%8D%B1%E5%BA%94%E7%94%A8)
- [08-Java安全参考资源](https://github.com/HackJava/HackJava#08-java%E5%AE%89%E5%85%A8%E5%8F%82%E8%80%83%E8%B5%84%E6%BA%90)

## 01-Java安全研究资源

一、书籍资料
- [ ] [《Java代码审计-入门篇》](https://item.jd.com/10033832360716.html)@陈俊杰等
- [ ] [《Java代码审计实战》](https://item.jd.com/13466996.html)@高昌盛等
- [ ] [《Java安全编码标准》](https://book.douban.com/subject/24846041)@计文柯译
- [ ] [《Java安全性编程指南》]()@庞南
- [ ] [《Java安全》]()@奥克斯
- [ ] [《Java编码指南》](https://www.amazon.co.uk/%E7%BC%96%E5%86%99%E5%AE%89%E5%85%A8%E5%8F%AF%E9%9D%A0%E7%A8%8B%E5%BA%8F%E7%9A%8475%E6%9D%A1%E5%BB%BA%E8%AE%AE%EF%BC%88%E8%8B%B1%E6%96%87%E7%89%88%EF%BC%89-%E5%BE%B7%E9%B2%81%C2%B7%E8%8E%AB%E6%AC%A3%E8%BE%BE%EF%BC%88Dhruv-C-%E8%A5%BF%E7%A7%91%E5%BE%B7%EF%BC%88Robert-F-%E8%90%A8%E7%91%9F%E5%85%B0%EF%BC%88Dean-%E5%BC%97%E9%9B%B7%E5%BE%B7%C2%B7%E6%9C%97%EF%BC%88Fred/dp/B017WGUFKO)@刘先宁
- [ ] [《Java-Web-Security》](https://play.google.com/store/books/details/Java_Web_Security_Sichere_Webanwendungen_mit_Java_?id=ZxZ4DwAAQBAJ&hl=en_US&gl=US)@Dominik Schadow

二、基础教程
- [ ] [《Java Web安全-代码审计》](https://github.com/javaweb-sec/javaweb-sec)@凌天实验室
- [ ] [《Java安全漫谈笔记相关内容》](https://github.com/phith0n/JavaThings)@phith0n
- [ ] [《Java代码审计学习笔记》](https://github.com/proudwind/javasec_study)@proudwind
- [ ] [《Java漏洞学习笔记》](https://github.com/SummerSec/JavaLearnVulnerability)@SummerSec
- [ ] [《代码审计入门小项目》](https://github.com/cn-panda/JavaCodeAudit)@cn-panda
- [ ] [《自学Java安全总结》](https://github.com/Maskhe/javasec)@Maskhe
- [ ] [《攻击Java Web应用》](https://github.com/March110/javaweb-sec)@安百科技
- [ ] [《Java RCE 回显测试代码》](https://github.com/feihong-cs/Java-Rce-Echo)@feihong
- [ ] [《Java反序列化技术分享》](https://github.com/Y4er/WebLogic-Shiro-shell)@Y4er
- [ ] [《Java代码审计总结》](https://github.com/huyuanzhi2/CodeReview)@huyuanzhi2
- [ ] [《代码审计知识点整理-Java》](https://github.com/7hang/--Java)@7hang
- [ ] [《Java代码审计案例》](https://github.com/5huai/POC-Test)@5huai
- [ ] [《Java安全和Java框架漏洞》](https://github.com/Firebasky/Java)@Firebasky
- [ ] [《Java安全相关的漏洞和技术demo》](https://github.com/threedr3am/learnjavabug)@threedr3am
- [ ] [《跟我一起JAVA代码审计》](https://www.freebuf.com/column/1289)@0neOfU4
- [ ] [《告别脚本小子系列丨JAVA安全》](https://mp.weixin.qq.com/s/oEI1GLJKSoSLxMcAhFFWKQ)@烽火台实验室

三、视频教程
- [ ] [《MS08067安全实验室》](https://space.bilibili.com/396298765?spm_id_from=333.788.b_765f7570696e666f.2)@MS08067
- [ ] [《Java代码审计系列课程》](https://edu.51cto.com/course/27875.html)@Hack_Man
- [ ] [《Java代码审计课程》](https://www.learnfuture.com/study/ist126v)@嘉为教育
- [ ] [《宽字节安全 JAVA安全线上进阶课程》](https://www.cnblogs.com/unicodeSec/p/15062087.html)@宽字节
- [ ] [《Securing Java Web Applications》](https://www.pluralsight.com/courses/java-web-application-security-vulnerabilities)@Josh Cummings

四、培训演讲

五、专利文献
- [ ] [一种基于java的web动态安全漏洞检测方法](https://patents.google.com/patent/CN103699480B/zh)@安恒

六、审计报告

七、其他资源
- [ ] https://github.com/topics/static-analysis?l=java
- [ ] [《攻击Java Web应用》](https://zhishihezi.net/b/5d644b6f81cbc9e40460fe7eea3c7925)@javasec
- [ ] [《J2EE 渗透测试与安全开发》](https://zhishihezi.net/b/98ae566719b21536dff0c4febaa697d2)@路人甲
- [ ] [《静态程序分析入门教程》](https://github.com/RangerNJU/Static-Program-Analysis-Book)
- [ ] [《Java代码审计文章集合》](https://www.cnblogs.com/r00tuser/p/10577571.html)@r00tuser
- [ ] https://github.com/su18/JDBC-Attack
- [ ] https://xz.aliyun.com/t/7945
- [ ] http://tttang.com/archive/1322
- [ ] https://teamssix.com/211115-165745.html
- [ ] https://teamssix.com/211115-123451.html
- [ ] https://github.com/dean2021/java_security_book
- [ ] https://github.com/yq1ng/Java
- [ ] https://github.com/wa1ki0g/javasec
- [ ] https://github.com/pen4uin/JavaSec
- [ ] https://github.com/javaparser/javaparser
- [ ] https://github.com/safe6Sec/JavaDeserialization
- [ ] https://github.com/ninthDevilHAUNSTER/JavaSecLearning
- [ ] https://github.com/Ghost2097221/javaweb_security_study_notes
- [ ] https://github.com/Cryin/JavaID
- [ ] https://paper.seebug.org/312
- [ ] https://tttang.com/archive/1337
- [ ] https://paper.seebug.org/1766
- [ ] https://github.com/p1n93r/javasec
- [ ] https://github.com/haby0/sec-note
- [ ] https://github.com/woodpecker-appstore/rmi-deserialization-vuldb
- [ ] https://github.com/4ra1n/JavaSecInterview
- [ ] https://github.com/4ra1n/FindShell
- [ ] https://github.com/pen4uin/java-security
- [ ] https://github.com/flowerwind/JspFinder
- [ ] https://github.com/TonyD0g/JavaHacker
- [ ] https://github.com/qtc-de/remote-method-guesser
- [ ] https://github.com/fynch3r/Gadgets
- [ ] https://tttang.com/archive/1405
- [ ] https://github.com/eugenp/tutorials
- [ ] https://github.com/Adrninistrator/java-all-call-graph
- [ ] https://github.com/KeenSecurityLab/BinAbsInspector
- [ ] https://github.com/R17a-17/JavaVulnSummary
- [ ] [红队java代码审计生命周期](https://xz.aliyun.com/t/11966)

## 02-Java安全研究工具

工欲善其事必先利其器，此处收集整理Java代码审计的一些优秀工具！期待自己的代码审计工具能够早日发布！

一、SAST
- [ ] https://github.com/ASTTeam/SAST
- [ ] https://github.com/wooyunwang/Fortify
- [ ] https://github.com/FeeiCN/Cobra
- [ ] https://github.com/LoRexxar/Kunlun-M
- [ ] https://checkstyle.sourceforge.io
- [ ] https://github.com/j5s/XVulnFinder
- [ ] https://github.com/SummerSec/SPATool
- [ ] https://github.com/noidsirius/SootTutorial
- [ ] [Tencent Xcheck](https://cloud.tencent.com/product/asd)

二、DAST
- [ ] https://github.com/ASTTeam/DAST

三、IAST
- [ ] https://github.com/ASTTeam/IAST
- [ ] https://github.com/HXSecurity/DongTai

四、CodeQL
- [ ] https://github.com/ASTTeam/CodeQL
- [ ] https://codeql.github.com

五、RASP
- [ ] https://github.com/0e0w/RASP

六、JNDI
- [ ] https://github.com/HackJava/JNDI
- [ ] https://github.com/bradfitz/jndi
- [ ] https://github.com/EmYiQing/LDAPKit
- [ ] https://github.com/su18/JNDI
- [ ] https://github.com/welk1n/JNDI-Injection-Exploit
- [ ] https://github.com/feihong-cs/JNDIExploit
- [ ] https://github.com/0x727/JNDIExploit
- [ ] https://github.com/veracode-research/rogue-jndi
- [ ] https://github.com/quentinhardy/jndiat
- [ ] https://github.com/p1n93r/AttackJNDI
- [ ] https://github.com/Jeromeyoung/JNDIExploit-1
- [ ] https://github.com/exp1orer/JNDI-Inject-Exploit
- [ ] https://github.com/zu1k/ldap-log
- [ ] https://github.com/orleven/Celestion

七、Deserialization
- [ ] https://github.com/wh1t3p1g/ysomap
- [ ] https://github.com/frohoff/ysoserial
- [ ] https://github.com/KpLi0rn/ysoserial
- [ ] https://github.com/Y4er/ysoserial
- [ ] https://github.com/0range228/Gadgets
- [ ] https://github.com/ikkisoft/SerialKiller
- [ ] https://github.com/5wimming/gadgetinspector
- [ ] https://github.com/threedr3am/gadgetinspector
- [ ] https://github.com/JackOfMostTrades/gadgetinspector
- [ ] https://github.com/Afant1/JavaSearchTools
- [ ] https://github.com/j1anFen/ysoserial_echo
- [ ] https://github.com/EmYiQing/ShortPayload

八、Monitor
- [ ] https://github.com/TheKingOfDuck/FileMonitor
- [ ] https://github.com/TheKingOfDuck/MySQLMonitor
- [ ] https://github.com/Lotus6/FileMonitor

九、IDEA
- [ ] https://github.com/XianYanTechnology/RocB
- [ ] https://github.com/momosecurity/momo-code-sec-inspector-java
- [ ] https://github.com/XmirrorSecurity/OpenSCA-intellij-plugin

十、Others
- [ ] https://github.com/MobSF/mobsfscan
- [ ] https://github.com/threedr3am/log-agent
- [ ] https://github.com/wh1t3p1g/tabby
- [ ] https://github.com/j5s/XVulnFinder
- [ ] https://github.com/EmYiQing/CodeInspector
- [ ] https://github.com/mtxiaowangzi/CAFJE
- [ ] https://github.com/returntocorp/semgrep
- [ ] https://github.com/cqkenuo/LingZhi
- [ ] https://github.com/blinkfox/stalker
- [ ] https://github.com/spotbugs/spotbugs
- [ ] https://github.com/SonarSource/sonarqube
- [ ] https://www.jarchitect.com
- [ ] https://github.com/eclipse/eclemma
- [ ] https://github.com/phith0n/zkar
- [ ] https://github.com/Firebasky/GoRmi
- [ ] https://github.com/LostZX/Kakaka
- [ ] https://github.com/jenkinsci/snyk-security-scanner-plugin
- [ ] https://github.com/secdec/attack-surface-detector-burp
- [ ] https://github.com/0Kee-Team/JavaProbe
- [ ] https://github.com/EmYiQing/SpringInspector
- [ ] https://github.com/whwlsfb/JDumpSpider
- [ ] https://github.com/Ppsoft1991/CodeReviewTools
- [ ] https://github.com/0nise/shell-plus
- [ ] https://github.com/4ra1n/SpringInspector
- [ ] https://github.com/GraxCode/cafecompare
- [ ] https://github.com/siberas/sjet
- [ ] https://github.com/4ra1n/accelerator
- [ ] https://github.com/hluwa/Wallbreaker

## 03-Java安全漏洞环境

此处收集整理Java安全漏洞研究的一些环境，包括Web环境，应用框架漏洞环境等。

- [ ] [WebBug-JavaEE编写的Web漏洞靶场](https://github.com/Mysticbinary/WebBug)@mysticbinary
- [ ] [WebGoat-一个故意不安全的应用程序](https://github.com/WebGoat/WebGoat)@WebGoat
- [ ] [JavaSecurity-Java Web漏洞演示程序](https://github.com/dschadow/JavaSecurity)@dschadow
- [ ] [Java-Web-Security-书籍完整代码示例](https://github.com/dschadow/Java-Web-Security)@dschadow
- [ ] [maobugs-Java 漏洞平台包含各种CVE演示](https://github.com/langligelang/maobugs)@langligelang
- [ ] [SecExample-Java漏洞靶场](https://github.com/tangxiaofeng7/SecExample)@tangxiaofeng7
- [ ] [java sec code-学习Java漏洞代码的项目](https://github.com/JoyChou93/java-sec-code)@JoyChou93
- [ ] [dvja-该死的易受攻击的 Java EE应用程序](https://github.com/appsecco/dvja)@appsecco
- [ ] [JavaVulnerableLab-易受攻击的Java Web应用程序](https://github.com/CSPF-Founder/JavaVulnerableLab)@CSPF-Founder
- [ ] [Java_deserialize_vuln_lab-Java反序列化学习的实验代码](https://github.com/bit4woo/Java_deserialize_vuln_lab)@bit4woo
- [ ] [Java-EE-VulnWeb用于演示的Java Web漏洞项目](https://github.com/mtxiaowangzi/Java-EE-VulnWeb)@mtxiaowangzi
- [ ] [Hello Java Sec-Java安全编码和代码审计](https://github.com/j3ers3/Hello-Java-Sec)@3ers3
- [ ] [javaweb codereview-演示java代码审计程序](https://github.com/iiiusky/javaweb-codereview)@iiiusky
- [ ] [sqlilab Jsp-jsp版sqlilab 1-21关](https://github.com/yhy0/sqlilab-Jsp)@yhy0
- [ ] [ShiroAndFastJson-shiro加fastjson环境](https://github.com/safe6Sec/ShiroAndFastJson)@safe6Sec
- [ ] [RMI 反序列化环境 一步步](https://github.com/lalajun/RMIDeserialize)@lalajun
- [ ] [mytestvul-一个用来做漏洞复现/验证的小框架](https://github.com/novysodope/mytestvul)@novysodope
- [ ] [JavaVulnerableLab circle-练习Java反序列化的最简单环境](https://github.com/pmiaowu/DeserializationTest)@pmiaowu
- [ ] [易受攻击的Java Web应用程序](https://github.com/Zhangyao-zzyy/JavaVulnerableLab-circle)@Zhangyao-zzyy
- [ ] https://github.com/l4yn3/micro_service_seclab
- [ ] https://github.com/GoSecure/goinsecure-deserialization
- [ ] https://gitee.com/cor0ps/java-range
- [ ] https://github.com/c0ny1/xxe-lab
- [ ] https://github.com/shanika04/Kura_XXE
- [ ] https://github.com/t0thkr1s/allsafe
- [ ] https://github.com/oversecured/ovaa
- [ ] https://github.com/jaiswalakshansh/Vuldroid
- [ ] https://github.com/baidu-security/openrasp-testcases
- [ ] https://github.com/cschneider4711/Marathon
- [ ] https://github.com/pmiaowu/RMITest
- [ ] https://github.com/OWASP-Benchmark/BenchmarkJava
- [ ] https://github.com/EmYiQing/CIDemo
- [ ] https://github.com/Y4tacker/JavaSec
- [ ] https://github.com/javaweb-sec/javaweb-vuls
- [ ] https://github.com/LandGrey/SpringBootVulExploit

## 04-Java安全漏洞分类

- Java反序列化漏洞
- 任意命令执行漏洞
- 任意文件上传漏洞
- 任意文件写入漏洞
- 任意文件包含漏洞
- 任意文件删除漏洞
- SQL注入漏洞
- 业务逻辑漏洞
- 变量覆盖漏洞
- 程序安装问题
- XSS漏洞
- XXE漏洞
- SSRF漏洞
- CSRF漏洞

## 05-Java安全代码审计

一、Java安全Web漏洞
- [ ] https://github.com/ax1sX/SecurityList

二、Java代码审计实战

## 06-Java安全漏洞修复

一、Java安全编码规范
- [x] [《Java安全编码标准》](https://developer.aliyun.com/article/175341)@计文柯
- [OWASP 安全编码规范](https://owasp.org/www-pdf-archive/OWASP_SCP_Quick_Reference_Guide_%28Chinese%29.pdf)
- [腾讯-Java安全编码规范](https://github.com/Tencent/secguide/blob/main/Java%E5%AE%89%E5%85%A8%E6%8C%87%E5%8D%97.md)
- [陌陌-Java安全编码规范](https://github.com/momosecurity/rhizobia_J)
- 华为-Java安全编码规范
- 绿盟-Java安全编码规范
- 奇安信-Java安全编码规范
- 软通动力-Java-Web安全开发规范
- [securitypaper-Java安全编码规范](https://www.securitypaper.org/2.sdl%E8%A7%84%E8%8C%83%E6%96%87%E6%A1%A3/3-java%E5%AE%89%E5%85%A8%E7%BC%96%E7%A0%81%E8%A7%84%E8%8C%83)

二、Java安全漏洞修复

## 07-Java高危应用框架

此处整理收集Java开发的普遍使用的程序：包括中间件、核心框架、底层库、重要应用系统等。待更新。

- [Log4j2](https://github.com/HackJava/Log4j2)
- [Shiro](https://github.com/HackJava/Shiro)
- [Weblogic](https://github.com/HackJava/Weblogic)
- MyBatis
- Spring

## 08-Java安全参考资源

本人在学习Java安全的过程中遇到了很多优秀的Java安全研究员，感谢这些研究者！排名不分先后。

- https://github.com/4ra1n
- https://github.com/phith0n
- https://github.com/su18
- https://github.com/welk1n
- https://github.com/threedr3am
- https://github.com/Y4er
- https://github.com/wh1t3p1g
- https://xz.aliyun.com/u/44415

## Stargazers

[![Stargazers @HackJava/HackJava](https://reporoster.com/stars/HackJava/HackJava)](https://github.com/HackJava/HackJava/stargazers)

## Forkers

[![Forkers @HackJava/HackJava](https://reporoster.com/forks/HackJava/HackJava)](https://github.com/HackJava/HackJava/network/members)

![](01-Java安全研究资源/TEMP/wx.png)

[![Stargazers over time](https://starchart.cc//HackJava/HackJava.svg)](https://starchart.cc/HackJava/HackJava)

