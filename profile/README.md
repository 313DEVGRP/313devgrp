# 📊 Metrics [<img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=280144&theme=dark" alt="" align="right" width="190" height="41">](https://www.producthunt.com/posts/github-metrics?utm_source=badge-featured&utm_medium=badge&utm_source=badge-github-metrics)

[![Continuous integration](https://github.com/lowlighter/metrics/actions/workflows/ci.yml/badge.svg)](https://github.com/lowlighter/metrics/actions/workflows/ci.yml)

Generate metrics that can be embedded everywhere, including your GitHub profile readme! Supports users, organizations, and even repositories!

<table>
  <tr>
    <th align="center">For user accounts</th>
    <th align="center">For organization accounts</th>
  </tr>
  <tr>
    <td align="center">
<img alt="" width="400" src="https://github.com/lowlighter/metrics/blob/examples/metrics.classic.svg" alt=""></img>
</td>
<td align="center">
<img alt="" width="400" src="https://github.com/lowlighter/metrics/blob/examples/metrics.organization.svg" alt=""></img>
</td>
  </tr>
  <tr>
    <th colspan="2" align="center">
      <h3><a href="/README.md#-plugins">🧩 Customizable with 47 plugins and 335 options!</a></h3>
    </th>
  </tr>
  <tr>
    <th><a href="source/plugins/isocalendar/README.md">📅 Isometric commit calendar</a></th>
    <th><a href="source/plugins/languages/README.md">🈷️ Languages activity</a></th>
  </tr>
  <tr>
        <td  align="center">
        <details open><summary>Full year calendar</summary><img alt="" width="400" src="https://github.com/lowlighter/metrics/blob/examples/metrics.plugin.isocalendar.fullyear.svg" alt=""></img></details>
        <details><summary>Half year calendar</summary><img alt="" width="400" src="https://github.com/lowlighter/metrics/blob/examples/metrics.plugin.isocalendar.svg" alt=""></img></details>
        <img width="900" height="1" alt="">
      </td>
        <td  align="center">
        <details open><summary>Indepth analysis (clone and analyze repositories)</summary><img alt="" width="400" src="https://github.com/lowlighter/metrics/blob/examples/metrics.plugin.languages.indepth.svg" alt=""></img></details>
        <details open><summary>Recently used (analyze recent activity events)</summary><img alt="" width="400" src="https://github.com/lowlighter/metrics/blob/examples/metrics.plugin.languages.recent.svg" alt=""></img></details>
        <details><summary>Default algorithm</summary><img alt="" width="400" src="https://github.com/lowlighter/metrics/blob/examples/metrics.plugin.languages.svg" alt=""></img></details>
        <details><summary>Default algorithm (with details)</summary><img alt="" width="400" src="https://github.com/lowlighter/metrics/blob/examples/metrics.plugin.languages.details.svg" alt=""></img></details>
        <img width="900" height="1" alt="">
      </td>
  </tr>
 
</table>


# 📚 Documentation


> <sup>*⚠️ This is the documentation of **v3.35-beta** (`@master`/`@main` branches) which includes [unreleased features](https://github.com/lowlighter/metrics/compare/latest...master) planned for next release. See documentation for current released version [**v3.34** (`@latest` branch) here](https://github.com/lowlighter/metrics/blob/latest/README.md).* </sup>



## 🦮 Setup

There are several ways to setup metrics, each having its advantages and disadvantages:

* [⚙️ Using GitHub Action on a profile repository *(~10 min)*](/.github/readme/partials/documentation/setup/action.md)
    * ✔️ All features
    * ✔️ High availability (no downtimes)
    * ➖ Configuration can be a bit time-consuming
* [💕 Using the shared instance *(~1 min)*](/.github/readme/partials/documentation/setup/shared.md)
    * ✔️ Easily configurable and previewable
    * ➖ Limited features *(compute-intensive features are disabled)*
* [🏗️ Deploying a web instance *(~20 min)*](/.github/readme/partials/documentation/setup/web.md)
    * ✔️ Create another shared instance
    * ➖ Requires some sysadmin knowledge
* [🐳 Using command line with docker *(~2 min)*](/.github/readme/partials/documentation/setup/docker.md)
    * ✔️ Suited for one-time rendering
* [🔧 Local setup for development *(~20 min)*](/.github/readme/partials/documentation/setup/local.md)

Additional resources for setup:
* [🏦 Configure metrics for organizations](/.github/readme/partials/documentation/organizations.md)
* [🏠 Run metrics on self-hosted runners](/.github/readme/partials/documentation/selfhosted.md)
* [🧰 Template/Plugin compatibility matrix](/.github/readme/partials/documentation/compatibility.md)
## 🖼️ Templates

Templates lets you change general appearance of rendered metrics.


* [📗 Classic template <sub>`classic`</sub>](/source/templates/classic/README.md)
* [📘 Repository template <sub>`repository`</sub>](/source/templates/repository/README.md)
* [📙 Terminal template <sub>`terminal`</sub>](/source/templates/terminal/README.md)
* [📒 Markdown template <sub>`markdown`</sub>](/source/templates/markdown/README.md)
* [📕 Community templates <sub>`community`</sub>](/source/templates/community/README.md)

## 🧩 Plugins

Plugins provide additional content and lets you customize rendered metrics.

**📦 Maintained by core team**

* **Core plugins**
    * [🗃️ Base content <sub>`base`</sub>](/source/plugins/base/README.md)
    * [🧱 Core <sub>`core`</sub>](/source/plugins/core/README.md)
* **GitHub plugins**
    * [🏆 Achievements <sub>`achievements`</sub>](/source/plugins/achievements/README.md)
    * [📰 Recent activity <sub>`activity`</sub>](/source/plugins/activity/README.md)
    * [📆 Commit calendar <sub>`calendar`</sub>](/source/plugins/calendar/README.md)
    * [♐ Random code snippet <sub>`code`</sub>](/source/plugins/code/README.md)
    * [🏅 Repository contributors <sub>`contributors`</sub>](/source/plugins/contributors/README.md)
    * [💬 Discussions <sub>`discussions`</sub>](/source/plugins/discussions/README.md)
    * [🎟️ Follow-up of issues and pull requests <sub>`followup`</sub>](/source/plugins/followup/README.md)
    * [🎫 Gists <sub>`gists`</sub>](/source/plugins/gists/README.md)
    * [💡 Coding habits and activity <sub>`habits`</sub>](/source/plugins/habits/README.md)
    * [🙋 Introduction <sub>`introduction`</sub>](/source/plugins/introduction/README.md)
    * [📅 Isometric commit calendar <sub>`isocalendar`</sub>](/source/plugins/isocalendar/README.md)
    * [🈷️ Languages activity <sub>`languages`</sub>](/source/plugins/languages/README.md)
    * [📜 Repository licenses <sub>`licenses`</sub>](/source/plugins/licenses/README.md)
    * [👨‍💻 Lines of code changed <sub>`lines`</sub>](/source/plugins/lines/README.md)
    * [🎩 Notable contributions <sub>`notable`</sub>](/source/plugins/notable/README.md)
    * [🧑‍🤝‍🧑 People <sub>`people`</sub>](/source/plugins/people/README.md)
    * [🗂️ GitHub projects <sub>`projects`</sub>](/source/plugins/projects/README.md)
    * [🎭 Comment reactions <sub>`reactions`</sub>](/source/plugins/reactions/README.md)
    * [📓 Featured repositories <sub>`repositories`</sub>](/source/plugins/repositories/README.md)
    * [🌇 GitHub Skyline <sub>`skyline`</sub>](/source/plugins/skyline/README.md)
    * [💕 GitHub Sponsors <sub>`sponsors`</sub>](/source/plugins/sponsors/README.md)
    * [💝 GitHub Sponsorships <sub>`sponsorships`</sub>](/source/plugins/sponsorships/README.md)
    * [✨ Stargazers <sub>`stargazers`</sub>](/source/plugins/stargazers/README.md)
    * [💫 Star lists <sub>`starlists`</sub>](/source/plugins/starlists/README.md)
    * [🌟 Recently starred repositories <sub>`stars`</sub>](/source/plugins/stars/README.md)
    * [💭 GitHub Community Support <sub>`support`</sub>](/source/plugins/support/README.md) <sub>`⚠️ deprecated`</sub>
    * [📌 Starred topics <sub>`topics`</sub>](/source/plugins/topics/README.md)
    * [🧮 Repositories traffic <sub>`traffic`</sub>](/source/plugins/traffic/README.md)
* **Social plugins**
    * [🌸 Anilist watch list and reading list <sub>`anilist`</sub>](/source/plugins/anilist/README.md)
    * [🗳️ Leetcode <sub>`leetcode`</sub>](/source/plugins/leetcode/README.md)
    * [🎼 Music activity and suggestions <sub>`music`</sub>](/source/plugins/music/README.md)
    * [⏱️ Google PageSpeed <sub>`pagespeed`</sub>](/source/plugins/pagespeed/README.md)
    * [✒️ Recent posts <sub>`posts`</sub>](/source/plugins/posts/README.md)
    * [🗼 Rss feed <sub>`rss`</sub>](/source/plugins/rss/README.md)
    * [🗨️ Stack Overflow <sub>`stackoverflow`</sub>](/source/plugins/stackoverflow/README.md)
    * [🕹️ Steam <sub>`steam`</sub>](/source/plugins/steam/README.md)
    * [🐤 Latest tweets <sub>`tweets`</sub>](/source/plugins/tweets/README.md) <sub>`⚠️ deprecated`</sub>
    * [⏰ WakaTime <sub>`wakatime`</sub>](/source/plugins/wakatime/README.md)

**🎲 Maintained by community**
* **[Community plugins](/source/plugins/community/README.md)**
    * [🧠 16personalities <sub>`16personalities`</sub>](/source/plugins/community/16personalities/README.md) by [@lowlighter](https://github.com/lowlighter)
    * [♟️ Chess <sub>`chess`</sub>](/source/plugins/community/chess/README.md) by [@lowlighter](https://github.com/lowlighter)
    * [🪙 Crypto <sub>`crypto`</sub>](/source/plugins/community/crypto/README.md) by [@dajneem23](https://github.com/dajneem23)
    * [🥠 Fortune <sub>`fortune`</sub>](/source/plugins/community/fortune/README.md) by [@lowlighter](https://github.com/lowlighter)
    * [💉 Nightscout <sub>`nightscout`</sub>](/source/plugins/community/nightscout/README.md) by [@legoandmars](https://github.com/legoandmars)
    * [💩 PoopMap plugin <sub>`poopmap`</sub>](/source/plugins/community/poopmap/README.md) by [@matievisthekat](https://github.com/matievisthekat)
    * [📸 Website screenshot <sub>`screenshot`</sub>](/source/plugins/community/screenshot/README.md) by [@lowlighter](https://github.com/lowlighter)
    * [🦑 Splatoon <sub>`splatoon`</sub>](/source/plugins/community/splatoon/README.md) by [@lowlighter](https://github.com/lowlighter)
    * [💹 Stock prices <sub>`stock`</sub>](/source/plugins/community/stock/README.md) by [@lowlighter](https://github.com/lowlighter)


## 💪 Contributing

If you are interested in contributing, the following resources may interest you:

* [💪 Contribution guide](/CONTRIBUTING.md)
* [🧬 Architecture](/ARCHITECTURE.md)
* [📜 License](/LICENSE)
* **:octocat: GitHub resources**
    * [📖 GitHub GraphQL API](https://docs.github.com/en/graphql)
    * [📖 GitHub GraphQL Explorer](https://docs.github.com/en/free-pro-team@latest/graphql/overview/explorer)
    * [📖 GitHub Rest API](https://docs.github.com/en/rest)
    * [📖 GitHub Octicons](https://github.com/primer/octicons)

Use [`💬 discussions`](https://github.com/lowlighter/metrics/discussions) for feedback, new features suggestions, bugs reports or to request help for installation.


## 📜 License

```
MIT License
Copyright (c) 2020-present lowlighter
```

![Sponsors](https://github.com/lowlighter/metrics/blob/examples/metrics.sponsors.svg)

