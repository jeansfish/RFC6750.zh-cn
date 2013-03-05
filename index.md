互联网工程任务组（IETF，Internet Engineering Task Force）  
RFC：6750  
淘汰：[5849][RFC5849] 
类别：标准化过程  
ISSN：2070-1721  


M. Jones  
Microsoft  
D. Hardt  
独立  
2012年10月


# OAuth 2.0授权框架：不记名令牌用法
## 摘要
本规范描述了如何在HTTP请求中使用不记名令牌访问受OAuth 2.0保护的资源。持有不记名令牌（“bearer”）的任何一方可以用它获得相关联的资源的访问权限（无需证明持有加密密钥）。为防止误操作，不记名令牌在存储和传输时需要被保护防止泄露。
## 本备忘录状态
这是一个互联网标准化过程文档。

本文档是互联网工程任务组（IETF）的作品。它代表了IETF社区的共识。它已接受公开审查并被互联网工程指导小组（IESG）批准公布。互联网标准的更多信息可在[RFC5741的第2节][RFC5741#2]找到。

可于[http://www.rfc-editor.org/info/rfc6750][RFC6750Editor]获取有关本文档的当前状态、勘误表以及如何提供反馈的信息。
## 版权声明
IETF信托及标识为本文档的作者版权所有（c）2012。保留所有权利。

本文档受[BCP78][PCB78]和IETF信托有关IETF文档的法律条款 ([http://trustee.ietf.org/license-info][IETF License])的约束，自本文档发布之日起生效。请仔细查阅这些文件，因为它们描述了与本文档有关的权利和限制。从本文档中提取的代码组件必须按信托法律条款[4.e][TrustLegalProvisions#4.e]节所述包含简化BSD许可证文本；并且按简化BSD许可证中所述不附带质量保证。

## [目录](TableofContents.md)

[RFC5741#2]:http://tools.ietf.org/html/rfc5741#section-2 "RFC5741第二节"
[RFC6750Editor]: http://www.rfc-editor.org/info/rfc6750 "RFC6750Editor"
[PCB78]: http://tools.ietf.org/html/bcp78 "PCB78"
[IETF License]: http://trustee.ietf.org/license-info "IETF文档的法律条款"
[TrustLegalProvisions#4.e]: http://tools.ietf.org/html/rfc6749#section-4 "信托法律条款4.e"

