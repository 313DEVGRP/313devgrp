<a href="https://www.a-rms.net">
    <img alt="a-rms concept" src="https://www.a-rms.net/arms/img/screenshot/title.png" style="width: 100%">
</a>

# 📜 A-RMS is.
ALM <sup>( Jira, Redmine, Gitlab... )</sup> integrated<br>
Requirement Base<br>
Project Management System

# 📚 Documentation
> ⚠️ This is the documentation of **A-RMS** 
> which includes [unreleased features](http://313.co.kr/php/gnuboard5/bbs/board.php?bo_table=releasenote) planned for next release.<br>
> See documentation for current [**User Manual**](http://313.co.kr/document/dist/)



## 🦮 Setup

There are several ways to setup metrics, each having its advantages and disadvantages:

* 🐳 A-RMS 는 Docker 를 지향합니다.
    * ✔️ Docker Swarm Cluster 를 통하여, OnPremise 환경을 지원하며,
    * ✔️ Kubernetes 를 통하여, Cloud 환경을 지원하며, 멀티 테넌시를 활용한 SaaS 서비스를 제공합니다.
* 🔧 개발환경에 관한 내용은 아래를 참조 부탁드립니다.
    * ✔️ Spring Profile 은 dev 로 고정하시고, 각 MSA 모듈의 Root Path에는 개발규칙.txt 가 존재합니다.
    * ✔️ 또한, README.md 파일을 통해서 필요한 패키지 정보와 함께 아키텍쳐를 구성할 수 있도록 지원했습니다.

## 🧬 PLE Architecture
Templates lets you change general appearance of rendered metrics.

<img alt="a-rms concept" src="https://www.a-rms.net/arms/img/screenshot/arc16.png" style="width: 100%">

## 🧩 Plugins

Plugins provide additional content and lets you customize rendered metrics.

**📦 Maintained by core team**

* **Core plugins**
    * [🗃️ Base content <sub>`base`</sub>](/source/plugins/base/README.md)
    * [🧱 Core <sub>`core`</sub>](/source/plugins/core/README.md)
* **GitHub plugins**
    * [🏆 Achievements <sub>`achievements`</sub>](/source/plugins/achievements/README.md)
    * [📰 Recent activity <sub>`activity`</sub>](/source/plugins/activity/README.md)

**🎲 Maintained by community**
* **[Community plugins](/source/plugins/community/README.md)**
    * [🧠 16personalities <sub>`16personalities`</sub>](/source/plugins/community/16personalities/README.md) by [@lowlighter](https://github.com/lowlighter)
    * [♟️ Chess <sub>`chess`</sub>](/source/plugins/community/chess/README.md) by [@lowlighter](https://github.com/lowlighter)

## 💪 Contributing

If you are interested in contributing, the following resources may interest you:

* [💪 Contribution guide](/CONTRIBUTING.md)
* [🧬 Architecture](/ARCHITECTURE.md)
* [📜 License](/LICENSE)

Use [`💬 discussions`](https://github.com/lowlighter/metrics/discussions) for feedback, new features suggestions, bugs reports or to request help for installation.


## 📜 License

```
LGPL2 License & Commercial License
Copyright 2012-present (c)313DEVGRP
```