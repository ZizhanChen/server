<p align="center">
    <img src="logo.png" />
</p>

<h1 align="center">gotify/server</h1>

<p align="center">
    <a href="https://travis-ci.org/gotify/server">
        <img alt="Build Status" src="https://travis-ci.org/gotify/server.svg?branch=master">
    </a>
    <a href="https://codecov.io/gh/gotify/server">
        <img alt="codecov" src="https://codecov.io/gh/gotify/server/branch/master/graph/badge.svg">
    </a>
     <a href="https://goreportcard.com/report/github.com/gotify/server">
        <img alt="Go Report Card" src="https://goreportcard.com/badge/github.com/gotify/server">
    </a>
    <a href="https://github.com/gotify/server/blob/master/docs/spec.json">
        <img alt="Swagger Valid" src="https://img.shields.io/swagger/valid/2.0/https/raw.githubusercontent.com/gotify/server/master/docs/spec.json.svg">
    </a>
    <a href="https://app.fossa.io/projects/git%2Bgithub.com%2Fgotify%2Fserver">
        <img alt="FOSSA Status" src="https://app.fossa.io/api/projects/git%2Bgithub.com%2Fgotify%2Fserver.svg?type=shield">
    </a>
    <a href="https://github.com/gotify/server/releases/latest">
        <img alt="latest release" src="https://img.shields.io/github/release/gotify/server.svg">
    </a>
</p>

## Intro
We wanted a simple server for sending and receiving messages (in real time per web socket). For this, not many open source projects existed and most of the existing ones were abandoned. Also, a requirement was that it can be self-hosted. We know there are many free and commercial push services out there.

## Features

<img alt="Gotify UI screenshot" src="ui.png" align="right" width="500px"/>

* send messages via REST-API
* receive messages via web socket
* manage users, clients and applications
* [API Docs](https://gotify.net/api-docs) (also available at `/docs`)
* Web-UI -> [./ui](ui)
* CLI for sending messages -> [gotify/cli](https://github.com/gotify/cli)
* Android-App -> [gotify/android](https://github.com/gotify/android)

[<img src="https://play.google.com/intl/en_gb/badges/images/generic/en_badge_web_generic.png" alt="Get it on Google Play" width="150" />][playstore]
[<img src="https://f-droid.org/badge/get-it-on.png" alt="Get it on F-Droid" width="150"/>][fdroid]

<sub>(Google Play and the Google Play logo are trademarks of Google LLC.)</sub>

---

**[Documentation](https://gotify.net/docs)**

[Install](https://gotify.net/docs/install) ᛫
[Configuration](https://gotify.net/docs/config) ᛫
[REST-API](https://gotify.net/api-docs) ᛫
[Setup Dev Environment](https://gotify.net/docs/dev-environment)

## Versioning
We use [SemVer](http://semver.org/) for versioning. For the versions available, see the
[tags on this repository](https://github.com/gotify/server/tags).

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

 [playstore]: https://play.google.com/store/apps/details?id=com.github.gotify
 [fdroid]: https://f-droid.org/de/packages/com.github.gotify/
