# 📜 A-RMS is.
**A**LM<sup>( Jira, Redmine, GitLab... )</sup> integrated<br>
**R**equirement Base<br>
Project **M**anagement **S**ystem

# 📚 Documentation
> ⚠️ This is the documentation of **A-RMS** 
> which includes [unreleased features](http://313.co.kr/php/gnuboard5/bbs/board.php?bo_table=releasenote) planned for next release.<br>
> See documentation for current [**User Manual**](http://313.co.kr/document/dist/)

## 🦮 Setup

A-RMS는 MSA 모듈 구조를 활용했습니다. 따라서, Docker Base 로 Artifact를 운영하며,<br>
각 모듈을 Build 시 Dev profile 을 활용하며, Docker Image 는 Nexus 를 활용하여 <br>
Docker Swarm 및 Kubernetes 를 기반으로 운영한다.

* 🐳 A-RMS 는 Docker 를 지향합니다.
    * ✔️ Docker Swarm Cluster 를 통하여, OnPremise 환경을 지원하며,
    * ✔️ Kubernetes 를 통하여, Cloud 환경을 지원하며, 멀티 테넌시를 활용한 SaaS 서비스를 제공합니다.
* 🔧 개발환경에 관한 내용은 아래를 참조 부탁드립니다.
    * ✔️ Spring Profile 은 dev 로 고정하며, 각 MSA 모듈의 Root Path에는 개발규칙.txt 가 존재합니다.
    * ✔️ 또한, README.md 파일을 통해서 필요한 패키지 정보와 함께 아키텍쳐를 구성할 수 있도록 지원했습니다.

## 🧬 PLE Architecture
313DEVGRP 는 PLE 아키텍쳐를 지향합니다. 따라서, 하나의 아키텍쳐와 알고리즘으로 다양한 제품과 솔루션에 대응하는 방법을 고민합니다.

## 🧩 Plugins

A-RMS는 다양한 오픈소스 플러그인을 활용합니다. 특히나 Spring 의 경우는 Cloud Framework 의 모든 플러그인을 활용하고 있으며,<br>
추가로 활용되는 Frontend 의 플러그인은 custermize 하여 A-RMS와 integration 합니다.<br>
아래는 활용되는 오픈소스의 라이선스를 기재하며, 라이선스 요구를 준수하기 위하여 노력합니다.

**📦 Maintained by core team**

* **Core plugins**
    * [🗃️ Base content <sub>`base`</sub>](/source/plugins/base/README.md)
    * [🧱 Core <sub>`core`</sub>](/source/plugins/core/README.md)
* **GitHub plugins**
    * [🏆 Achievements <sub>`achievements`</sub>](/source/plugins/achievements/README.md)
    * [📰 Recent activity <sub>`activity`</sub>](/source/plugins/activity/README.md)

## 💪 Contributing

우리 A-RMS 팀은 외부 컨트리뷰션에 관대합니다.<br>
단, A-RMS 가 지향하는 목적과 부합하는 기술적 활용에 대한 컨트리뷰션이어야 하며,<br>
A-RMS 팀은 Project Management 의 Scope Creep 을 경계하고 있습니다.

* [💪 Contribution guide](/CONTRIBUTING.md)
* [🧬 Architecture](/ARCHITECTURE.md)
* [📜 License](/LICENSE)


## 📜 License

```
MIT License
Copyright 2012-present (c)313DEVGRP
```
