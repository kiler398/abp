<!--﻿## Module Development Best Practices & Conventions-->
﻿## 模块化开发最佳实践与约定
 
<!--### Introduction-->
### 简介

<!--This document describes the **best practices** and **conventions** for those who want to develop **modules** that satisfy the following specifications:-->
本文档为开发**模块化**应用的开发人员提供了以下**最佳实践** 以及 **约定**：

<!--
* Develop modules that conform to the **Domain Driven Design** patterns & best practices.
* Develop modules with **DBMS and ORM independence**.
* Develop modules that can be used as a **remote service / microservice** as well as being compatible with a **monolithic** application.-->

* 开发模块符合**领域驱动设计**模式以及对应的最佳实践.
* 开发模块 with **DBMS and ORM independence**.
* Develop modules that can be used as a **remote service / microservice** as well as being compatible with a **monolithic** application.

Also, this guide is mostly usable for general **application development**.

<!--### Guides-->
### 指南

* Overall
  * [Module Architecture](Module-Architecture.md)
* Domain Layer
  * [Entities](Entities.md)
  * [Repositories](Repositories.md)
  * [Domain Services](Domain-Services.md)
* Application Layer
  * [Application Services](Application-Services.md)
  * [Data Transfer Objects](Data-Transfer-Objects.md)
* Data Access
  * [Entity Framework Core Integration](Entity-Framework-Core-Integration.md)
  * [MongoDB Integration](MongoDB-Integration.md)  

## See Also

* [E-Book: Implementing Domain Driven Design](https://abp.io/books/implementing-domain-driven-design)
