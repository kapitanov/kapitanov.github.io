<!--
**kapitanov/kapitanov** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

# Hi there 👋 I'm Albert

I am a backend developer with a focus on software design and architecture having 10+ years of experience. I've engaged in the
development and support of web and desktop applications, both developing new features and migrating from legacy stack
to modern technologies and tools. My main responsibilities were design and development of server parts of web applications,
development of desktop applications for Windows, database and infrastructure design.

My primary programming language and platform are C#/.NET (Core) and Golang. Also I have notable experience JavaScript ecosystem including frontend development and development of utilitary web services on NodeJS platform.

# Social

[![Linkedin Badge](https://img.shields.io/badge/-@albertkapitanov-blue?style=for-the-badge&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/albertkapitanov/)](https://www.linkedin.com/in/albertkapitanov)
[![Github Badge](https://img.shields.io/badge/-@kapitanov-black?style=for-the-badge&logo=github&logoColor=white&link=[https://www.linkedin.com/in/albertkapitanov/](https://github.com/kapitanov))](https://github.com/kapitanov)
[![Reddit Badge](https://img.shields.io/badge/-@al__bert__k-FF4500?style=for-the-badge&logo=reddit&logoColor=white)](https://www.reddit.com/u/al_bert_k)

# My notable projects

## [Moex Bond Recommender](https://github.com/kapitanov/moex-bond-recommender)

A web service that provides basic analytics on MOEX's bonds.

Web service models a single investing strategy:
acquiring a bond on its current market price and holding a position until bond's maturiry.

Service evaluates:

* amount to invest
* sum of payments till maturity
* personal income tax
* profit/loss (both relative and absolute)
* a normalized interest rate till maturity

![Go](https://img.shields.io/badge/Go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)
![PostreSQL](https://img.shields.io/badge/PostreSQL-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED.svg?style=for-the-badge&logo=docker&logoColor=white)

## [Backup Monitor](https://github.com/ITGlobal/backupmonitor)

Small server-side app that serves a simple purpose: to receive, manage and monitor various backups.

Features:

* App receives a generic backup files via HTTP(S)
* App stores backups either on local filesystem or on any S3-compatible service
* App keeps at least N last backups for each target
* App notifies your team via Slack/Telegram/Webhooks if something goes wrong

![Go](https://img.shields.io/badge/Go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-%23B52E31.svg?style=for-the-badge&logo=angular&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED.svg?style=for-the-badge&logo=docker&logoColor=white)
![Amazon S3](https://img.shields.io/badge/Amazon%20S3-569A31.svg?style=for-the-badge&logo=amazons3&logoColor=white)

## [dotnet-package-cache-gen](https://github.com/ITGlobal/dotnet-package-cache-gen)

Tiny tool to generate cache files for Docker-powered .NET SDK projects.

This toos helps you to setup a docker-based builds for .NET Core projects with proper Docker image caching.

![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=dotnet&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED.svg?style=for-the-badge&logo=docker&logoColor=white)

## [notion2html](https://github.com/kapitanov/notion2html)

An app than generates a static website from [Notion](https://www.notion.so/) and watches for changes.

![Go](https://img.shields.io/badge/Go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED.svg?style=for-the-badge&logo=docker&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000.svg?style=for-the-badge&logo=notion&logoColor=white)

## [habrabot](https://github.com/kapitanov/habrabot)

A telegram bot that publishes items from an RSS feed into a Telegram channel.

Inially it has been written for [habr.com](https://habr.com) but can be used for any RSS feed.

![Go](https://img.shields.io/badge/Go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED.svg?style=for-the-badge&logo=docker&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram-26A5E4.svg?style=for-the-badge&logo=telegram&logoColor=white)

## [auto-github-backup](https://github.com/kapitanov/auto-github-backup)

This app makes a backup daily of your GitHub repositories, uploads them to S3 object storage and keeps up to defined number of backups.

![Python](https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED.svg?style=for-the-badge&logo=docker&logoColor=white)
![Amazon S3](https://img.shields.io/badge/Amazon%20S3-569A31.svg?style=for-the-badge&logo=amazons3&logoColor=white)

## [ITGlobal.CLI](https://github.com/ITGlobal/CLI)

`ITGlobal.CLI` is a powerful library to build used-friendly command-line applications wit C#.

Features:

* Colored console output
* Ctrl+C/SIGINT interceptor
* Unified error handling
* No-Colors mode
* Command line parser (supporting switches, options, positional arguments, nested commands and built-in auto generated help)
* ASCII tables (both data-driven tables and free-format (fluent) tables)
* Terminal live output (including spinners, progress bars and live text entries)

![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=dotnet&logoColor=white)

# Skills

* **Backend:** C#, .NET, Go, NodeJS, EntityFramework, Dapper, Newtonsoft.JSON, GORM.
* **Frontend:** TypeScript, JavaScript, VueJS, Angular, Blazor Server, React, HTML, CSS.
* **Desktop:** WinForms, WPF.
* **Tests:** xUnit, Moq, testify.
* **Software design:** DDD, TDD, RESTful API, SOLID, OOP, OpenAPI, Design Patterns.
* **Databases:** PostreSQL, MS SQL Server, MongoDB, Redis, SQLite, Memcached.
* **Message queues and brokers:** Kafka, RabbitMQ, ZeroMQ.
* **Intrastructure:** Docker, Docker Compose, Kubernetes, Helm, Amazon S3.
* **CI/CD:** Bitbucket Pipelines, Gitlab Pipelines, TeamCity, Github Actions.
* **IDEs and tools:** Visual Studio, VSCode, Rider, GoLand, DataGrip, Bash, Powershell, Git, Subversion, Lens, Studio 3T.

---

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=kapitanov&show_icons=true&hide_border=true&hide_title=true)
![Most Used Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=kapitanov&hide_border=true&layout=compact&hide=logos,g-code,hlsl)

![thophies](https://github-profile-trophy.vercel.app/?username=kapitanov&column=8)
