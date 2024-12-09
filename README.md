# WMS

# 仓库管理系统
### 一、实验目标
**1.	掌握Java编程技能**
通过开发仓库管理系统（WMS），学生能够全面学习并掌握Java编程语言的核心与高级应用。开发过程将涵盖面向对象编程的深入理解和实际应用，包括类的封装、继承、多态等特性。学生还将学习Java集合框架的操作，如列表、映射和集合的高效使用。同时，通过实现系统中对文件的读写功能，学生可以掌握文件流和序列化的操作技巧。此外，在处理用户输入错误和系统故障的过程中，学生将掌握异常的捕获与处理，培养代码健壮性和稳定性，增强对实际开发场景的适应能力。

**2.	掌握数据库管理技能**
通过实现WMS系统中的商品管理、订单记录、库存跟踪等功能，学生能够学习并熟练掌握MySQL数据库的设计与操作技能。课程中将涵盖数据库的基本概念和应用技巧，如表结构设计、字段类型选择、主键与外键的设置，以及索引优化。学生将通过动手实践，学习如何执行数据插入、查询、更新和删除操作，并在此过程中了解SQL语句的编写规范。同时，系统中复杂查询和多表联结操作的实现将帮助学生深入理解数据库优化和事务处理的重要性。
**3.	软件工程实践**
WMS项目开发为学生提供了一个完整的软件工程实践机会，从需求分析到系统设计、编码实现、测试优化，再到最终交付。通过编写需求文档和绘制系统架构图，学生能够学习如何分解业务需求并转化为技术实现方案。在编码阶段，学生将接触主流的开发工具和框架，积累实际的项目开发经验。在测试阶段，学生将学习单元测试和集成测试的基本方法，确保代码的正确性和系统的稳定性。整个实践过程将帮助学生熟悉软件开发的标准流程，提高项目管理和开发效率。
**4.	解决实际问题**
WMS系统的开发目标是解决企业在仓库管理中的实际问题，如商品的高效进出库、库存信息的实时更新、员工操作的权限管理等。通过项目开发，学生将深入了解这些实际业务场景，并将所学知识应用于具体问题的解决中。例如，设计库存报警功能以避免商品短缺或过剩，通过权限管理模块确保敏感数据的安全性等。这个过程中，学生不仅能够锻炼技术能力，还能够提升商业问题的分析与解决能力。
**5.	提升协作和问题解决能力**
项目开发过程中，学生将以模拟团队协作模式进行开发，涉及从任务分解到问题解决的全链路协作。团队成员可能分工负责不同的模块，如用户管理、订单处理或数据存储。在任务完成的过程中，学生需要协调资源、讨论设计方案并解决开发中遇到的技术难题。这样的经历将帮助学生掌握团队合作的基本技巧，包括分工明确、定期沟通和目标管理，从而提高整体协作效率。
**6.	培养团队协作能力**
在开发WMS系统的过程中，学生需要与团队成员合作，共同完成复杂项目。团队协作不仅包括技术上的分工合作，还需要解决开发过程中出现的各种问题，如需求冲突、接口设计不一致等。学生将通过参与团队讨论和制定计划，学习如何高效地沟通意见、合理分配任务并按照进度推进项目。此外，学生还将在团队协作中培养责任感和解决冲突的能力，为未来的实际工作环境做好充分准备。

### 二、实验要求
利用JAVA和MySQL开发一个WMS系统，包括以下核心模块：
- 注册和登录功能：支持用户角色区分（管理员与员工）。
- 商品管理：商品分类展示、信息查看及更新。
- 日志管理：记录商品入库和出库操作。
- 订单管理：员工可根据库存提出订单需求。

### 三、实验环境
开发工具：IntelliJ IDEA
数 据 库：MySQL 8.0
操作系统：Windows 10 
语    言：Java

### 四、实验过程
（一）需求分析
系统用户：管理员与员工。
功能模块：
     注册与登录。
      商品管理（包括分类展示、信息查看与更新）。
      日志记录（入库/出库操作日志）。
      订单管理。


（二）概要设计
使用UML类图对系统模块的分布情况进行详细展示，全面分析用户角色管理模块、商品管理模块以及日志记录模块之间的关系和交互机制。类图应直观体现各模块的核心职责划分，包括模块内主要类的功能定位及其属性和方法。通过使用继承、依赖、聚合、组合等关联类型，精准表达类与类之间的层次关系和交互方式。此外，图中应标注关键的操作流程和数据流动方向，如用户角色如何与商品管理模块交互、日志记录模块如何捕获和存储重要的操作记录等。最终目标是通过清晰的结构化表达，使系统的功能架构和设计逻辑一目了然，便于后续的开发实施和维护优化。

![WMS.png](https://s2.loli.net/2024/12/09/XnsIihrmuDBlLSP.png)

 
（三）详细设计
界面设计：设计登录页面、管理员主界面、员工主界面及商品查看界面。
    数据库设计：设计员工管理表、商品种类表、商品信息表、入库日志表、出库日志表、订单表

