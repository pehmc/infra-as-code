<div align="center">
  <h1>Infra as Code</h1>
  <p>
     IT基础设施工程
    <br />
    <a href="https://github.com/pehmc/infra-playbook/releases">下载pdf</a>
    ·
    <a href="https://github.com/pehmc/infra-playbook/issues">报告错误</a>
  </p>
</div>

<div align="center">

<p align="center">
  <a href="https://www.gnu.org/licenses/agpl-2.0.html"><img src="https://img.shields.io/badge/License-AGPL--2.0-blue.svg" alt="License: AGPL-2.0"></a>
  <a href="https://www.bing.com/"><img src="https://img.shields.io/badge/Platform-Web-green.svg" alt="Platform: Web"></a>
  <a href="http://linux-wiki.cn/wiki/Shell"><img src="https://img.shields.io/badge/Language-Script-orange.svg" alt="Language: Script"></a>
</p>

</div>

## 目录

- [目录](#目录)
  - [数据中心](#数据中心)
  - [DevOps](#DevOps)

### 数据中心

按照服务对象，规模，特征，可将数据中心划分成三种类型：
- IDC，互联网数据中心。服务对象是互联网客户，规模庞大，在全国范围内部署节点数据中心。通常由电信，移动等ISP维护，带宽和算力按合约交付。
- EDC，企业数据中心。服务对象是企业内部业务部门，规模随企业需求而定。自建自维护，常用于有商密，国密需求的企业。
- NSC，国家超算中心。服务对象是国家科研项目，公共服务，规模体现在算力，存储方面。计算节点密集。

数据中心的基础设施由四种必要的资源组成：
- 存储资源，计算资源，网络资源，配套设施

分别覆盖到了三个层面：
- 硬件，底层软件，架构
### DevOps

DevOps是一套实践体系，特点是自动化，跨团队协作，持续反馈。让软件交付更快，更稳定，更可靠，让开发和运维共同对线上结果负责。

体系的核心概念：
- CI/CD，持续集成，持续交付，持续部署。以流水线的形式，走完从代码提交到上线的全流程。
- IaC，基础设施即代码。用代码声明基础设施，纳入版本管理；一致的环境配置，快速部署环境。
- 平台工程，聚合CI/CD，IaC，监控能力。
- 可观测性，用metrics指标，logs日志，traces链路追踪来监控运行时的内部状态。