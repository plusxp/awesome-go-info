# Awesome Go Info

go语言开源项目列表，项目分类及GitHub上的开源项目数据完全来自于[awesome-go](https://github.com/avelino/awesome-go) 的[README.md](https://github.com/avelino/awesome-go/blob/master/README.md)文件，通过调用GitHub的API获取仓库信息，展示项目的star数、watch数等，方便查看go语言开源项目的一些相关信息。

_该文件仅包含[awesome-go](https://github.com/avelino/awesome-go) [README.md](https://github.com/avelino/awesome-go/blob/master/README.md)文件中列出的在GitHub上开源的优秀项目，不罗列其它golang相关的网站_
_该文件中的GitHub仓库信息数据会在每天凌晨1点左右更新,当前数据更新于2020-09-02 01:10:02_

- [Awesome Go](#awesome-go)
    - [Audio and Music](#audio-and-music)
    - [Authentication and OAuth](#authentication-and-oauth)
    - [Bot Building](#bot-building)
    - [Command Line](#command-line)
    - [Configuration](#configuration)
    - [Continuous Integration](#continuous-integration)
    - [CSS Preprocessors](#css-preprocessors)
    - [Data Structures](#data-structures)
    - [Database](#database)
    - [Database Drivers](#database-drivers)
        - [Relational Databases](#relational-databases)
        - [NoSQL Databases](#nosql-databases)
    - [Date and Time](#date-and-time)
    - [Distributed Systems](#distributed-systems)
    - [Dynamic DNS](#dynamic-dns)
    - [Email](#email)
    - [Embeddable Scripting Languages](#embeddable-scripting-languages)
    - [Error Handling](#error-handling)
    - [Files](#files)
    - [Financial](#financial)
    - [Forms](#forms)
    - [Functional](#functional)
    - [Game Development](#game-development)
    - [Generation and Generics](#generation-and-generics)
    - [Geographic](#geographic)
    - [Go Compilers](#go-compilers)
    - [Goroutines](#goroutines)
    - [GUI](#gui)
    - [Hardware](#hardware)
    - [Images](#images)
    - [IoT](#iot-internet-of-things)
    - [Job Scheduler](#job-scheduler)
    - [JSON](#json)
    - [Logging](#logging)
    - [Machine Learning](#machine-learning)
    - [Messaging](#messaging)
    - [Microsoft Office](#microsoft-office)
        - [Microsoft Excel](#microsoft-excel)
    - [Miscellaneous](#miscellaneous)
        - [Dependency Injection](#dependency-injection)
        - [Project Layout](#project-layout)
        - [Strings](#strings)
        - [Uncategorized](#uncategorized)
    - [Natural Language Processing](#natural-language-processing)
    - [Networking](#networking)
        - [HTTP Clients](#http-clients)
    - [OpenGL](#opengl)
    - [ORM](#orm)
    - [Package Management](#package-management)
    - [Performance](#performance)
    - [Query Language](#query-language)
    - [Resource Embedding](#resource-embedding)
    - [Science and Data Analysis](#science-and-data-analysis)
    - [Security](#security)
    - [Serialization](#serialization)
    - [Server Applications](#server-applications)
    - [Stream Processing](#stream-processing)
    - [Template Engines](#template-engines)
    - [Testing](#testing)
        - [Testing Frameworks](#testing-frameworks)
        - [Mock](#mock)
        - [Fail injection](#fail-injection)
    - [Text Processing](#text-processing)
        - [Specific Formats](#specific-formats)
        - [Utility](#utility)
    - [Third-party APIs](#third-party-apis)
    - [Utilities](#utilities)
    - [UUID](#uuid)
    - [Validation](#validation)
    - [Version Control](#version-control)
    - [Video](#video)
    - [Web Frameworks](#web-frameworks)
        - [Middlewares](#middlewares)
            - [Actual middlewares](#actual-middlewares)
            - [Libraries for creating HTTP middlewares](#libraries-for-creating-http-middlewares)
        - [Routers](#routers)
    - [Windows](#windows)
    - [XML](#xml)
    - [WebAssembly](#webassembly)
    - [Files](#Files)
    - [File Handling](#file-handling)
- [Tools](#tools)
    - [Code Analysis](#code-analysis)
    - [Editor Plugins](#editor-plugins)
    - [Go Generate Tools](#go-generate-tools)
    - [Go Tools](#go-tools)
    - [Software Packages](#software-packages)
        - [DevOps Tools](#devops-tools)
        - [Other Software](#other-software)
- [Resources](#resources)
    - [Benchmarks](#benchmarks)
    - [Conferences](#conferences)
    - [E-Books](#e-books)
    - [Gophers](#gophers)
    - [Meetups](#meetups)
    - [Twitter](#twitter)
    - [Websites](#websites)
        - [Tutorials](#tutorials)
    - [Style Guides](#style-guides)




# Awesome Go
        

## Audio and Music
        
*Libraries for manipulating audio.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [oto](https://github.com/hajimehoshi/oto) | 637 | 9 | 2017-05-04 | 1 week ago | A low-level library to play sound on multiple platforms. |
| [portaudio](https://github.com/gordonklaus/portaudio) | 392 | 17 | 2015-09-16 | 3 months ago | Go bindings for the PortAudio audio I/O library. |
| [music-theory](https://github.com/go-music-theory/music-theory) | 316 | 15 | 2016-03-17 | 1 month ago | Music theory models in Go. |
| [waveform](https://github.com/mdlayher/waveform) | 301 | 13 | 2014-09-13 | 5 months ago | Go package capable of generating waveform images from audio streams. |
| [portmidi](https://github.com/rakyll/portmidi) | 245 | 11 | 2013-11-10 | 4 months ago | Go bindings for PortMidi. |
| [id3v2](https://github.com/bogem/id3v2) | 167 | 5 | 2016-05-15 | 3 days ago | Fast and powerful ID3 decoding and encodung library written completely in Go. |
| [flac](https://github.com/mewkiz/flac) | 133 | 10 | 2012-11-01 | 8 months ago | Native Go FLAC encoder/decoder with support for FLAC streams. |
| [mix](https://github.com/go-mix/mix) | 128 | 3 | 2016-01-03 | 3 months ago | Sequence-based Go-native audio mixer for music apps. |
| [mp3](https://github.com/tcolgate/mp3) | 113 | 2 | 2015-02-26 | 3 years ago | Native Go MP3 decoder. |
| [malgo](https://github.com/gen2brain/malgo) | 112 | 5 | 2017-11-09 | 6 days ago | Mini audio library. |
| [go-sox](https://github.com/krig/go-sox) | 110 | 8 | 2013-10-08 | 2 years ago | libsox bindings for go. |
| [gaad](https://github.com/Comcast/gaad) | 76 | 10 | 2016-07-11 | 6 months ago | Native Go AAC bitstream parser. |
| [go-taglib](https://github.com/wtolson/go-taglib) | 74 | 6 | 2012-11-20 | 2 years ago | Go bindings for taglib. |
| [minimp3](https://github.com/tosone/minimp3) | 50 | 3 | 2018-01-26 | 1 day ago | Lightweight MP3 decoder library. |
| [EasyMIDI](https://github.com/algoGuy/EasyMIDI) | 35 | 3 | 2018-02-19 | 2 years ago | EasyMidi is a simple and reliable library for working with standard midi file (SMF). |
| [go_mediainfo](https://github.com/zhulik/go_mediainfo) | 32 | 1 | 2015-12-13 | 4 years ago | libmediainfo bindings for go. |
| [vorbis](https://github.com/mccoyst/vorbis) | 27 | 3 | 2013-07-12 | 1 year ago | "Native" Go Vorbis decoder (uses CGO, but has no dependencies). |
| [gosamplerate](https://github.com/dh1tw/gosamplerate) | 10 | 1 | 2016-11-20 | 1 month ago | libsamplerate bindings for go. |

## Authentication and OAuth
        
*Libraries for implementing authentications schemes.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [jwt-go](https://github.com/dgrijalva/jwt-go) | 8247 | 154 | 2012-04-18 | 4 days ago | Golang implementation of JSON Web Tokens (JWT). |
| [casbin](https://github.com/casbin/casbin) | 7522 | 205 | 2017-04-08 | 2 days ago | Authorization library that supports access control models like ACL, RBAC, ABAC. |
| [oauth2](https://github.com/golang/oauth2) | 3068 | 102 | 2014-04-14 | 2 weeks ago | Successor of goauth2. Generic OAuth 2.0 package that comes with JWT, Google APIs, Compute Engine and App Engine support. |
| [goth](https://github.com/markbates/goth) | 2875 | 65 | 2014-10-14 | 1 day ago | provides a simple, clean, and idiomatic way to use OAuth and OAuth2. Handles multiple providers out of the box. |
| [authboss](https://github.com/volatiletech/authboss) | 2358 | 48 | 2015-01-03 | 4 days ago | Modular authentication system for the web. It tries to remove as much boilerplate and "hard things" as possible so that each time you start a new web project in Go, you can plug it in, configure, and start building your app without having to build an authentication system each time. |
| [loginsrv](https://github.com/tarent/loginsrv) | 1656 | 55 | 2016-11-11 | 2 months ago | JWT login microservice with plugable backends such as OAuth2 (Github), htpasswd, osiam. |
| [osin](https://github.com/openshift/osin) | 1619 | 74 | 2013-09-10 | 2 months ago | Golang OAuth2 server library. |
| [go-jose](https://github.com/square/go-jose) | 1598 | 66 | 2014-11-14 | 6 days ago | Fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs. |
| [go-oauth2-server](https://github.com/RichardKnop/go-oauth2-server) | 1580 | 84 | 2015-11-01 | 3 months ago | Standalone, specification-compliant,  OAuth2 server written in Golang. |
| [gologin](https://github.com/dghubble/gologin) | 1255 | 29 | 2015-06-23 | 1 month ago | chainable handlers for login with OAuth1 and OAuth2 authentication providers. |
| [gorbac](https://github.com/mikespook/gorbac) | 1077 | 63 | 2013-12-26 | 1 year ago | provides a lightweight role-based access control (RBAC) implementation in Golang. |
| [scs](https://github.com/alexedwards/scs) | 753 | 19 | 2016-08-08 | 1 month ago | Session Manager for HTTP servers. |
| [permissions2](https://github.com/xyproto/permissions2) | 402 | 13 | 2014-11-19 | 5 months ago | Library for keeping track of users, login states and permissions. Uses secure cookies and bcrypt. |
| [paseto](https://github.com/o1egl/paseto) | 383 | 18 | 2018-01-23 | 2 months ago | Golang implementation of Platform-Agnostic Security Tokens (PASETO). |
| [jwt](https://github.com/pascaldekloe/jwt) | 216 | 12 | 2018-03-21 | 2 weeks ago | Lightweight JSON Web Token (JWT) library. |
| [httpauth](https://github.com/goji/httpauth) | 192 | 7 | 2014-05-26 | 3 weeks ago | HTTP Authentication middleware. |
| [jeff](https://github.com/abraithwaite/jeff) | 191 | 4 | 2018-08-02 | 3 weeks ago | Simple, flexible, secure and idiomatic web session management with pluggable backends. |
| [jwt-auth](https://github.com/adam-hanna/jwt-auth) | 188 | 12 | 2016-07-05 | 4 months ago | JWT middleware for Golang http servers with many configuration options. |
| [jwt](https://github.com/cristalhq/jwt) | 152 | 10 | 2019-07-20 | 3 days ago | Safe, simple and fast JSON Web Tokens for Go. |
| [branca](https://github.com/hako/branca) | 132 | 7 | 2018-01-09 | 3 weeks ago | Golang implementation of Branca Tokens. |
| [session](https://github.com/icza/session) | 104 | 6 | 2016-02-08 | 1 year ago | Go session management for web servers (including support for Google App Engine - GAE). |
| [sessionup](https://github.com/swithek/sessionup) | 88 | 5 | 2019-07-23 | 5 months ago | Simple, yet effective HTTP session management and identification package. |
| [jwt](https://github.com/robbert229/jwt) | 85 | 7 | 2016-06-05 | 1 year ago | Clean and easy to use implementation of JSON Web Tokens (JWT). |
| [go-guardian](https://github.com/shaj13/go-guardian) | 79 | 2 | 2020-05-14 | 3 days ago | Go-Guardian is a golang library that provides a simple, clean, and idiomatic way to create powerful modern API and web authentication that supports LDAP, Basic, Bearer token and Certificate based authentication. |
| [sjwt](https://github.com/brianvoe/sjwt) | 68 | 0 | 2019-06-20 | 11 months ago | Simple jwt generator and parser. |
| [rbac](https://github.com/zpatrick/rbac) | 62 | 3 | 2018-08-02 | 2 years ago | Minimalistic RBAC package for Go applications. |
| [sessions](https://github.com/adam-hanna/sessions) | 54 | 3 | 2017-04-29 | 4 months ago | Dead simple, highly performant, highly customizable sessions service for go http servers. |
| [securecookie](https://github.com/chmike/securecookie) | 39 | 6 | 2017-09-03 | 2 weeks ago | Efficient secure cookie encoding/decoding. |
| [sessiongate-go](https://github.com/f0rmiga/sessiongate-go) | 9 | 2 | 2017-10-20 | 1 year ago | Go session management using the SessionGate Redis module. |
| [signedvalue](https://github.com/sashka/signedvalue) | 8 | 0 | 2018-01-06 | 11 months ago | Signed and timestamped strings compatible with [Tornado's](https://github.com/tornadoweb/tornado) `create_signed_value`, `decode_signed_value`, and therefore `set_secure_cookie` and `get_secure_cookie`. |
| [cookiestxt](https://github.com/mengzhuo/cookiestxt) | 5 | 1 | 2017-10-09 | 2 years ago | provides parser of cookies.txt file format. |
| [scope](https://github.com/SonicRoshan/scope) | 4 | 1 | 2019-09-23 | 7 months ago | Easily Manage OAuth2 Scopes In Go. |

## Bot Building
        
*Libraries for building and working with bots.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [olivia](https://github.com/olivia-ai/olivia) | 2634 | 65 | 2018-06-05 | 1 month ago | A chatbot built with an artificial neural network. |
| [telegram-bot-api](https://github.com/go-telegram-bot-api/telegram-bot-api) | 2329 | 66 | 2015-06-25 | 5 days ago | Simple and clean Telegram bot client. |
| [telebot](https://github.com/tucnak/telebot) | 1424 | 41 | 2015-06-25 | 5 hours ago | Telegram bot framework written in Go. |
| [bot](https://github.com/go-chat-bot/bot) | 604 | 42 | 2015-09-22 | 3 weeks ago | IRC, Slack & Telegram bot written in Go. |
| [slacker](https://github.com/shomali11/slacker) | 444 | 16 | 2017-05-20 | 1 month ago | Easy to use framework to create Slack bots. |
| [kelp](https://github.com/stellar/kelp) | 367 | 40 | 2018-08-08 | 1 day ago | official trading and market-making bot for the [Stellar](https://www.stellar.org/) DEX. Works out-of-the-box, written in Golang, compatible with centralized exchanges and custom trading strategies. |
| [golang-crypto-trading-bot](https://github.com/saniales/golang-crypto-trading-bot) | 332 | 27 | 2017-05-14 | 2 months ago | A golang implementation of a console-based trading bot for cryptocurrency exchanges. |
| [tbot](https://github.com/yanzay/tbot) | 288 | 11 | 2015-09-11 | 2 weeks ago | Telegram bot server with API similar to net/http. |
| [go-sarah](https://github.com/oklahomer/go-sarah) | 177 | 8 | 2016-11-06 | 2 days ago | Framework to build bot for desired chat services including LINE, Slack, Gitter and more. |
| [tenyks](https://github.com/kyleterry/tenyks) | 168 | 15 | 2012-08-26 | 11 months ago | Service oriented IRC bot using Redis and JSON for messaging. |
| [go-twitch-irc](https://github.com/gempir/go-twitch-irc) | 129 | 9 | 2017-03-23 | 2 weeks ago | Libary to write bots for twitch. |
| [hanu](https://github.com/sbstjn/hanu) | 126 | 5 | 2016-09-16 | 3 months ago | Framework for writing Slack bots. |
| [go-tgbot](https://github.com/olebedev/go-tgbot) | 98 | 9 | 2016-12-11 | 2 years ago | Pure Golang Telegram Bot API wrapper, generated from swagger file, session-based router and middleware. |
| [margelet](https://github.com/zhulik/margelet) | 63 | 5 | 2015-11-21 | 4 years ago | Framework for building Telegram bots. |
| [govkbot](https://github.com/nikepan/govkbot) | 33 | 3 | 2016-07-11 | 6 months ago | Simple Go [VK](https://vk.com) bot library. |
| [slackscot](https://github.com/alexandre-normand/slackscot) | 32 | 1 | 2015-10-22 | 1 month ago | Another framework for building Slack bots. |
| [ephemeral-roles](https://github.com/ewohltman/ephemeral-roles) | 30 | 3 | 2017-12-19 | 4 days ago | A Discord bot for managing ephemeral roles based upon voice channel member presence. |
| [micha](https://github.com/onrik/micha) | 17 | 4 | 2016-04-14 | 1 week ago | Go Library for Telegram bot api. |

## Command Line
        
*Libraries for building Console Applications and Console User Interfaces.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [cobra](https://github.com/spf13/cobra) | 18317 | 324 | 2013-09-03 | 2 days ago | Commander for modern Go CLI interactions. |
| [cli](https://github.com/urfave/cli) | 14375 | 299 | 2013-07-13 | 6 days ago | Simple, fast, and fun package for building command line apps in Go (formerly codegangsta/cli). |
| [termui](https://github.com/gizak/termui) | 10128 | 288 | 2015-02-03 | 6 days ago | Go terminal dashboard based on **termbox-go** and inspired by [blessed-contrib](https://github.com/yaronn/blessed-contrib). |
| [gocui](https://github.com/jroimartin/gocui) | 6574 | 132 | 2014-01-04 | 1 month ago | Minimalist Go library aimed at creating Console User Interfaces. |
| [termbox-go](https://github.com/nsf/termbox-go) | 3847 | 101 | 2012-01-12 | 4 months ago | Termbox is a library for creating cross-platform text-based interfaces. |
| [go-prompt](https://github.com/c-bata/go-prompt) | 3175 | 47 | 2017-08-14 | 1 week ago | Library for building a powerful interactive prompt, inspired by [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit). |
| [kingpin](https://github.com/alecthomas/kingpin) | 2914 | 56 | 2014-05-14 | 1 month ago | Command line and flag parser supporting sub commands. |
| [dnote](https://github.com/dnote/dnote) | 1833 | 31 | 2017-03-30 | 1 day ago | A simple command line notebook with multi-device sync. |
| [go-flags](https://github.com/jessevdk/go-flags) | 1744 | 28 | 2012-08-31 | 3 weeks ago | go command line option parser. |
| [uiprogress](https://github.com/gosuri/uiprogress) | 1691 | 35 | 2015-11-17 | 1 year ago | Flexible library to render progress bars in terminal applications. |
| [readline](https://github.com/chzyer/readline) | 1537 | 39 | 2015-09-20 | 9 months ago | Pure golang implementation that provides most features in GNU-Readline under MIT license. |
| [asciigraph](https://github.com/guptarohit/asciigraph) | 1429 | 26 | 2018-06-17 | 2 days ago | Go package to make lightweight ASCII line graph ╭┈╯ in command line apps with no other dependencies. |
| [progressbar](https://github.com/schollz/progressbar) | 1284 | 22 | 2017-10-26 | 5 days ago | Basic thread-safe progress bar that works in every OS. |
| [termdash](https://github.com/mum4k/termdash) | 1270 | 25 | 2018-03-24 | 14 hours ago | Go terminal dashboard based on **termbox-go** and inspired by [termui](https://github.com/gizak/termui). |
| [docopt.go](https://github.com/docopt/docopt.go) | 1253 | 34 | 2013-08-25 | 11 months ago | Command-line arguments parser that will make you smile. |
| [pflag](https://github.com/spf13/pflag) | 1213 | 31 | 2013-08-30 | 1 week ago | Drop-in replacement for Go's flag package, implementing POSIX/GNU-style --flags. |
| [uilive](https://github.com/gosuri/uilive) | 1189 | 19 | 2015-11-16 | 3 months ago | Library for updating terminal output in realtime. |
| [cli](https://github.com/mitchellh/cli) | 1175 | 22 | 2013-11-03 | 4 months ago | Go library for implementing command-line interfaces. |
| [mpb](https://github.com/vbauerster/mpb) | 1074 | 19 | 2016-12-14 | 5 days ago | Multi progress bar for terminal applications. |
| [go-arg](https://github.com/alexflint/go-arg) | 956 | 14 | 2015-11-01 | 2 weeks ago | Struct-based argument parsing in Go. |
| [aurora](https://github.com/logrusorgru/aurora) | 910 | 8 | 2016-11-06 | 1 month ago | ANSI terminal colors that supports fmt.Printf/Sprintf. |
| [gcli](https://github.com/tcnksm/gcli) | 900 | 26 | 2014-06-19 | 2 years ago | The easy way to start building Golang command line applications. |
| [complete](https://github.com/posener/complete) | 714 | 14 | 2017-05-05 | 2 months ago | Write bash completions in Go + Go command bash completion. |
| [liner](https://github.com/peterh/liner) | 703 | 23 | 2012-08-15 | 3 months ago | Go readline-like library for command-line interfaces. |
| [mow.cli](https://github.com/jawher/mow.cli) | 688 | 20 | 2014-12-18 | 2 weeks ago | Go library for building CLI applications with sophisticated flag and argument parsing and validation. |
| [flaggy](https://github.com/integrii/flaggy) | 671 | 18 | 2018-03-05 | 1 month ago | A robust and idiomatic flags package with excellent subcommand support. |
| [uitable](https://github.com/gosuri/uitable) | 580 | 15 | 2015-11-13 | 9 months ago | Library to improve readability in terminal apps using tabular data. |
| [cli](https://github.com/mkideal/cli) | 537 | 22 | 2016-02-26 | 1 month ago | Feature-rich and easy to use command-line package based on golang struct tags. |
| [ops](https://github.com/nanovms/ops) | 474 | 27 | 2018-09-10 | 23 hours ago | Unikernel Builder/Orchestrator. |
| [go-colorable](https://github.com/mattn/go-colorable) | 455 | 19 | 2014-07-30 | 2 months ago | Colorable writer for windows. |
| [go-isatty](https://github.com/mattn/go-isatty) | 439 | 9 | 2014-04-01 | 7 months ago | isatty for golang. |
| [color](https://github.com/gookit/color) | 430 | 10 | 2018-07-01 | 1 week ago | Terminal color rendering tool library, support 16 colors, 256 colors, RGB color rendering output, compatible with Windows. |
| [chalk](https://github.com/ttacon/chalk) | 343 | 9 | 2014-07-18 | 1 year ago | Intuitive package for prettifying terminal/console output. |
| [tabby](https://github.com/cheynewallace/tabby) | 270 | 2 | 2018-12-17 | 1 year ago | A tiny library for super simple Golang tables. |
| [simpletable](https://github.com/alexeyco/simpletable) | 254 | 4 | 2017-03-29 | 1 month ago | Simple tables in terminal with Go. |
| [argparse](https://github.com/akamensky/argparse) | 222 | 11 | 2017-11-24 | 1 week ago | Command line argument parser inspired by Python's argparse module. |
| [go-colortext](https://github.com/daviddengcn/go-colortext) | 205 | 9 | 2013-01-23 | 5 months ago | Go library for color output in terminals. |
| [commandeer](https://github.com/jaffee/commandeer) | 138 | 7 | 2017-10-12 | 1 month ago | Dev-friendly CLI apps: sets up flags, defaults, and usage based on struct fields and tags. |
| [wmenu](https://github.com/dixonwille/wmenu) | 118 | 2 | 2016-04-20 | 2 months ago | Easy to use menu structure for cli applications that prompts users to make choices. |
| [sflags](https://github.com/octago/sflags) | 116 | 5 | 2016-12-04 | 3 months ago | Struct based flags generator for flag, urfave/cli, pflag, cobra, kingpin and other libraries. |
| [clif](https://github.com/ukautz/clif) | 105 | 2 | 2015-05-30 | 1 year ago | Small command line interface framework. |
| [flag](https://github.com/cosiner/flag) | 104 | 5 | 2016-10-05 | 4 months ago | Simple but powerful command line option parsing library for Go supporting subcommand. |
| [flag](https://github.com/zhuah/flag) | 102 | 5 | 2016-10-05 | 1 year ago | Simple but powerful command line option parsing library for Go supporting subcommand. |
| [yacspin](https://github.com/theckman/yacspin) | 90 | 4 | 2019-12-29 | 2 months ago | Yet Another CLi Spinner package, for working with terminal spinners. |
| [job](https://github.com/liujianping/job) | 80 | 1 | 2019-04-09 | 2 months ago | JOB, make your short-term command as a long-term job. |
| [1build](https://github.com/gopinath-langote/1build) | 77 | 6 | 2019-04-23 | 2 weeks ago | Command line tool to frictionlessly manage project-specific commands. |
| [cli](https://github.com/teris-io/cli) | 76 | 1 | 2017-05-24 | 1 year ago | Simple and complete API for building command line interfaces in Go. |
| [cfmt](https://github.com/mingrammer/cfmt) | 75 | 3 | 2018-03-15 | 1 year ago | Contextual fmt inspired by bootstrap color classes. |
| [env](https://github.com/codingconcepts/env) | 60 | 1 | 2017-06-14 | 1 week ago | Tag-based environment configuration for structs. |
| [gocmd](https://github.com/devfacet/gocmd) | 44 | 3 | 2018-01-08 | 2 years ago | Go library for building command line applications. |
| [tabular](https://github.com/InVisionApp/tabular) | 43 | 84 | 2018-04-23 | 2 years ago | Print ASCII tables from command line utilities without the need to pass large sets of data to the API. |
| [wlog](https://github.com/dixonwille/wlog) | 41 | 1 | 2016-04-13 | 7 months ago | Simple logging interface that supports cross-platform color and concurrency. |
| [cmdr](https://github.com/hedzr/cmdr) | 39 | 5 | 2019-05-15 | 1 week ago | A POSIX/GNU style, getopt-like command-line UI Go library. |
| [strumt](https://github.com/antham/strumt) | 38 | 1 | 2017-06-19 | 1 week ago | Library to create prompt chain. |
| [clir](https://github.com/leaanthony/clir) | 36 | 2 | 2019-11-18 | 3 months ago | A Simple and Clear CLI library. Dependency free. |
| [flagvar](https://github.com/sgreben/flagvar) | 34 | 2 | 2018-05-18 | 1 month ago | A collection of flag argument types for Go's standard `flag` package. |
| [ctc](https://github.com/wzshiming/ctc) | 28 | 1 | 2018-04-27 | 1 month ago | The non-invasive cross-platform terminal color library does not need to modify the Print method. |
| [go-getoptions](https://github.com/DavidGamba/go-getoptions) | 27 | 4 | 2015-12-18 | 9 hours ago | Go option parser inspired on the flexibility of Perl’s GetOpt::Long. |
| [argv](https://github.com/cosiner/argv) | 27 | 1 | 2017-01-22 | 4 months ago | Go library to split command line string as arguments array using the bash syntax. |
| [colourize](https://github.com/TreyBastian/colourize) | 20 | 3 | 2015-05-11 | 4 years ago | Go library for ANSI colour text in terminals. |
| [argv](https://github.com/zhuah/argv) | 19 | 1 | 2017-01-22 | 1 year ago | Go library to split command line string as arguments array using the bash syntax. |
| [go-commander](https://github.com/yitsushi/go-commander) | 19 | 1 | 2016-10-10 | 3 months ago | Go library to simplify CLI workflow. |
| [cmd](https://github.com/posener/cmd) | 17 | 2 | 2019-10-29 | 4 months ago | Extends the standard `flag` package to support sub commands and more in idomatic way. |
| [ts](https://github.com/liujianping/ts) | 12 | 0 | 2019-06-25 | 1 year ago | Timestamp convert & compare tool. |
| [sand](https://github.com/Zaba505/sand) | 11 | 1 | 2018-11-18 | 1 year ago | Simple API for creating interpreters and so much more. |
| [go-ataman](https://github.com/workanator/go-ataman) | 9 | 2 | 2017-05-17 | 2 years ago | Go library for rendering ANSI colored text templates in terminals. |

## Configuration
        
*Libraries for configuration parsing.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [viper](https://github.com/spf13/viper) | 13264 | 227 | 2014-04-02 | 5 days ago | Go configuration with fangs. |
| [envconfig](https://github.com/kelseyhightower/envconfig) | 3174 | 42 | 2013-11-06 | 1 week ago | Go library for managing configuration data from environment variables. |
| [godotenv](https://github.com/joho/godotenv) | 3122 | 42 | 2013-07-30 | 2 weeks ago | Go port of Ruby's dotenv library (Loads environment variables from `.env`). |
| [ini](https://github.com/go-ini/ini) | 2166 | 77 | 2014-12-18 | 14 hours ago | Go package to read and write INI files. |
| [env](https://github.com/caarlos0/env) | 1596 | 22 | 2015-07-28 | 1 week ago | Parse environment variables to Go structs (with defaults). |
| [konfig](https://github.com/lalamove/konfig) | 575 | 13 | 2019-01-18 | 1 month ago | Composable, observable and performant config handling for Go for the distributed processing era. |
| [confita](https://github.com/heetch/confita) | 320 | 25 | 2017-12-21 | 2 months ago | Load configuration in cascade from multiple backends into a struct. |
| [store](https://github.com/tucnak/store) | 249 | 5 | 2015-10-03 | 3 years ago | Lightweight configuration manager for Go. |
| [config](https://github.com/JeremyLoy/config) | 248 | 1 | 2019-04-02 | 2 weeks ago | Cloud native application configuration. Bind ENV to structs in only two lines. |
| [config](https://github.com/olebedev/config) | 232 | 8 | 2014-04-21 | 1 year ago | JSON or YAML configuration wrapper with environment variables and flags parsing. |
| [koanf](https://github.com/knadh/koanf) | 212 | 7 | 2019-06-18 | 1 month ago | Light weight, extensible library for reading config in Go applications. Built in support for JSON, TOML, YAML, env, command line. |
| [hjson-go](https://github.com/hjson/hjson-go) | 211 | 9 | 2016-08-05 | 3 months ago | Human JSON, a configuration file format for humans. Relaxed syntax, fewer mistakes, more comments. |
| [config](https://github.com/joshbetz/config) | 203 | 2 | 2017-04-02 | 10 months ago | Small configuration library for Go that parses environment variables, JSON files, and reloads automatically on SIGHUP. |
| [envconfig](https://github.com/vrischmann/envconfig) | 175 | 4 | 2015-04-21 | 3 weeks ago | Read your configuration from environment variables. |
| [config](https://github.com/gookit/config) | 165 | 7 | 2018-07-07 | 1 day ago | application config manage(load,get,set). support JSON, YAML, TOML, INI, HCL. multi file load, data override merge. |
| [cleanenv](https://github.com/ilyakaznacheev/cleanenv) | 139 | 3 | 2019-07-12 | 2 weeks ago | Minimalistic configuration reader (from files, ENV, and wherever you want). |
| [gcfg](https://github.com/go-gcfg/gcfg) | 134 | 7 | 2015-08-17 | 1 month ago | read INI-style configuration files into Go structs; supports user-defined types and subsections. |
| [goconfig](https://github.com/crgimenes/goconfig) | 131 | 11 | 2016-12-18 | 3 months ago | Parses a struct as input and populates the fields of this struct with parameters from command line, environment variables and configuration file. |
| [fig](https://github.com/kkyr/fig) | 123 | 4 | 2020-01-16 | 3 months ago | Tiny library for reading configuration from a file and from environment variables (with validation & defaults). |
| [envh](https://github.com/antham/envh) | 95 | 3 | 2017-01-12 | 1 month ago | Helpers to manage environment variables. |
| [envcfg](https://github.com/tomazk/envcfg) | 92 | 1 | 2014-11-29 | 3 years ago | Un-marshaling environment variables to Go structs. |
| [config](https://github.com/golobby/config) | 75 | 2 | 2019-10-15 | 1 month ago | A lightweight yet powerful config package for Go projects. |
| [harvester](https://github.com/beatlabs/harvester) | 64 | 12 | 2019-04-09 | 2 weeks ago | Harvester, a easy to use static and dynamic configuration package supportig seeding, env vars and Consul integration. |
| [gofigure](https://github.com/ian-kent/gofigure) | 59 | 5 | 2014-11-25 | 11 months ago | Go application configuration made easy. |
| [configuro](https://github.com/sherifabdlnaby/configuro) | 58 | 4 | 2020-04-09 | 1 month ago | opinionated configuration loading & validation framework from ENV and Files focused towards 12-Factor compliant applications. |
| [configure](https://github.com/paked/configure) | 55 | 3 | 2015-06-14 | 1 year ago | Provides configuration through multiple sources, including JSON, flags and environment variables. |
| [xdg](https://github.com/OpenPeeDeeP/xdg) | 55 | 3 | 2017-07-20 | 1 week ago | Cross platform package that follows the [XDG Standard](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html). |
| [aconfig](https://github.com/cristalhq/aconfig) | 55 | 3 | 2020-06-26 | 2 weeks ago | Simple, useful and opinionated config loader. |
| [ingo](https://github.com/schachmat/ingo) | 33 | 1 | 2016-02-07 | 3 years ago | Flags persisted in an ini-like config file. |
| [configuration](https://github.com/BoRuDar/configuration) | 33 | 2 | 2019-11-27 | 2 weeks ago | Library for initializing configuration structs from env variables, files, flags and 'default' tag. |
| [go-aws-ssm](https://github.com/PaddleHQ/go-aws-ssm) | 33 | 15 | 2019-01-24 | 2 weeks ago | Go package that fetches parameters from AWS System Manager - Parameter Store. |
| [go-up](https://github.com/ufoscout/go-up) | 28 | 1 | 2018-02-18 | 7 months ago | A simple configuration library with recursive placeholders resolution and no magic. |
| [mini](https://github.com/sasbury/mini) | 25 | 1 | 2015-04-29 | 1 year ago | Golang package for parsing ini-style configuration files. |
| [conflate](https://github.com/the4thamigo-uk/conflate) | 17 | 0 | 2018-02-01 | 1 year ago | Library/tool to merge multiple JSON/YAML/TOML files from arbitrary URLs, validation against a JSON schema, and application of default values defined in the schema. |
| [genv](https://github.com/sakirsensoy/genv) | 16 | 1 | 2019-07-15 | 1 year ago | Read environment variables easily with dotenv support. |
| [hocon](https://github.com/gurkankaymak/hocon) | 12 | 1 | 2020-03-01 | 21 hours ago | Configuration library for working with the HOCON(a human-friendly JSON superset) format, supports features like environment variables, referencing other values, comments and multiple files. |
| [envconf](https://github.com/ian-kent/envconf) | 10 | 1 | 2014-10-26 | 5 years ago | Configuration from environment. |
| [go-ssm-config](https://github.com/ianlopshire/go-ssm-config) | 8 | 1 | 2019-12-02 | 1 month ago | Go utility for loading configuration parameters from AWS SSM (Parameter Store). |
| [sprbox](https://github.com/oblq/sprbox) | 4 | 2 | 2018-07-17 | 4 months ago | Build-environment aware toolbox factory and agnostic config parser (YAML, TOML, JSON and Environment vars). |
| [env](https://github.com/nasermirzaei89/env) | 2 | 0 | 2019-07-24 | 3 months ago | Simple useful package for read environment variables. |
| [go-ini](https://github.com/subpop/go-ini) | 2 | 1 | 2019-09-11 | 3 months ago | A Go package that marshals and unmarshals INI-files. |
| [swap](https://github.com/oblq/swap) | 2 | 1 | 2020-04-12 | 3 months ago | Instantiate/configure structs recursively, based on build environment. (YAML, TOML, JSON and env). |
| [typenv](https://github.com/diegomarangoni/typenv) | 2 | 1 | 2020-06-30 | 1 month ago | Minimalistic, zero dependency, typed environment variables library. |

## Continuous Integration
        
*Tools for help with continuous integration.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [drone](https://github.com/drone/drone) | 21667 | 586 | 2014-02-07 | 1 day ago | Drone is a Continuous Integration platform built on Docker, written in Go. |
| [cds](https://github.com/ovh/cds) | 3055 | 75 | 2016-10-11 | 1 hour ago | Enterprise-Grade CI/CD and DevOps Automation Open Source Platform. |
| [goveralls](https://github.com/mattn/goveralls) | 659 | 13 | 2013-04-17 | 2 days ago | Go integration for Coveralls.io continuous code coverage tracking system. |
| [overalls](https://github.com/go-playground/overalls) | 105 | 3 | 2015-07-30 | 8 months ago | Multi-Package go project coverprofile for tools like goveralls. |
| [duci](https://github.com/duck8823/duci) | 57 | 3 | 2018-04-01 | 6 days ago | A simple ci server no needs domain specific languages. |
| [gomason](https://github.com/nikogura/gomason) | 49 | 1 | 2017-11-18 | 1 week ago | Test, Build, Sign, and Publish your go binaries from a clean workspace. |
| [roveralls](https://github.com/lawrencewoodman/roveralls) | 14 | 1 | 2016-06-26 | 2 years ago | Recursive coverage testing tool. |

## CSS Preprocessors
        
*Libraries for preprocessing CSS files.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gcss](https://github.com/yosssi/gcss) | 437 | 17 | 2014-09-04 | 5 years ago | Pure Go CSS Preprocessor. |
| [go-libsass](https://github.com/wellington/go-libsass) | 160 | 7 | 2015-04-19 | 1 year ago | Go wrapper to the 100% Sass compatible libsass project. |

## Data Structures
        
*Generic datastructures and algorithms in Go.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gods](https://github.com/emirpasic/gods) | 8778 | 356 | 2015-03-04 | 2 weeks ago | Go Data Structures. Containers, Sets, Lists, Stacks, Maps, BidiMaps, Trees, HashSet etc. |
| [go-datastructures](https://github.com/Workiva/go-datastructures) | 5704 | 322 | 2014-10-29 | 5 months ago | Collection of useful, performant, and thread-safe data structures. |
| [golang-set](https://github.com/deckarep/golang-set) | 1617 | 41 | 2013-07-03 | 9 months ago | Thread-Safe and Non-Thread-Safe high-performance sets for Go. |
| [gota](https://github.com/go-gota/gota) | 1330 | 71 | 2016-02-06 | 23 hours ago | Implementation of dataframes, series, and data wrangling methods for Go. |
| [BoomFilters](https://github.com/tylertreat/BoomFilters) | 1281 | 40 | 2015-02-06 | 3 months ago | Probabilistic data structures for processing continuous, unbounded streams. |
| [roaring](https://github.com/RoaringBitmap/roaring) | 948 | 39 | 2014-07-10 | 1 week ago | Go package implementing compressed bitsets. |
| [bloom](https://github.com/willf/bloom) | 871 | 34 | 2011-05-21 | 4 days ago | Go package implementing Bloom filters. |
| [hyperloglog](https://github.com/axiomhq/hyperloglog) | 710 | 17 | 2017-06-18 | 9 months ago | HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction. |
| [cuckoofilter](https://github.com/seiflotfy/cuckoofilter) | 658 | 19 | 2015-06-28 | 3 months ago | Cuckoo filter: a good alternative to a counting bloom filter implemented in Go. |
| [bitset](https://github.com/willf/bitset) | 593 | 31 | 2011-05-11 | 2 weeks ago | Go package implementing bitsets. |
| [trie](https://github.com/derekparker/trie) | 496 | 19 | 2014-03-06 | 3 weeks ago | Trie implementation in Go. |
| [gocache](https://github.com/eko/gocache) | 490 | 14 | 2019-10-05 | 1 week ago | A complete Go cache library with mutiple stores (memory, memcache, redis, ...), chainable, loadable, metrics cache and more. |
| [algorithms](https://github.com/shady831213/algorithms) | 418 | 17 | 2018-01-31 | 1 year ago | Algorithms and data structures.CLRS study. |
| [go-geoindex](https://github.com/hailocab/go-geoindex) | 323 | 69 | 2015-01-22 | 2 years ago | In-memory geo index. |
| [mafsa](https://github.com/smartystreets-archives/mafsa) | 283 | 16 | 2014-11-07 | 1 year ago | MA-FSA implementation with Minimal Perfect Hashing. |
| [goskiplist](https://github.com/ryszard/goskiplist) | 218 | 15 | 2012-05-09 | 10 months ago | Skip list implementation in Go. |
| [merkletree](https://github.com/cbergoon/merkletree) | 208 | 4 | 2017-04-12 | 9 months ago | Implementation of a merkle tree providing an efficient and secure verification of the contents of data structures. |
| [hilbert](https://github.com/google/hilbert) | 202 | 22 | 2015-08-06 | 1 year ago | Go package for mapping values to and from space-filling curves, such as Hilbert and Peano curves. |
| [deque](https://github.com/gammazero/deque) | 172 | 7 | 2018-04-24 | 1 month ago | Fast ring-buffer deque (double-ended queue). |
| [ttlcache](https://github.com/ReneKroon/ttlcache) | 161 | 10 | 2014-12-13 | 2 weeks ago | In-memory string-interface{} cache with various time-based expiration options and callbacks. |
| [go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) | 150 | 6 | 2016-04-01 | 2 weeks ago | Go implementation of Adaptive Radix Tree. |
| [binpacker](https://github.com/zhuangsirui/binpacker) | 149 | 13 | 2016-02-02 | 2 years ago | Binary packer and unpacker helps user build custom binary stream. |
| [gostl](https://github.com/liyue201/gostl) | 144 | 6 | 2019-10-12 | 5 days ago | Data structure and algorithm library for go, designed to provide functions similar to C++ STL. |
| [bloom](https://github.com/zentures/bloom) | 132 | 7 | 2013-09-03 | 2 years ago | Bloom filters implemented in Go. |
| [skiplist](https://github.com/MauriceGit/skiplist) | 128 | 6 | 2018-06-23 | 9 months ago | Very fast Go Skiplist implementation. |
| [iter](https://github.com/disksing/iter) | 122 | 5 | 2019-10-20 | 8 months ago | Go implementation of C++ STL iterators and algorithms. |
| [ring](https://github.com/TheTannerRyan/ring) | 110 | 1 | 2019-01-27 | 10 months ago | Go implementation of a high performance, thread safe bloom filter. |
| [ring](https://github.com/tannerryan/ring) | 109 | 1 | 2019-01-27 | 10 months ago | Go implementation of a high performance, thread safe bloom filter. |
| [go-rquad](https://github.com/arl/go-rquad) | 106 | 3 | 2016-09-12 | 4 months ago | Region quadtrees with efficient point location and neighbour finding. |
| [encoding](https://github.com/zentures/encoding) | 102 | 6 | 2013-09-20 | 2 years ago | Integer Compression Libraries for Go. |
| [levenshtein](https://github.com/agnivade/levenshtein) | 100 | 3 | 2014-07-30 | 2 weeks ago | Implementation to calculate levenshtein distance in Go. |
| [bit](https://github.com/yourbasic/bit) | 93 | 6 | 2017-05-03 | 2 years ago | Golang set data structure with bonus bit-twiddling functions. |
| [conjungo](https://github.com/InVisionApp/conjungo) | 90 | 97 | 2016-12-29 | 1 year ago | A small, powerful and flexible merge library. |
| [goconcurrentqueue](https://github.com/enriquebris/goconcurrentqueue) | 87 | 1 | 2019-01-10 | 3 months ago | Concurrent FIFO queue. |
| [skiplist](https://github.com/gansidui/skiplist) | 71 | 7 | 2014-11-18 | 5 years ago | Skiplist implementation in Go. |
| [remember-go](https://github.com/rocketlaunchr/remember-go) | 60 | 4 | 2019-04-04 | 10 months ago | A universal interface for caching slow database queries (backed by redis, memcached, ristretto, or in-memory). |
| [bloom](https://github.com/yourbasic/bloom) | 55 | 2 | 2017-05-06 | 3 years ago | Golang Bloom filter implementation. |
| [go-mcache](https://github.com/OrlovEvgeny/go-mcache) | 55 | 3 | 2018-04-14 | 7 months ago | Fast in-memory key:value store/cache library. Pointer caches. |
| [count-min-log](https://github.com/seiflotfy/count-min-log) | 51 | 2 | 2015-08-16 | 3 years ago | Go implementation Count-Min-Log sketch: Approximately counting with approximate counters (Like Count-Min sketch but using less memory). |
| [levenshtein](https://github.com/agext/levenshtein) | 49 | 1 | 2016-04-08 | 5 months ago | Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix. |
| [crunch](https://github.com/superwhiskers/crunch) | 42 | 6 | 2019-02-27 | 4 months ago | Go package implementing buffers for handling various datatypes easily. |
| [concurrent-writer](https://github.com/free/concurrent-writer) | 29 | 4 | 2017-09-18 | 2 years ago | Highly concurrent drop-in replacement for `bufio.Writer`. |
| [goset](https://github.com/zoumo/goset) | 26 | 1 | 2017-08-25 | 10 months ago | A useful Set collection implementation for Go. |
| [pipeline](https://github.com/hyfather/pipeline) | 25 | 1 | 2018-04-25 | 2 years ago | An implementation of pipelines with fan-in and fan-out. |
| [hide](https://github.com/emvi/hide) | 24 | 3 | 2019-01-16 | 1 month ago | ID type with marshalling to/from hash to prevent sending IDs to clients. |
| [typ](https://github.com/gurukami/typ) | 21 | 1 | 2019-03-03 | 1 year ago | Null Types, Safe primitive type conversion and fetching value from complex structures. |
| [deque](https://github.com/edwingeng/deque) | 20 | 1 | 2019-02-01 | 5 months ago | A highly optimized double-ended queue. |
| [nan](https://github.com/kak-tus/nan) | 20 | 2 | 2020-05-05 | 2 weeks ago | Zero allocation Nullable structures in one library with handy conversion functions, marshallers and unmarshallers. |
| [go-ef](https://github.com/amallia/go-ef) | 16 | 2 | 2017-09-22 | 2 years ago | A Go implementation of the Elias-Fano encoding. |
| [dict](https://github.com/srfrog/dict) | 15 | 0 | 2019-04-23 | 1 year ago | Python-like dictionaries (dict) for Go. |
| [null](https://github.com/emvi/null) | 14 | 2 | 2018-07-04 | 1 month ago | Nullable Go types that can be marshalled/unmarshalled to/from JSON. |
| [timedmap](https://github.com/zekroTJA/timedmap) | 12 | 2 | 2019-01-30 | 4 weeks ago | Map with expiring key-value pairs. |
| [ptrie](https://github.com/viant/ptrie) | 11 | 7 | 2019-05-20 | 10 months ago | An implementation of prefix tree. |
| [mspm](https://github.com/BlackRabbitt/mspm) | 9 | 3 | 2018-05-17 | 2 years ago | Multi-String Pattern Matching Algorithm for information retrieval. |
| [treap](https://github.com/perdata/treap) | 9 | 2 | 2018-09-16 | 8 months ago | Persistent, fast ordered map using tree heaps. |
| [gofal](https://github.com/xxjwxc/gofal) | 7 | 1 | 2019-08-05 | 10 months ago | fractional api for Go. |
| [set](https://github.com/StudioSol/set) | 7 | 17 | 2018-07-20 | 1 year ago | Simple set data structure implementation in Go using LinkedHashMap. |
| [parsefields](https://github.com/MonaxGT/parsefields) | 4 | 1 | 2019-04-12 | 1 year ago | Tools for parse JSON-like logs for collecting unique fields and events. |
| [cmap](https://github.com/lrita/cmap) | 3 | 1 | 2019-11-26 | 1 week ago | a thread-safe concurrent map for go, support using `interface{}` as key and auto scale up shards. |
| [goterator](https://github.com/yaa110/goterator) | 1 | 1 | 2020-08-12 | 1 week ago | Iterator implementation to provide map and reduce functionalities. |

## Database
        
*SQL query builder, libraries for building and using SQL.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [prometheus](https://github.com/prometheus/prometheus) | 32643 | 1138 | 2012-11-24 | 3 hours ago | Monitoring system and time series database. |
| [tidb](https://github.com/pingcap/tidb) | 24915 | 1346 | 2015-09-06 | 2 hours ago | TiDB is a distributed SQL database. Inspired by the design of Google F1. |
| [influxdb](https://github.com/influxdata/influxdb) | 19454 | 752 | 2013-09-26 | 5 hours ago | Scalable datastore for metrics, events, and real-time analytics. |
| [cockroach](https://github.com/cockroachdb/cockroach) | 18731 | 731 | 2014-02-06 | 51 minutes ago | Scalable, Geo-Replicated, Transactional Datastore. |
| [dgraph](https://github.com/dgraph-io/dgraph) | 13848 | 381 | 2015-08-25 | 56 minutes ago | Scalable, Distributed, Low Latency, High Throughput Graph Database. |
| [vitess](https://github.com/vitessio/vitess) | 10559 | 510 | 2013-06-27 | 58 minutes ago | vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services. |
| [bolt](https://github.com/boltdb/bolt) | 10426 | 343 | 2013-12-20 | 2 years ago | Low-level key/value database for Go. |
| [groupcache](https://github.com/golang/groupcache) | 9089 | 474 | 2013-07-22 | 2 weeks ago | Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases. |
| [badger](https://github.com/dgraph-io/badger) | 8071 | 250 | 2017-01-26 | 1 hour ago | Fast key-value store in Go. |
| [pgweb](https://github.com/sosedoff/pgweb) | 6516 | 151 | 2014-10-09 | 1 month ago | Web-based PostgreSQL database browser. |
| [rqlite](https://github.com/rqlite/rqlite) | 6096 | 205 | 2014-08-23 | 3 weeks ago | The lightweight, distributed, relational database built on SQLite. |
| [kingshard](https://github.com/flike/kingshard) | 5334 | 408 | 2015-07-04 | 2 days ago | kingshard is a high performance proxy for MySQL powered by Golang. |
| [migrate](https://github.com/golang-migrate/migrate) | 4915 | 56 | 2018-01-19 | 4 hours ago | Database migrations. CLI and Golang library. |
| [bigcache](https://github.com/allegro/bigcache) | 4217 | 112 | 2016-03-23 | 1 day ago | Efficient key/value cache for gigabytes of data. |
| [go-cache](https://github.com/patrickmn/go-cache) | 4193 | 108 | 2012-01-02 | 1 week ago | In-memory key:value store/cache (similar to Memcached) library for Go, suitable for single-machine applications. |
| [goleveldb](https://github.com/syndtr/goleveldb) | 3892 | 175 | 2013-01-23 | 1 week ago | Implementation of the [LevelDB](https://github.com/google/leveldb) key/value database in Go. |
| [orchestrator](https://github.com/openark/orchestrator) | 3736 | 277 | 2016-11-30 | 6 hours ago | MySQL replication topology manager & visualizer. |
| [bbolt](https://github.com/etcd-io/bbolt) | 3573 | 110 | 2017-06-17 | 4 days ago | An embedded key/value database for Go. |
| [ledisdb](https://github.com/ledisdb/ledisdb) | 3392 | 183 | 2014-04-30 | 3 months ago | Ledisdb is a high performance NoSQL like Redis based on LevelDB. |
| [orchestrator](https://github.com/github/orchestrator) | 3362 | 299 | 2016-11-30 | 6 months ago | MySQL replication topology manager & visualizer. |
| [ledisdb](https://github.com/siddontang/ledisdb) | 3265 | 188 | 2014-04-30 | 4 months ago | Ledisdb is a high performance NoSQL like Redis based on LevelDB. |
| [squirrel](https://github.com/Masterminds/squirrel) | 3248 | 45 | 2014-01-18 | 4 days ago | Go library that helps you build SQL queries. |
| [go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) | 3093 | 170 | 2015-01-15 | 1 week ago | Sync your MySQL data into Elasticsearch automatically. |
| [buntdb](https://github.com/tidwall/buntdb) | 2895 | 100 | 2016-07-19 | 2 months ago | Fast, embeddable, in-memory key/value database for Go with custom indexing and spatial support. |
| [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) | 2885 | 86 | 2018-09-30 | 4 hours ago | fast, resource-effective and scalable open source time series database. May be used as long-term remote storage for Prometheus. Supports PromQL. |
| [go-mysql](https://github.com/siddontang/go-mysql) | 2602 | 158 | 2014-02-21 | 3 days ago | Go toolset to handle MySQL protocol and replication. |
| [xo](https://github.com/xo/xo) | 2542 | 74 | 2016-02-05 | 2 months ago | Generate idiomatic Go code for databases based on existing schema definitions or custom queries supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server. |
| [tiedot](https://github.com/HouzuoGuo/tiedot) | 2521 | 159 | 2013-05-26 | 5 months ago | Your NoSQL database powered by Golang. |
| [prest](https://github.com/prest/prest) | 2367 | 85 | 2016-11-22 | 6 hours ago | Serve a RESTful API from any PostgreSQL database. |
| [sql-migrate](https://github.com/rubenv/sql-migrate) | 1867 | 34 | 2014-09-09 | 1 month ago | Database migration tool. Allows embedding migrations into the application using go-bindata. |
| [cache2go](https://github.com/muesli/cache2go) | 1344 | 65 | 2013-11-11 | 1 month ago | In-memory key:value cache which supports automatic invalidation based on timeouts. |
| [nutsdb](https://github.com/xujiajun/nutsdb) | 1337 | 44 | 2018-12-07 | 2 days ago | Nutsdb is a simple, fast, embeddable, persistent key/value store written in pure Go. It supports fully serializable transactions and many data structures such as  list, set, sorted set. |
| [gcache](https://github.com/bluele/gcache) | 1227 | 40 | 2015-01-24 | 1 month ago | Cache library with support for expirable Cache, LFU, LRU and ARC. |
| [CovenantSQL](https://github.com/CovenantSQL/CovenantSQL) | 1073 | 67 | 2018-04-11 | 4 months ago | CovenantSQL is a SQL database on blockchain. |
| [gendry](https://github.com/didi/gendry) | 1066 | 61 | 2017-12-01 | 1 week ago | Non-invasive SQL builder and powerful data binder. |
| [diskv](https://github.com/peterbourgon/diskv) | 949 | 36 | 2012-03-21 | 3 months ago | Home-grown disk-backed key-value store. |
| [fastcache](https://github.com/VictoriaMetrics/fastcache) | 871 | 27 | 2018-11-22 | 5 months ago | fast thread-safe inmemory cache for big number of entries. Minimizes GC overhead. |
| [goqu](https://github.com/doug-martin/goqu) | 843 | 31 | 2015-02-21 | 3 days ago | Idiomatic SQL builder and query library. |
| [moss](https://github.com/couchbase/moss) | 765 | 77 | 2016-02-06 | 4 months ago | Moss is a simple LSM key-value storage engine written in 100% Go. |
| [skeema](https://github.com/skeema/skeema) | 739 | 29 | 2016-10-31 | 1 week ago | Pure-SQL schema management system for MySQL, with support for sharding and external online schema change tools. |
| [pogreb](https://github.com/akrylysov/pogreb) | 597 | 23 | 2018-01-06 | 4 months ago | Embedded key-value store for read-heavy workloads. |
| [eliasdb](https://github.com/krotik/eliasdb) | 588 | 26 | 2016-08-13 | 1 month ago | Dependency-free, transactional graph database with REST API, phrase search and SQL-like query language. |
| [dotsql](https://github.com/gchaincl/dotsql) | 546 | 22 | 2014-11-20 | 4 months ago | Go library that helps you keep sql files in one place and use them with ease. |
| [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) | 489 | 25 | 2015-12-10 | 6 months ago | Powerful data retrieval methods as well as DB-agnostic query building capabilities. |
| [gormigrate](https://github.com/go-gormigrate/gormigrate) | 488 | 6 | 2016-08-31 | 1 month ago | Database schema migration helper for Gorm ORM. |
| [bitcask](https://github.com/prologic/bitcask) | 454 | 13 | 2019-03-12 | 20 hours ago | Bitcask is an embeddable, persistent and fast key-value (KV) database written in pure Go with predictable read/write performance, low latency and high throughput thanks to the bitcask on-disk layout (LSM+WAL). |
| [chproxy](https://github.com/Vertamedia/chproxy) | 451 | 25 | 2017-09-18 | 1 week ago | HTTP proxy for ClickHouse database. |
| [levigo](https://github.com/jmhodges/levigo) | 389 | 24 | 2012-01-17 | 2 months ago | Levigo is a Go wrapper for LevelDB. |
| [jet](https://github.com/go-jet/jet) | 302 | 11 | 2019-03-02 | 1 day ago | Framework for writing type-safe SQL queries in Go, with ability to easily convert database query result into desired arbitrary object structure. |
| [pudge](https://github.com/recoilme/pudge) | 272 | 11 | 2018-11-20 | 4 months ago | Fast and simple  key/value store written using Go's standard library. |
| [dbq](https://github.com/rocketlaunchr/dbq) | 223 | 7 | 2019-07-11 | 2 weeks ago | Zero boilerplate database operations for Go. |
| [clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) | 219 | 7 | 2017-04-29 | 2 weeks ago | Collects small insterts and sends big requests to ClickHouse servers. |
| [sqrl](https://github.com/elgris/sqrl) | 213 | 8 | 2014-06-25 | 8 months ago | SQL query builder, fork of Squirrel with improved performance. |
| [vasto](https://github.com/chrislusf/vasto) | 188 | 20 | 2018-01-16 | 1 year ago | A distributed high-performance key-value store. On Disk. Eventual consistent. HA. Able to grow or shrink without service interruption. |
| [kivik](https://github.com/go-kivik/kivik) | 185 | 7 | 2017-02-09 | 1 week ago | Kivik provides a common Go and GopherJS client library for CouchDB, PouchDB, and similar databases. |
| [piladb](https://github.com/fern4lvarez/piladb) | 178 | 11 | 2015-09-08 | 2 years ago | Lightweight RESTful database engine based on stack data structures. |
| [myreplication](https://github.com/2tvenom/myreplication) | 163 | 19 | 2015-02-04 | 1 year ago | MySql binary log replication listener. Supports statement and row based replication. |
| [goose](https://github.com/steinbacher/goose) | 144 | 4 | 2016-03-04 | 3 years ago | Database migration tool. You can manage your database's evolution by creating incremental SQL or Go scripts. |
| [golang-scribble](https://github.com/nanobox-io/golang-scribble) | 108 | 3 | 2018-06-21 | 1 year ago | Tiny flat file JSON store. |
| [darwin](https://github.com/GuiaBolso/darwin) | 106 | 3 | 2016-04-05 | 8 months ago | Database schema evolution library for Go. |
| [migrator](https://github.com/lopezator/migrator) | 104 | 4 | 2019-02-04 | 4 months ago | Dead simple Go database migration library. |
| [slowpoke](https://github.com/recoilme/slowpoke) | 97 | 8 | 2018-02-19 | 11 months ago | Key-value store with persistence. |
| [octillery](https://github.com/knocknote/octillery) | 91 | 16 | 2018-11-26 | 1 month ago | Go package for sharding databases ( Supports every ORM or raw SQL ). |
| [sqlingo](https://github.com/lqs/sqlingo) | 83 | 11 | 2018-11-18 | 2 hours ago | A lightweight DSL to build SQL in Go. |
| [igor](https://github.com/galeone/igor) | 82 | 7 | 2016-03-10 | 2 months ago | Abstraction layer for PostgreSQL that supports advanced functionality and uses gorm-like syntax. |
| [databunker](https://github.com/paranoidguy/databunker) | 67 | 8 | 2019-12-08 | 23 hours ago | Personally identifiable information (PII) storage service built to comply with GDPR and CCPA. |
| [cache](https://github.com/akyoto/cache) | 66 | 2 | 2019-05-11 | 6 months ago | In-memory key:value store with expiration time, 0 dependencies, <100 LoC, 100% coverage. |
| [go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations) | 60 | 1 | 2018-08-11 | 2 months ago | A Go package to help write migrations with go-pg/pg. |
| [bcache](https://github.com/iwanbk/bcache) | 56 | 2 | 2018-12-26 | 1 year ago | Eventually consistent distributed in-memory  cache Go library. |
| [godbal](https://github.com/xujiajun/godbal) | 51 | 4 | 2018-02-28 | 1 year ago | Database Abstraction Layer (dbal) for go. Support SQL builder and get result easily. |
| [couchcache](https://github.com/codingsince1985/couchcache) | 47 | 3 | 2015-04-05 | 1 week ago | RESTful caching micro-service backed by Couchbase server. |
| [dbbench](https://github.com/sj14/dbbench) | 45 | 3 | 2018-11-24 | 2 months ago | Database benchmarking tool with support for several databases and scripts. |
| [unitdb](https://github.com/unit-io/unitdb) | 36 | 1 | 2019-08-29 | 5 days ago | Fast timeseries database for IoT, realtime messaging  applications. Access unitdb with pubsub over tcp or websocket using github.com/unit-io/unitd application. |
| [clusteredBigCache](https://github.com/oaStuff/clusteredBigCache) | 35 | 6 | 2017-12-18 | 2 years ago | BigCache with clustering support and individual item expiration. |
| [gondolier](https://github.com/emvi/gondolier) | 33 | 4 | 2017-10-18 | 1 year ago | Database migration library using struct decorators. |
| [prep](https://github.com/hexdigest/prep) | 27 | 2 | 2017-12-11 | 2 years ago | Use prepared SQL statements without changing your code. |
| [pravasan](https://github.com/pravasan/pravasan) | 24 | 6 | 2015-01-03 | 1 year ago | Simple Migration tool - currently for MySQL but planning to soon support Postgres, SQLite, MongoDB, etc. |
| [go-fixtures](https://github.com/RichardKnop/go-fixtures) | 23 | 1 | 2015-12-24 | 8 months ago | Django style fixtures for Golang's excellent built-in database/sql library. |
| [datagen](https://github.com/codingconcepts/datagen) | 23 | 1 | 2019-04-18 | 2 months ago | A fast data generator that's multi-table aware and supports multi-row DML. |
| [coffer](https://github.com/claygod/coffer) | 20 | 3 | 2019-05-13 | 6 months ago | Simple ACID key-value database that supports transactions. |
| [buildsqlx](https://github.com/arthurkushman/buildsqlx) | 17 | 1 | 2019-08-18 | 3 months ago | Go database query builder library for PostgreSQL. |
| [tempdb](https://github.com/rafaeljesus/tempdb) | 14 | 3 | 2017-03-17 | 2 years ago | Key-value store for temporary items. |
| [avro](https://github.com/khezen/avro) | 14 | 1 | 2019-04-07 | 1 month ago | Discover SQL schemas and convert them to AVRO schemas. Query SQL records into AVRO bytes. |
| [gorocksdb](https://github.com/kapitan-k/gorocksdb) | 12 | 1 | 2017-12-28 | 2 years ago | Gorocksdb is a wrapper for [RocksDB](https://rocksdb.org) written in Go. |
| [sqlf](https://github.com/leporo/sqlf) | 12 | 3 | 2019-07-20 | 7 months ago | Fast SQL query builder. |
| [rwdb](https://github.com/andizzle/rwdb) | 11 | 2 | 2017-10-04 | 2 years ago | rwdb provides read replica capability for multiple database servers setup. |
| [qry](https://github.com/HnH/qry) | 11 | 1 | 2019-08-20 | 7 hours ago | Tool that generates constants from files with raw SQL queries. |
| [bucket](https://github.com/PumpkinSeed/bucket) | 6 | 3 | 2019-09-22 | 3 months ago | Optimized data structure framework for Couchbase specialized on one bucket usage. |
| [gosql](https://github.com/twharmon/gosql) | 6 | 1 | 2020-01-08 | 5 days ago | SQL Query builder with better null values support. |
| [schema](https://github.com/adlio/schema) | 5 | 2 | 2019-09-24 | 3 months ago | Library to embed schema migrations for database/sql-compatible databases inside your Go binaries. |
| [gostore](https://github.com/twharmon/gostore) | 5 | 2 | 2020-01-08 | 6 months ago | Gostore is a simple, durable, embedded key-value storage engine written in Go. |
| [mpath-go](https://github.com/spacetab-io/mpath-go) | 5 | 3 | 2020-01-09 | 7 months ago | MPTT (Modified Preorder Tree Traversal) package for SQL records - materialized path realisation. |
| [tracedb](https://github.com/unit-io/tracedb) | 3 | 1 | 2019-08-29 | 4 months ago | Fast timeseries database for IoT, realtime messaging  applications. Access tracedb with pubsub over tcp or websocket using github.com/unit-io/trace application. |
| [ormlite](https://github.com/pupizoid/ormlite) | 0 | 2 | 2018-06-28 | 3 months ago | Lightweight package containing some ORM-like features and helpers for sqlite databases. |

## Database Drivers
        
*Libraries for connecting and operating databases.*

### Relational Databases
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [mysql](https://github.com/go-sql-driver/mysql) | 9873 | 416 | 2012-12-09 | 1 day ago | MySQL driver for Go. |
| [pq](https://github.com/lib/pq) | 6080 | 158 | 2012-03-12 | 3 days ago | Pure Go Postgres driver for database/sql. |
| [go-sqlite3](https://github.com/mattn/go-sqlite3) | 4270 | 145 | 2011-11-11 | 4 hours ago | SQLite3 driver for go that uses database/sql. |
| [pgx](https://github.com/jackc/pgx) | 3105 | 75 | 2013-03-30 | 19 hours ago | PostgreSQL driver supporting features beyond those exposed by database/sql. |
| [go-mssqldb](https://github.com/denisenkom/go-mssqldb) | 1250 | 70 | 2013-12-16 | 20 hours ago | Microsoft MSSQL driver for Go. |
| [go-oci8](https://github.com/mattn/go-oci8) | 486 | 41 | 2012-02-29 | 15 hours ago | Oracle driver for go that uses database/sql. |
| [goracle](https://github.com/go-goracle/goracle) | 283 | 29 | 2015-03-25 | 8 months ago | Oracle driver for Go, using the ODPI-C driver. |
| [firebirdsql](https://github.com/nakagami/firebirdsql) | 130 | 18 | 2013-08-27 | 1 month ago | Firebird RDBMS SQL driver for Go. |
| [go-adodb](https://github.com/mattn/go-adodb) | 112 | 14 | 2011-11-14 | 6 months ago | Microsoft ActiveX Object DataBase driver for go that uses database/sql. |
| [gofreetds](https://github.com/minus5/gofreetds) | 100 | 22 | 2012-12-06 | 6 days ago | Microsoft MSSQL driver. Go wrapper over [FreeTDS](http://www.freetds.org). |
| [calcite-avatica-go](https://github.com/apache/calcite-avatica-go) | 54 | 23 | 2017-08-08 | 2 weeks ago | Apache Avatica/Phoenix SQL driver for database/sql. |
| [bgc](https://github.com/viant/bgc) | 14 | 10 | 2016-06-13 | 6 months ago | Datastore Connectivity for BigQuery for go. |
| [sqinn-go](https://github.com/cvilsmeier/sqinn-go) | 13 | 1 | 2020-06-06 | 2 months ago | SQLite with pure Go. |

### NoSQL Databases
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [cayley](https://github.com/cayleygraph/cayley) | 13541 | 611 | 2014-06-05 | 1 month ago | Graph database with support for multiple backends. |
| [redis](https://github.com/go-redis/redis) | 9566 | 244 | 2012-07-25 | 10 hours ago | Redis client for Golang. |
| [redigo](https://github.com/gomodule/redigo) | 7746 | 300 | 2012-04-14 | 2 months ago | Redigo is a Go client for the Redis database. |
| [bleve](https://github.com/blevesearch/bleve) | 6858 | 256 | 2014-04-17 | 18 hours ago | Modern text indexing library for go. |
| [riot](https://github.com/go-ego/riot) | 5414 | 192 | 2017-06-21 | 2 months ago | Go Open Source, Distributed, Simple and efficient Search Engine. |
| [elastic](https://github.com/olivere/elastic) | 5282 | 170 | 2012-12-06 | 2 days ago | Elasticsearch client for Go. |
| [mongo-go-driver](https://github.com/mongodb/mongo-go-driver) | 4798 | 145 | 2017-02-08 | 2 hours ago | Official MongoDB driver for the Go language. |
| [go-elasticsearch](https://github.com/elastic/go-elasticsearch) | 2743 | 286 | 2017-03-27 | 2 hours ago | Official Elasticsearch client for Go. |
| [mgo](https://github.com/globalsign/mgo) | 1819 | 65 | 2017-04-13 | 3 months ago | (unmaintained) MongoDB driver for the Go language that implements a rich and well tested selection of features under a very simple API following standard Go idioms. |
| [rethinkdb-go](https://github.com/rethinkdb/rethinkdb-go) | 1538 | 49 | 2013-09-12 | 3 months ago | Go language driver for RethinkDB. |
| [elastigo](https://github.com/mattbaird/elastigo) | 950 | 48 | 2012-10-12 | 1 year ago | Elasticsearch client library. |
| [elasticsql](https://github.com/cch123/elasticsql) | 581 | 33 | 2016-08-24 | 2 months ago | Convert sql to elasticsearch dsl in Go. |
| [redeo](https://github.com/bsm/redeo) | 380 | 25 | 2014-03-06 | 1 year ago | Redis-protocol compatible TCP servers/services. |
| [neoism](https://github.com/jmcvetta/neoism) | 371 | 25 | 2012-07-12 | 6 months ago | Neo4j client for Golang. |
| [aerospike-client-go](https://github.com/aerospike/aerospike-client-go) | 339 | 39 | 2014-07-26 | 1 day ago | Aerospike client in Go language. |
| [gocb](https://github.com/couchbase/gocb) | 320 | 65 | 2015-01-15 | 6 days ago | Official Couchbase Go SDK. |
| [go-couchbase](https://github.com/couchbase/go-couchbase) | 305 | 26 | 2012-01-19 | 2 weeks ago | Couchbase client in Go. |
| [gokv](https://github.com/philippgille/gokv) | 249 | 5 | 2018-10-08 | 5 months ago | Simple key-value store abstraction and implementations for Go (Redis, Consul, etcd, bbolt, BadgerDB, LevelDB, Memcached, DynamoDB, S3, PostgreSQL, MongoDB, CockroachDB and many more). |
| [qmgo](https://github.com/qiniu/qmgo) | 210 | 8 | 2020-08-04 | 1 day ago | The MongoDB dirver for Go. It‘s based on official MongoDB driver but easier to use like Mgo. |
| [mgm](https://github.com/Kamva/mgm) | 187 | 13 | 2019-12-27 | 3 weeks ago | MongoDB model-based ODM for Go (based on official MongoDB driver). |
| [go-rejson](https://github.com/nitishm/go-rejson) | 142 | 7 | 2018-04-23 | 1 month ago | Golang client for redislabs' ReJSON module using Redigo golang client. Store and manipulate structs as JSON objects in redis with ease. |
| [cachego](https://github.com/faabiosr/cachego) | 136 | 6 | 2016-10-05 | 2 months ago | Golang Cache component for multiple drivers. |
| [godis](https://github.com/piaohao/godis) | 83 | 9 | 2019-06-14 | 3 months ago | redis client implement by golang, inspired by jedis. |
| [Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) | 76 | 7 | 2011-06-04 | 2 years ago | Neo4j REST Client in golang. |
| [skizze](https://github.com/seiflotfy/skizze) | 74 | 7 | 2016-01-17 | 4 years ago | probabilistic data-structures service and storage. |
| [dynago](https://github.com/underarmour/dynago) | 70 | 123 | 2015-05-18 | 3 years ago | Dynago is a principle of least surprise client for DynamoDB. |
| [arangolite](https://github.com/solher/arangolite) | 68 | 6 | 2015-10-04 | 1 year ago | Lightweight golang driver for ArangoDB. |
| [go-pilosa](https://github.com/pilosa/go-pilosa) | 41 | 19 | 2016-09-30 | 5 months ago | Go client library for Pilosa. |
| [goforestdb](https://github.com/couchbase/goforestdb) | 29 | 42 | 2014-05-14 | 3 years ago | Go bindings for ForestDB. |
| [goriak](https://github.com/zegl/goriak) | 26 | 3 | 2016-10-05 | 1 year ago | Go language driver for Riak KV. |
| [neo4j](https://github.com/cihangir/neo4j) | 26 | 4 | 2013-05-18 | 5 years ago | Neo4j Rest API Bindings for Golang. |
| [goes](https://github.com/OwnLocal/goes) | 24 | 33 | 2015-12-28 | 3 years ago | Library to interact with Elasticsearch. |
| [dsc](https://github.com/viant/dsc) | 20 | 15 | 2016-06-13 | 5 months ago | Datastore connectivity for SQL, NoSQL, structured files. |
| [xredis](https://github.com/shomali11/xredis) | 12 | 2 | 2017-06-14 | 1 year ago | Typesafe, customizable, clean & easy to use Redis client. |
| [godscache](https://github.com/defcronyke/godscache) | 8 | 3 | 2018-05-08 | 1 year ago | A wrapper for the Google Cloud Platform Go Datastore package that adds caching using memcached. |
| [asc](https://github.com/viant/asc) | 6 | 10 | 2016-06-13 | 1 year ago | Datastore Connectivity for Aerospike for go. |

## Date and Time
        
*Libraries for working with dates and times.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [now](https://github.com/jinzhu/now) | 2649 | 55 | 2013-11-18 | 10 months ago | Now is a time toolkit for golang. |
| [dateparse](https://github.com/araddon/dateparse) | 1113 | 18 | 2014-04-21 | 2 months ago | Parse date's without knowing format in advance. |
| [carbon](https://github.com/uniplaces/carbon) | 480 | 42 | 2016-08-03 | 1 year ago | Simple Time extension with a lot of util methods, ported from PHP Carbon library. |
| [durafmt](https://github.com/hako/durafmt) | 311 | 5 | 2016-05-20 | 1 month ago | Time duration formatting library for Go. |
| [timeutil](https://github.com/leekchan/timeutil) | 181 | 8 | 2015-08-02 | 1 year ago | Useful extensions (Timedelta, Strftime, ...) to the golang's time package. |
| [go-persian-calendar](https://github.com/yaa110/go-persian-calendar) | 81 | 4 | 2016-01-31 | 9 months ago | The implementation of the Persian (Solar Hijri) Calendar in Go (golang). |
| [iso8601](https://github.com/relvacode/iso8601) | 79 | 4 | 2017-04-25 | 2 months ago | Efficiently parse ISO8601 date-times without regex. |
| [timespan](https://github.com/SaidinWoT/timespan) | 73 | 6 | 2014-10-07 | 1 year ago | For interacting with intervals of time, defined as a start time and a duration. |
| [date](https://github.com/rickb777/date) | 46 | 3 | 2015-11-23 | 8 hours ago | Augments Time for working with dates, date ranges, time spans, periods, and time-of-day. |
| [feiertage](https://github.com/wlbr/feiertage) | 34 | 2 | 2015-11-04 | 3 months ago | Set of functions to calculate public holidays in Germany, incl. specialization on the states of Germany (Bundesländer). Things like Easter, Pentecost, Thanksgiving... |
| [go-sunrise](https://github.com/nathan-osman/go-sunrise) | 27 | 4 | 2017-06-15 | 2 years ago | Calculate the sunrise and sunset times for a given location. |
| [kair](https://github.com/GuilhermeCaruso/kair) | 17 | 1 | 2018-10-03 | 2 months ago | Date and Time - Golang Formatting Library. |
| [nulltime](https://github.com/kirillDanshin/nulltime) | 11 | 2 | 2016-03-06 | 3 years ago | Nullable `time.Time`. |
| [go-str2duration](https://github.com/xhit/go-str2duration) | 10 | 2 | 2020-02-02 | 3 weeks ago | Convert string to duration. Support time.Duration returned string and more. |
| [tuesday](https://github.com/osteele/tuesday) | 9 | 3 | 2017-08-10 | 3 years ago | Ruby-compatible Strftime function. |
| [strftime](https://github.com/awoodbeck/strftime) | 6 | 2 | 2018-02-10 | 2 years ago | C99-compatible strftime formatter. |
| [cronrange](https://github.com/1set/cronrange) | 4 | 1 | 2019-11-10 | 9 months ago | Parses Cron-style time range expressions, checks if the given time is within any ranges. |
| [go-week](https://github.com/stoewer/go-week) | 4 | 4 | 2018-02-23 | 2 months ago | An efficient package to work with ISO8601 week dates. |

## Distributed Systems
        
*Packages that help with building Distributed Systems.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [kit](https://github.com/go-kit/kit) | 17884 | 679 | 2015-02-03 | 2 days ago | Microservice toolkit with support for service discovery, load balancing, pluggable transports, request tracking, etc. |
| [go-micro](https://github.com/micro/go-micro) | 14084 | 485 | 2015-01-13 | 1 hour ago | A distributed systems development framework. |
| [grpc-go](https://github.com/grpc/grpc-go) | 12094 | 494 | 2014-12-08 | 10 hours ago | The Go language implementation of gRPC. HTTP/2 based RPC. |
| [micro](https://github.com/micro/micro) | 8374 | 318 | 2015-01-16 | 1 day ago | A distributed systems runtime for the cloud and beyond. |
| [nats-server](https://github.com/nats-io/nats-server) | 8169 | 380 | 2012-10-29 | 2 hours ago | Lightweight, high performance messaging system for microservices, IoT, and cloud native systems. |
| [rpcx](https://github.com/smallnest/rpcx) | 4949 | 333 | 2016-05-18 | 6 hours ago | Distributed pluggable RPC service framework like alibaba Dubbo. |
| [raft](https://github.com/hashicorp/raft) | 3822 | 299 | 2013-11-05 | 3 days ago | Golang implementation of the Raft consensus protocol, by HashiCorp. |
| [tendermint](https://github.com/tendermint/tendermint) | 3736 | 261 | 2014-05-14 | 46 minutes ago | High-performance middleware for transforming a state machine written in any programming language into a Byzantine Fault Tolerant replicated state machine using the Tendermint consensus and blockchain protocols. |
| [torrent](https://github.com/anacrolix/torrent) | 3589 | 136 | 2015-01-08 | 3 weeks ago | BitTorrent client package. |
| [dragonboat](https://github.com/lni/dragonboat) | 3217 | 140 | 2018-12-23 | 3 days ago | A feature complete and high performance multi-group Raft library in Go. |
| [krakend](https://github.com/devopsfaith/krakend) | 3032 | 93 | 2016-11-04 | 6 days ago | Ultra performant API Gateway framework with middlewares. |
| [glow](https://github.com/chrislusf/glow) | 2840 | 148 | 2015-06-14 | 1 year ago | Easy-to-Use scalable distributed big data processing, Map-Reduce, DAG execution, all in pure Go. |
| [gleam](https://github.com/chrislusf/gleam) | 2589 | 152 | 2016-08-26 | 4 months ago | Fast and scalable distributed map/reduce system written in pure Go and Luajit, combining Go's high concurrency with Luajit's high performance, runs standalone or distributed. |
| [emitter](https://github.com/emitter-io/emitter) | 2505 | 98 | 2016-10-29 | 2 months ago | High performance, distributed, secure and low latency publish-subscribe platform built with MQTT, Websockets and love. |
| [liftbridge](https://github.com/liftbridge-io/liftbridge) | 1863 | 75 | 2017-10-13 | 48 minutes ago | Lightweight, fault-tolerant message streams for NATS. |
| [hprose-golang](https://github.com/hprose/hprose-golang) | 1112 | 94 | 2014-02-14 | 2 months ago | Very newbility RPC Library, support 25+ languages now. |
| [ringpop-go](https://github.com/uber/ringpop-go) | 622 | 2397 | 2015-06-05 | 1 year ago | Scalable, fault-tolerant application-layer sharding for Go applications. |
| [gorpc](https://github.com/valyala/gorpc) | 610 | 27 | 2014-11-20 | 11 months ago | Simple, fast and scalable RPC library for high load. |
| [go-health](https://github.com/InVisionApp/go-health) | 565 | 103 | 2017-11-29 | 7 months ago | Library for enabling asynchronous dependency health checks in your service. |
| [rain](https://github.com/cenkalti/rain) | 514 | 14 | 2014-05-21 | 1 month ago | BitTorrent client and library. |
| [digota](https://github.com/digota/digota) | 344 | 25 | 2017-08-14 | 1 year ago | grpc ecommerce microservice. |
| [go-sundheit](https://github.com/AppsFlyer/go-sundheit) | 323 | 7 | 2019-04-08 | 3 months ago | A library built to provide support for defining async service health checks for golang services. |
| [sleuth](https://github.com/ursiform/sleuth) | 323 | 9 | 2016-04-23 | 2 years ago | Library for master-less p2p auto-discovery and RPC between HTTP services (using [ZeroMQ](https://github.com/zeromq/libzmq)). |
| [consistent](https://github.com/buraksezer/consistent) | 309 | 10 | 2018-03-25 | 11 months ago | Consistent hashing with bounded loads. |
| [go-jump](https://github.com/dgryski/go-jump) | 301 | 13 | 2014-06-15 | 2 years ago | Port of Google's "Jump" Consistent Hash function. |
| [redislock](https://github.com/bsm/redislock) | 215 | 4 | 2019-06-24 | 1 month ago | Simplified distributed locking implementation using Redis. |
| [dht](https://github.com/anacrolix/dht) | 167 | 12 | 2016-12-14 | 3 months ago | BitTorrent Kademlia DHT implementation. |
| [jsonrpc](https://github.com/ybbus/jsonrpc) | 138 | 9 | 2016-11-10 | 6 months ago | JSON-RPC 2.0 HTTP client implementation. |
| [jsonrpc](https://github.com/osamingo/jsonrpc) | 132 | 6 | 2016-10-28 | 1 week ago | The jsonrpc package helps implement of JSON-RPC 2.0. |
| [celeriac.v1](https://github.com/svcavallar/celeriac.v1) | 61 | 3 | 2015-10-10 | 1 month ago | Library for adding support for interacting and monitoring Celery workers, tasks and events in Go. |
| [doublejump](https://github.com/edwingeng/doublejump) | 55 | 3 | 2018-06-26 | 5 months ago | A revamped Google's jump consistent hash. |
| [semaphore](https://github.com/jexia/semaphore) | 36 | 14 | 2020-02-05 | 2 hours ago | A straightforward (micro) service orchestrator. |
| [outboxer](https://github.com/italolelis/outboxer) | 35 | 0 | 2019-02-01 | 12 hours ago | Outboxer is a go library that implements the outbox pattern. |
| [maestro](https://github.com/jexia/maestro) | 34 | 16 | 2020-02-05 | 1 month ago | A straightforward (micro) service orchestrator. |
| [flowgraph](https://github.com/vectaport/flowgraph) | 33 | 1 | 2018-08-29 | 2 months ago | flow-based programming package. |
| [drmaa](https://github.com/dgruber/drmaa) | 29 | 2 | 2013-03-17 | 3 months ago | Job submission library for cluster schedulers based on the DRMAA standard. |
| [go-pdu](https://github.com/pdupub/go-pdu) | 22 | 2 | 2018-10-08 | 2 months ago | A decentralized identity-based social network. |
| [dynatomic](https://github.com/tylfin/dynatomic) | 12 | 0 | 2019-02-08 | 1 year ago | A library for using DynamoDB as an atomic counter. |
| [go-mysql-lock](https://github.com/sanketplus/go-mysql-lock) | 8 | 1 | 2020-06-06 | 2 months ago | MySQL based distributed lock. |
| [micro](https://github.com/gmsec/micro) | 6 | 1 | 2020-05-03 | 2 months ago | A Go distributed systems development framework. |
| [consistenthash](https://github.com/mbrostami/consistenthash) | 5 | 1 | 2020-04-22 | 4 months ago | Consistent hashing with configurable replicas. |

## Dynamic DNS
        
*Tools for updating dynamic DNS records.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [godns](https://github.com/TimothyYe/godns) | 655 | 21 | 2014-05-11 | 3 weeks ago | A dynamic DNS client tool, supports DNSPod & HE.net, written in Go. |
| [ddns](https://github.com/skibish/ddns) | 155 | 6 | 2017-03-13 | 2 weeks ago | Personal DDNS client with Digital Ocean Networking DNS as backend. |

## Email
        
*Libraries and tools that implement email creation and sending.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [MailHog](https://github.com/mailhog/MailHog) | 6865 | 128 | 2014-04-16 | 1 day ago | Email and SMTP testing with web and API interface. |
| [hermes](https://github.com/matcornic/hermes) | 2051 | 30 | 2017-03-25 | 5 hours ago | Golang package that generates clean, responsive HTML e-mails. |
| [email](https://github.com/jordan-wright/email) | 1483 | 46 | 2013-12-12 | 1 week ago | A robust and flexible email library for Go. |
| [go-imap](https://github.com/emersion/go-imap) | 1056 | 34 | 2016-04-26 | 5 days ago | IMAP library for clients and servers. |
| [sendgrid-go](https://github.com/sendgrid/sendgrid-go) | 636 | 186 | 2013-09-12 | 3 days ago | SendGrid's Go library for sending email. |
| [mailgun-go](https://github.com/mailgun/mailgun-go) | 470 | 58 | 2014-02-28 | 1 week ago | Go library for sending mail with the Mailgun API. |
| [hectane](https://github.com/hectane/hectane) | 186 | 13 | 2015-08-28 | 1 year ago | Lightweight SMTP client providing an HTTP API. |
| [douceur](https://github.com/aymerick/douceur) | 184 | 3 | 2015-04-09 | 2 years ago | CSS inliner for your HTML emails. |
| [go-message](https://github.com/emersion/go-message) | 166 | 11 | 2016-12-31 | 1 week ago | Streaming library for the Internet Message Format and mail messages. |
| [go-dkim](https://github.com/toorop/go-dkim) | 61 | 2 | 2015-04-29 | 3 months ago | DKIM library, to sign & verify email. |
| [go-premailer](https://github.com/vanng822/go-premailer) | 58 | 2 | 2015-02-16 | 2 weeks ago | Inline styling for HTML mail in Go. |
| [smtp](https://github.com/mailhog/smtp) | 57 | 10 | 2014-12-24 | 3 weeks ago | SMTP server protocol state machine. |
| [mailchain](https://github.com/mailchain/mailchain) | 54 | 7 | 2019-04-11 | 5 days ago | Send encrypted emails to blockchain addresses written in Go. |
| [go-simple-mail](https://github.com/xhit/go-simple-mail) | 47 | 1 | 2019-09-15 | 1 week ago | Very simple package to send emails with SMTP Keep Alive and two timeouts: Connect and Send. |

## Embeddable Scripting Languages
        
*Embedding other languages inside your go code.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [otto](https://github.com/robertkrimen/otto) | 5491 | 183 | 2012-10-06 | 3 days ago | JavaScript interpreter written in Go. |
| [gopher-lua](https://github.com/yuin/gopher-lua) | 3699 | 148 | 2015-02-15 | 2 weeks ago | Lua 5.1 VM and compiler written in Go. |
| [tengo](https://github.com/d5/tengo) | 1989 | 44 | 2019-01-09 | 1 month ago | Bytecode compiled script language for Go. |
| [go-lua](https://github.com/Shopify/go-lua) | 1904 | 275 | 2013-12-20 | 1 month ago | Port of the Lua 5.2 VM to pure Go. |
| [expr](https://github.com/antonmedv/expr) | 1418 | 38 | 2018-07-14 | 3 months ago | Expression evaluation engine for Go: fast, non-Turing complete, dynamic typing, static typing. |
| [go-python](https://github.com/sbinet/go-python) | 1125 | 45 | 2012-07-09 | 5 months ago | naive go bindings to the CPython C-API. |
| [anko](https://github.com/mattn/anko) | 1046 | 47 | 2014-03-28 | 3 months ago | Scriptable interpreter written in Go. |
| [go-php](https://github.com/deuill/go-php) | 760 | 44 | 2015-09-17 | 1 year ago | PHP bindings for Go. |
| [go-duktape](https://github.com/olebedev/go-duktape) | 727 | 29 | 2015-01-08 | 2 months ago | Duktape JavaScript engine bindings for Go. |
| [cel-go](https://github.com/google/cel-go) | 543 | 28 | 2018-03-09 | 6 days ago | Fast, portable, non-Turing complete expression evaluation with gradual typing. |
| [golua](https://github.com/aarzilli/golua) | 484 | 32 | 2010-12-06 | 6 days ago | Go bindings for Lua C API. |
| [gisp](https://github.com/jcla1/gisp) | 440 | 21 | 2014-01-11 | 3 years ago | Simple LISP in Go. |
| [gval](https://github.com/PaesslerAG/gval) | 231 | 16 | 2017-09-27 | 1 year ago | A highly customizable expression language written in Go. |
| [gentee](https://github.com/gentee/gentee) | 53 | 3 | 2018-01-14 | 1 week ago | Embeddable scripting programming language. |
| [binder](https://github.com/alexeyco/binder) | 40 | 2 | 2017-04-02 | 2 years ago | Go to Lua binding library, based on [gopher-lua](https://github.com/yuin/gopher-lua). |
| [purl](https://github.com/ian-kent/purl) | 29 | 2 | 2014-11-29 | 5 years ago | Perl 5.18.2 embedded in Go. |
| [ngaro](https://github.com/db47h/ngaro) | 20 | 1 | 2016-08-09 | 2 years ago | Embeddable Ngaro VM implementation enabling scripting in Retro. |

## Error Handling
        
*Libraries for handling errors.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [errors](https://github.com/pkg/errors) | 6052 | 109 | 2015-12-27 | 2 months ago | Package that provides simple error handling primitives. |
| [go-multierror](https://github.com/hashicorp/go-multierror) | 916 | 199 | 2014-12-15 | 2 months ago | Go (golang) package for representing a list of errors as a single error. |
| [eris](https://github.com/rotisserie/eris) | 667 | 9 | 2019-09-07 | 1 month ago | A better way to handle, trace, and log errors in Go. Compatible with the standard error library and github.com/pkg/errors. |
| [errorx](https://github.com/joomcode/errorx) | 636 | 61 | 2018-08-17 | 1 week ago | A feature rich error package with stack traces, composition of errors and more. |
| [tracerr](https://github.com/ztrue/tracerr) | 626 | 8 | 2019-02-06 | 1 year ago | Golang errors with stack trace and source fragments. |
| [errlog](https://github.com/snwfdhmp/errlog) | 344 | 6 | 2019-02-16 | 6 months ago | Hackable package that determines responsible source code for an error (and some other fast-debugging features). Pluggable to any logger in-place. |
| [emperror](https://github.com/emperror/emperror) | 147 | 2 | 2017-06-13 | 4 months ago | Error handling tools and best practices for Go libraries and applications. |
| [errors](https://github.com/emperror/errors) | 61 | 3 | 2019-07-09 | 4 months ago | Drop-in replacement for the standard library errors package and github.com/pkg/errors. Provides various error handling primitives. |
| [werr](https://github.com/txgruppi/werr) | 13 | 0 | 2015-08-04 | 4 years ago | Error Wrapper creates an wrapper for the error type in Go which captures the File, Line and Stack of where it was called. |
| [errors](https://github.com/bnkamalesh/errors) | 8 | 1 | 2020-07-17 | 1 month ago | Drop-in replacement for builting Go errors. This is a minimal error handling package with custom error types, user friendly messages, Unwrap & Is. With very easy to use and straightforward helper functions. |
| [falcon](https://github.com/SonicRoshan/falcon) | 6 | 2 | 2019-09-09 | 10 months ago | A Simple Yet Highly Powerful Package For Error Handling. |
| [errors](https://github.com/neuronlabs/errors) | 3 | 1 | 2019-07-26 | 1 year ago | Simple golang error handling with classification primitives. |
| [errors](https://github.com/PumpkinSeed/errors) | 2 | 1 | 2020-01-08 | 7 months ago | The most simple error wrapper with awesome performance and minimal memory overhead. |

## Files
        
*Libraries for handling files and file systems.*

## Financial
        
*Packages for accounting and finance.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [decimal](https://github.com/shopspring/decimal) | 2385 | 63 | 2015-02-25 | 1 week ago | Arbitrary-precision fixed-point decimal numbers. |
| [go-money](https://github.com/Rhymond/go-money) | 781 | 17 | 2017-03-20 | 1 month ago | Implementation of Fowler's Money pattern. |
| [accounting](https://github.com/leekchan/accounting) | 579 | 14 | 2015-08-10 | 3 weeks ago | money and currency formatting for golang. |
| [go-finance](https://github.com/FlashBoys/go-finance) | 537 | 27 | 2016-02-28 | 2 years ago | Comprehensive financial markets data in Go. |
| [techan](https://github.com/sdcoffey/techan) | 293 | 31 | 2017-03-08 | 8 months ago | Technical analysis library with advanced market analysis and trading strategies. |
| [orderbook](https://github.com/i25959341/orderbook) | 151 | 11 | 2018-04-24 | 1 year ago | Matching Engine for Limit Order Book in Golang. |
| [vat](https://github.com/dannyvankooten/vat) | 77 | 1 | 2016-06-18 | 4 months ago | VAT number validation & EU VAT rates. |
| [ofxgo](https://github.com/aclindsa/ofxgo) | 76 | 10 | 2015-11-08 | 5 months ago | Query OFX servers and/or parse the responses (with example command-line client). |
| [go-finance](https://github.com/alpeb/go-finance) | 75 | 4 | 2017-06-01 | 6 months ago | Library of financial functions for time value of money (annuities), cash flow, interest rate conversions, bonds and depreciation calculations. |
| [transaction](https://github.com/claygod/transaction) | 74 | 8 | 2017-10-11 | 1 month ago | Embedded transactional database of accounts, running in multithreaded mode. |
| [currency](https://github.com/bojanz/currency) | 60 | 1 | 2020-04-16 | 1 week ago | Handles currency amounts, provides currency information and formatting. |
| [go-finnhub](https://github.com/m1/go-finnhub) | 41 | 3 | 2020-01-13 | 7 months ago | Client for stock market, forex and crypto data from finnhub.io. Access real-time financial market data from 60+ stock exchanges, 10 forex brokers, and 15+ crypto exchanges. |
| [currency](https://github.com/bnkamalesh/currency) | 29 | 5 | 2017-05-09 | 2 months ago | High performant & accurate currency computation package. |
| [go-finance](https://github.com/pieterclaerhout/go-finance) | 3 | 1 | 2019-09-30 | 10 months ago | Module to fetch exchange rates, check VAT numbers via VIES and check IBAN bank account numbers. |

## Forms
        
*Libraries for working with forms.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [nosurf](https://github.com/justinas/nosurf) | 1082 | 36 | 2013-08-22 | 2 days ago | CSRF protection middleware for Go. |
| [binding](https://github.com/mholt/binding) | 774 | 32 | 2014-05-20 | 2 years ago | Binds form and JSON data from net/http Request to struct. |
| [csrf](https://github.com/gorilla/csrf) | 567 | 22 | 2015-08-03 | 6 days ago | CSRF protection for Go web applications & services. |
| [form](https://github.com/go-playground/form) | 423 | 11 | 2016-05-26 | 9 months ago | Decodes url.Values into Go value(s) and Encodes Go value(s) into url.Values. Dual Array and Full map support. |
| [conform](https://github.com/leebenson/conform) | 203 | 5 | 2016-01-05 | 2 months ago | Keeps user input in check. Trims, sanitizes & scrubs data based on struct tags. |
| [formam](https://github.com/monoculum/formam) | 150 | 4 | 2014-10-25 | 3 months ago | decode form's values into a struct. |
| [forms](https://github.com/albrow/forms) | 114 | 7 | 2014-08-07 | 3 years ago | Framework-agnostic library for parsing and validating form/JSON data which supports multipart forms and files. |
| [bind](https://github.com/robfig/bind) | 25 | 3 | 2014-08-06 | 6 years ago | Bind form data to any Go values. |
| [queryparam](https://github.com/TomWright/queryparam) | 6 | 2 | 2018-06-14 | 8 months ago | Decode `url.Values` into usable struct values of standard or custom types. |

## Functional
        
*Packages to support functional programming in Go.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-underscore](https://github.com/tobyhede/go-underscore) | 1162 | 29 | 2014-07-02 | 1 year ago | Useful collection of helpfully functional Go collection utilities. |
| [fpGo](https://github.com/TeaEntityLab/fpGo) | 152 | 5 | 2018-05-24 | 2 years ago | Monad, Functional Programming features for Golang. |
| [fuego](https://github.com/seborama/fuego) | 69 | 3 | 2018-11-05 | 1 year ago | Functional Experiment in Go. |

## Game Development
        
*Awesome game development libraries.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [leaf](https://github.com/name5566/leaf) | 3658 | 324 | 2014-08-04 | 3 months ago | Lightweight game server framework. |
| [ebiten](https://github.com/hajimehoshi/ebiten) | 3189 | 100 | 2013-06-16 | 2 hours ago | dead simple 2D game library in Go. |
| [pixel](https://github.com/faiface/pixel) | 3120 | 101 | 2016-11-19 | 1 week ago | Hand-crafted 2D game library in Go. |
| [goworld](https://github.com/xiaonanln/goworld) | 1580 | 123 | 2017-06-03 | 1 month ago | Scalable game server engine, featuring space-entity framework and hot-swapping. |
| [go-sdl2](https://github.com/veandco/go-sdl2) | 1397 | 44 | 2013-06-05 | 2 weeks ago | Go bindings for the [Simple DirectMedia Layer](https://www.libsdl.org/). |
| [nano](https://github.com/lonng/nano) | 1357 | 61 | 2017-08-02 | 8 months ago | Lightweight, facility, high performance golang based game server framework. |
| [engo](https://github.com/EngoEngine/engo) | 1256 | 47 | 2014-11-12 | 2 weeks ago | Engo is an open-source 2D game engine written in Go. It follows the Entity-Component-System paradigm. |
| [termloop](https://github.com/JoelOtter/termloop) | 1158 | 32 | 2015-05-23 | 3 months ago | Terminal-based game engine for Go, built on top of Termbox. |
| [engine](https://github.com/g3n/engine) | 1150 | 68 | 2017-03-07 | 2 weeks ago | Go 3D Game Engine. |
| [gonet](https://github.com/xtaci/gonet) | 1104 | 135 | 2013-04-11 | 3 years ago | Game server skeleton implemented with golang. |
| [oak](https://github.com/oakmound/oak) | 767 | 45 | 2017-07-15 | 3 days ago | Pure Go game engine. |
| [pitaya](https://github.com/topfreegames/pitaya) | 711 | 60 | 2018-03-19 | 3 days ago | Scalable game server framework with clustering support and client libraries for iOS, Android, Unity and others through the C SDK. |
| [raylib-go](https://github.com/gen2brain/raylib-go) | 512 | 24 | 2017-01-27 | 1 hour ago | Go bindings for [raylib](http://www.raylib.com/), a simple and easy-to-use library to learn videogames programming. |
| [engine](https://github.com/azul3d/engine) | 455 | 25 | 2016-02-29 | 10 months ago | 3D game engine written in Go. |
| [go-astar](https://github.com/beefsack/go-astar) | 382 | 10 | 2014-05-28 | 4 days ago | Go implementation of the A\* path finding algorithm. |
| [GarageEngine](https://github.com/vova616/GarageEngine) | 320 | 31 | 2012-08-07 | 1 year ago | 2d game engine written in Go working on OpenGL. |
| [go3d](https://github.com/ungerik/go3d) | 180 | 10 | 2011-06-27 | 6 months ago | Performance oriented 2D/3D math package for Go. |
| [glop](https://github.com/runningwild/glop) | 77 | 3 | 2011-04-20 | 5 years ago | Glop (Game Library Of Power) is a fairly simple cross-platform game library. |
| [prototype](https://github.com/gonutz/prototype) | 30 | 3 | 2015-03-04 | 1 week ago | Cross-platform (Windows/Linux/Mac) library for creating desktop games using a minimal API. |
| [go-collada](https://github.com/GlenKelley/go-collada) | 15 | 3 | 2013-09-19 | 7 years ago | Go package for working with the Collada file format. |

## Generation and Generics
        
*Tools to enhance the language with features like generics via code generation.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-linq](https://github.com/ahmetb/go-linq) | 2178 | 73 | 2013-12-19 | 2 months ago | .NET LINQ-like query methods for Go. |
| [jennifer](https://github.com/dave/jennifer) | 1667 | 25 | 2016-12-04 | 4 days ago | Generate arbitrary Go code without templates. |
| [gen](https://github.com/clipperhouse/gen) | 1128 | 34 | 2013-10-13 | 7 months ago | Code generation tool for ‘generics’-like functionality. |
| [goderive](https://github.com/awalterschulze/goderive) | 819 | 24 | 2017-02-10 | 6 months ago | Derives functions from input types. |
| [gowrap](https://github.com/hexdigest/gowrap) | 390 | 11 | 2018-09-15 | 4 weeks ago | Generate decorators for Go interfaces using simple templates. |
| [interfaces](https://github.com/rjeczalik/interfaces) | 231 | 7 | 2015-12-06 | 1 month ago | Command line tool for generating interface definitions. |
| [go-enum](https://github.com/abice/go-enum) | 117 | 3 | 2017-08-10 | 7 months ago | Code generation for enums from code comments. |
| [pkgreflect](https://github.com/ungerik/pkgreflect) | 93 | 5 | 2012-09-03 | 3 years ago | Go preprocessor for package scoped reflection. |
| [efaceconv](https://github.com/t0pep0/efaceconv) | 46 | 4 | 2016-11-18 | 2 years ago | Code generation tool for high performance conversion from interface{} to immutable type without allocations. |
| [gotype](https://github.com/wzshiming/gotype) | 32 | 4 | 2017-12-05 | 3 months ago | Golang source code parsing, usage like reflect package. |
| [GENERIS](https://github.com/senselogic/GENERIS) | 21 | 1 | 2019-03-10 | 1 month ago | Code generation tool providing generics, free-form macros, conditional compilation and HTML templating. |
| [go-xray](https://github.com/pieterclaerhout/go-xray) | 12 | 2 | 2019-10-01 | 9 months ago | Helpers for making the use of reflection easier. |
| [typeregistry](https://github.com/xiaoxin01/typeregistry) | 5 | 1 | 2020-01-14 | 6 months ago | A library to create type dynamically. |

## Geographic
        
*Geographic tools and servers*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [tile38](https://github.com/tidwall/tile38) | 7017 | 205 | 2016-03-04 | 2 weeks ago | Geolocation DB with spatial index and realtime geofencing. |
| [geo](https://github.com/golang/geo) | 1085 | 76 | 2014-12-03 | 1 month ago | S2 geometry library in Go. |
| [mbtileserver](https://github.com/consbio/mbtileserver) | 171 | 14 | 2014-11-01 | 3 months ago | A simple Go-based server for map tiles stored in mbtiles format. |
| [geocache](https://github.com/melihmucuk/geocache) | 125 | 6 | 2016-06-21 | 4 years ago | In-memory cache that is suitable for geolocation based applications. |
| [osm](https://github.com/paulmach/osm) | 121 | 9 | 2016-02-02 | 2 weeks ago | Library for reading, writing and working with OpenStreetMap data and APIs. |
| [wgs84](https://github.com/wroge/wgs84) | 55 | 1 | 2019-06-08 | 6 months ago | Library for Coordinate Conversion and Transformation (ETRS89, OSGB36, NAD83, RGF93, Web Mercator, UTM). |
| [geoserver](https://github.com/hishamkaram/geoserver) | 39 | 2 | 2018-03-26 | 2 months ago | geoserver Is a Go Package For Manipulating a GeoServer Instance via the GeoServer REST API. |
| [gismanager](https://github.com/hishamkaram/gismanager) | 32 | 1 | 2018-09-29 | 1 year ago | Publish Your GIS Data(Vector Data) to PostGIS and Geoserver. |
| [pbf](https://github.com/maguro/pbf) | 23 | 2 | 2017-09-18 | 2 months ago | OpenStreetMap PBF golang encoder/decoder. |
| [s2-geojson](https://github.com/pantrif/s2-geojson) | 6 | 1 | 2020-03-27 | 4 months ago | Convert geojson to s2 cells & demonstrating some S2 geometry features on map. |

## Go Compilers
        
*Tools for compiling Go to other languages.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gopherjs](https://github.com/gopherjs/gopherjs) | 9595 | 267 | 2013-08-27 | 2 months ago | Compiler from Go to JavaScript. |
| [llgo](https://github.com/go-llvm/llgo) | 1088 | 63 | 2011-11-05 | 5 years ago | LLVM-based compiler for Go. |
| [tardisgo](https://github.com/tardisgo/tardisgo) | 401 | 28 | 2014-01-08 | 3 years ago | Golang to Haxe to CPP/CSharp/Java/JavaScript transpiler. |
| [c4go](https://github.com/Konstantin8105/c4go) | 227 | 15 | 2018-03-28 | 2 weeks ago | Transpile C code to Go code. |
| [f4go](https://github.com/Konstantin8105/f4go) | 24 | 3 | 2018-07-08 | 9 months ago | Transpile FORTRAN 77 code to Go code. |

## Goroutines
        
*Tools for managing and working with Goroutines.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [ants](https://github.com/panjf2000/ants) | 4134 | 130 | 2018-05-19 | 3 days ago | A high-performance and low-cost goroutine pool in Go. |
| [goworker](https://github.com/benmanns/goworker) | 2441 | 77 | 2013-07-22 | 3 days ago | goworker is a Go-based background worker. |
| [tunny](https://github.com/Jeffail/tunny) | 1722 | 65 | 2014-04-02 | 11 months ago | Goroutine pool for golang. |
| [grpool](https://github.com/ivpusic/grpool) | 580 | 28 | 2015-07-22 | 1 year ago | Lightweight Goroutine pool. |
| [pool](https://github.com/go-playground/pool) | 577 | 15 | 2015-10-28 | 11 months ago | Limited consumer goroutine or unlimited goroutine pool for easier goroutine handling and cancellation. |
| [workerpool](https://github.com/gammazero/workerpool) | 341 | 10 | 2016-05-17 | 3 weeks ago | Goroutine pool that limits the concurrency of task execution, not the number of tasks queued. |
| [gowp](https://github.com/xxjwxc/gowp) | 222 | 13 | 2019-09-14 | 3 months ago | gowp is concurrency limiting goroutine pool. |
| [go-floc](https://github.com/workanator/go-floc) | 181 | 8 | 2017-07-03 | 2 years ago | Orchestrate goroutines with ease. |
| [go-flow](https://github.com/kamildrazkiewicz/go-flow) | 142 | 9 | 2016-09-25 | 1 year ago | Control goroutines execution order. |
| [GoSlaves](https://github.com/dgrr/GoSlaves) | 95 | 4 | 2017-09-17 | 1 year ago | Simple and Asynchronous Goroutine pool library. |
| [semaphore](https://github.com/marusama/semaphore) | 91 | 4 | 2017-11-22 | 2 months ago | Fast resizable semaphore implementation based on CAS (faster than channel-based semaphore implementations). |
| [semaphore](https://github.com/kamilsk/semaphore) | 83 | 1 | 2016-10-08 | 4 months ago | Semaphore pattern implementation with timeout of lock/unlock operations based on channel and context. |
| [pond](https://github.com/alitto/pond) | 71 | 3 | 2020-03-21 | 2 months ago | Minimalistic and High-performance goroutine worker pool written in Go. |
| [artifex](https://github.com/mborders/artifex) | 70 | 4 | 2018-10-31 | 1 week ago | Simple in-memory job queue for Golang using worker-based dispatching. |
| [breaker](https://github.com/kamilsk/breaker) | 69 | 3 | 2019-02-15 | 2 months ago | Flexible mechanism to make execution flow interruptible. |
| [gpool](https://github.com/sherifabdlnaby/gpool) | 68 | 1 | 2018-12-03 | 8 months ago | manages a resizeable pool of context-aware goroutines to bound concurrency. |
| [worker-pool](https://github.com/vardius/worker-pool) | 64 | 5 | 2017-10-04 | 5 months ago | goworker is a Go simple async worker pool. |
| [async](https://github.com/StudioSol/async) | 45 | 10 | 2017-06-30 | 5 months ago | A safe way to execute functions asynchronously, recovering them in case of panic. |
| [cyclicbarrier](https://github.com/marusama/cyclicbarrier) | 45 | 3 | 2018-01-11 | 2 months ago | CyclicBarrier for golang. |
| [errgroup](https://github.com/neilotoole/errgroup) | 42 | 1 | 2020-06-26 | 3 weeks ago | Drop-in alternative to `sync/errgroup`, limited to a pool of N worker goroutines. |
| [threadpool](https://github.com/shettyh/threadpool) | 41 | 3 | 2017-09-06 | 5 months ago | Golang threadpool implementation. |
| [routine](https://github.com/x-mod/routine) | 33 | 2 | 2019-03-04 | 6 months ago | go routine control with context, support: Main, Go, Pool and some useful Executors. |
| [gollback](https://github.com/vardius/gollback) | 32 | 1 | 2019-05-11 | 2 months ago | asynchronous simple function utilities, for managing execution of closures and callbacks. |
| [Hunch](https://github.com/AaronJan/Hunch) | 28 | 1 | 2019-06-05 | 1 year ago | Hunch provides functions like: `All`, `First`, `Retry`, `Waterfall` etc., that makes asynchronous flow control more intuitive. |
| [parallel-fn](https://github.com/rafaeljesus/parallel-fn) | 27 | 3 | 2017-06-18 | 2 years ago | Run functions in parallel. |
| [kyoo](https://github.com/dirkaholic/kyoo) | 27 | 2 | 2020-01-06 | 5 months ago | Provides an unlimited job queue and concurrent worker pools. |
| [stl](https://github.com/ssgreg/stl) | 15 | 2 | 2018-06-19 | 1 month ago | Software transactional locks based on Software Transactional Memory (STM) concurrency control mechanism. |
| [nursery](https://github.com/arunsworld/nursery) | 15 | 3 | 2019-11-23 | 4 months ago | Structured concurrency in Go. |
| [gohive](https://github.com/loveleshsharma/gohive) | 13 | 3 | 2019-05-31 | 10 months ago | A highly performant and easy to use Goroutine pool for Go. |
| [go-waitgroup](https://github.com/pieterclaerhout/go-waitgroup) | 12 | 1 | 2018-08-08 | 6 months ago | Like `sync.WaitGroup` with error handling and concurrency control. |
| [goccm](https://github.com/zenthangplus/goccm) | 12 | 1 | 2019-08-16 | 2 months ago | Go Concurrency Manager package limits the number of goroutines that allowed to run concurrently. |
| [go-trylock](https://github.com/subchen/go-trylock) | 11 | 1 | 2018-04-26 | 1 month ago | TryLock support on read-write lock for Golang. |
| [conexec](https://github.com/ITcathyh/conexec) | 6 | 2 | 2019-12-24 | 2 months ago | A concurrent toolkit to help execute funcs concurrently in an efficient and safe way.It supports specifying the overall timeout to avoid blocking and uses goroutine pool to improve efficiency. |
| [go-tools](https://github.com/nikhilsaraf/go-tools) | 5 | 2 | 2018-11-14 | 1 year ago | Manage a pool of goroutines using this lightweight library with a simple API. |
| [queue](https://github.com/AnikHasibul/queue) | 5 | 0 | 2018-12-21 | 1 year ago | Gives you a `sync.WaitGroup` like queue group accessibility. Helps you to throttle and limit goroutines, wait for the end of the all goroutines and much more. |
| [hands](https://github.com/duanckham/hands) | 4 | 1 | 2020-04-04 | 4 months ago | A process controller used to control the execution and return strategies of multiple goroutines. |

## GUI
        
*Interaction*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [fyne](https://github.com/fyne-io/fyne) | 10684 | 213 | 2018-02-04 | 10 hours ago | Cross platform native GUIs designed for Go based on Material Design. Supports: Linux, macOS, Windows, BSD, iOS and Android. |
| [qt](https://github.com/therecipe/qt) | 7713 | 307 | 2014-11-19 | 2 days ago | Qt binding for Go (support for Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi). |
| [ui](https://github.com/andlabs/ui) | 7634 | 380 | 2014-02-17 | 2 months ago | Platform-native GUI library for Go. Cross platform. |
| [webview](https://github.com/webview/webview) | 6704 | 216 | 2017-08-19 | 1 week ago | Cross-platform webview window with simple two-way JavaScript bindings (Windows / macOS / Linux). |
| [webview](https://github.com/zserge/webview) | 6166 | 211 | 2017-08-19 | 3 months ago | Cross-platform webview window with simple two-way JavaScript bindings (Windows / macOS / Linux). |
| [robotgo](https://github.com/go-vgo/robotgo) | 6098 | 223 | 2016-09-26 | 1 week ago | Go Native cross-platform GUI system automation. Control the mouse, keyboard and other. |
| [walk](https://github.com/lxn/walk) | 4781 | 262 | 2010-09-16 | 1 hour ago | Windows application library kit for Go. |
| [go-app](https://github.com/maxence-charriere/go-app) | 3939 | 124 | 2016-10-12 | 4 days ago | Package to create apps with GO, HTML and CSS. Supports: MacOS, Windows in progress. |
| [go-astilectron](https://github.com/asticode/go-astilectron) | 3382 | 136 | 2017-04-22 | 1 month ago | Build cross platform GUI apps with GO and HTML/JS/CSS (powered by Electron). |
| [app](https://github.com/maxence-charriere/app) | 3314 | 111 | 2016-10-12 | 6 months ago | Package to create apps with GO, HTML and CSS. Supports: MacOS, Windows in progress. |
| [go-sciter](https://github.com/sciter-sdk/go-sciter) | 1838 | 122 | 2015-10-15 | 3 weeks ago | Go bindings for Sciter: the Embeddable HTML/CSS/script engine for modern desktop UI development. Cross platform. |
| [systray](https://github.com/getlantern/systray) | 1284 | 58 | 2014-11-12 | 3 weeks ago | Cross platform Go library to place an icon and menu in the notification area. |
| [gotk3](https://github.com/gotk3/gotk3) | 1183 | 55 | 2015-08-13 | 2 weeks ago | Go bindings for GTK3. |
| [gosx-notifier](https://github.com/deckarep/gosx-notifier) | 529 | 14 | 2013-11-25 | 6 months ago | OSX Desktop Notifications library for Go. |
| [gowd](https://github.com/dtylman/gowd) | 274 | 27 | 2017-03-29 | 1 year ago | Rapid and simple desktop UI development with GO, HTML, CSS and NW.js. Cross platform. |
| [trayhost](https://github.com/shurcooL/trayhost) | 193 | 5 | 2014-04-25 | 10 months ago | Cross-platform Go library to place an icon in the host operating system's taskbar. |
| [go-appindicator](https://github.com/dawidd6/go-appindicator) | 9 | 3 | 2019-05-04 | 5 months ago | Go bindings for libappindicator3 C library. |
| [activity-tracker](https://github.com/prashantgupta24/activity-tracker) | 7 | 1 | 2019-03-12 | 1 year ago | OSX library to notify about any (pluggable) activity on your machine. |
| [mac-sleep-notifier](https://github.com/prashantgupta24/mac-sleep-notifier) | 4 | 1 | 2019-03-30 | 1 year ago | OSX Sleep/Wake notifications in golang. |

## Hardware
        
*Libraries, tools, and tutorials for interacting with hardware.*

## Images
        
*Libraries for manipulating images.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gocv](https://github.com/hybridgroup/gocv) | 3465 | 135 | 2017-09-18 | 17 hours ago | Go package for computer vision using OpenCV 3.3+. |
| [imaging](https://github.com/disintegration/imaging) | 3265 | 75 | 2012-12-06 | 2 months ago | Simple Go image processing package. |
| [imaginary](https://github.com/h2non/imaginary) | 3239 | 74 | 2015-03-04 | 4 days ago | Fast and simple HTTP microservice for image resizing. |
| [bild](https://github.com/anthonynsimon/bild) | 2923 | 62 | 2016-08-01 | 2 days ago | Collection of image processing algorithms in pure Go. |
| [ln](https://github.com/fogleman/ln) | 2711 | 86 | 2016-01-10 | 1 year ago | 3D line art rendering in Go. |
| [resize](https://github.com/nfnt/resize) | 2436 | 79 | 2012-08-02 | 2 years ago | Image resizing for Go with common interpolation methods. |
| [gg](https://github.com/fogleman/gg) | 2385 | 81 | 2016-02-18 | 1 week ago | 2D rendering in pure Go. |
| [pt](https://github.com/fogleman/pt) | 1877 | 59 | 2015-01-23 | 1 year ago | Path tracing engine written in Go. |
| [svgo](https://github.com/ajstarks/svgo) | 1532 | 50 | 2010-03-05 | 1 month ago | Go Language Library for SVG generation. |
| [smartcrop](https://github.com/muesli/smartcrop) | 1389 | 32 | 2014-04-07 | 4 months ago | Finds good crops for arbitrary images and crop sizes. |
| [gift](https://github.com/disintegration/gift) | 1358 | 52 | 2014-07-12 | 1 year ago | Package of image processing filters. |
| [picfit](https://github.com/thoas/picfit) | 1300 | 48 | 2014-12-06 | 2 weeks ago | An image resizing server written in Go. |
| [imagick](https://github.com/gographics/imagick) | 1207 | 55 | 2013-04-30 | 4 months ago | Go binding to ImageMagick's MagickWand C API. |
| [go-opencv](https://github.com/go-opencv/go-opencv) | 1193 | 67 | 2013-12-09 | 1 year ago | Go bindings for OpenCV. |
| [bimg](https://github.com/h2non/bimg) | 1178 | 35 | 2015-03-17 | 5 days ago | Small package for fast and efficient image processing using libvips. |
| [geopattern](https://github.com/pravj/geopattern) | 1086 | 21 | 2014-10-22 | 1 year ago | Create beautiful generative image patterns from a string. |
| [stegify](https://github.com/DimitarPetrov/stegify) | 863 | 21 | 2018-11-29 | 1 month ago | Go tool for LSB steganography, capable of hiding any file within an image. |
| [canvas](https://github.com/tdewolff/canvas) | 514 | 10 | 2017-05-20 | 4 days ago | Vector graphics to PDF, SVG or rasterized image. |
| [image2ascii](https://github.com/qeesung/image2ascii) | 436 | 9 | 2018-10-20 | 1 year ago | Convert image to ASCII. |
| [draft](https://github.com/lucasepe/draft) | 416 | 11 | 2020-06-05 | 3 weeks ago | Generate High Level Microservice Architecture diagrams for GraphViz using simple YAML syntax. |
| [mort](https://github.com/aldor007/mort) | 408 | 19 | 2017-11-19 | 6 months ago | Storage and image processing server written in Go. |
| [govatar](https://github.com/o1egl/govatar) | 386 | 7 | 2016-01-18 | 6 months ago | Library and CMD tool for generating funny avatars. |
| [goimagehash](https://github.com/corona10/goimagehash) | 335 | 9 | 2017-07-28 | 6 months ago | Go Perceptual image hashing package. |
| [go-nude](https://github.com/koyachi/go-nude) | 314 | 15 | 2014-05-02 | 1 year ago | Nudity detection with Go. |
| [rez](https://github.com/bamiaux/rez) | 201 | 9 | 2014-01-16 | 3 years ago | Image resizing in pure Go and SIMD. |
| [darkroom](https://github.com/gojek/darkroom) | 141 | 7 | 2019-07-01 | 2 weeks ago | An image proxy with changeable storage backends and image processing engines with focus on speed and resiliency. |
| [img](https://github.com/hawx/img) | 137 | 5 | 2012-07-28 | 5 years ago | Selection of image manipulation tools. |
| [mergi](https://github.com/noelyahan/mergi) | 114 | 6 | 2018-09-24 | 3 months ago | Tool & Go library for image manipulation (Merge, Crop, Resize, Watermark, Animate). |
| [go-cairo](https://github.com/ungerik/go-cairo) | 95 | 6 | 2012-08-22 | 10 months ago | Go binding for the cairo graphics library. |
| [gltf](https://github.com/qmuntal/gltf) | 79 | 1 | 2019-01-15 | 1 month ago | Efficient and robust glTF 2.0 reader, writer and validator. |
| [steganography](https://github.com/auyer/steganography) | 75 | 4 | 2018-05-21 | 6 months ago | Pure Go Library for LSB steganography. |
| [cameron](https://github.com/aofei/cameron) | 57 | 3 | 2018-05-05 | 1 week ago | An avatar generator for Go. |
| [go-gd](https://github.com/bolknote/go-gd) | 52 | 4 | 2011-05-12 | 2 years ago | Go binding for GD library. |
| [goimghdr](https://github.com/corona10/goimghdr) | 35 | 1 | 2018-02-25 | 1 year ago | The imghdr module determines the type of image contained in a file for Go. |
| [gridder](https://github.com/shomali11/gridder) | 29 | 2 | 2020-04-10 | 3 months ago | A Grid based 2D Graphics library. |
| [go-webcolors](https://github.com/jyotiska/go-webcolors) | 25 | 2 | 2014-04-24 | 5 years ago | Port of webcolors library from Python to Go. |
| [tga](https://github.com/ftrvxmtrx/tga) | 25 | 3 | 2012-10-08 | 5 years ago | Package tga is a TARGA image format decoder/encoder. |
| [mpo](https://github.com/donatj/mpo) | 6 | 1 | 2015-04-14 | 2 months ago | Decoder and conversion tool for MPO 3D Photos. |

## IoT
        
*Libraries for programming devices of the IoT.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [flogo](https://github.com/TIBCOSoftware/flogo) | 1537 | 139 | 2016-07-10 | 4 days ago | Project Flogo is an Open Source Framework for IoT Edge Apps & Integration. |
| [mainflux](https://github.com/mainflux/mainflux) | 1008 | 85 | 2015-07-06 | 1 day ago | Industrial IoT Messaging and Device Management Server. |
| [gatt](https://github.com/paypal/gatt) | 917 | 53 | 2014-04-23 | 1 month ago | Gatt is a Go package for building Bluetooth Low Energy peripherals. |
| [devices](https://github.com/goiot/devices) | 234 | 17 | 2016-05-30 | 4 years ago | Suite of libraries for IoT devices, experimental for x/exp/io. |
| [heedy](https://github.com/heedy/heedy) | 228 | 21 | 2015-01-16 | 1 month ago | Open-Source Platform for Quantified Self & IoT. |
| [sensorbee](https://github.com/sensorbee/sensorbee) | 193 | 18 | 2016-02-19 | 10 months ago | Lightweight stream processing engine for IoT. |
| [huego](https://github.com/amimof/huego) | 153 | 3 | 2017-05-16 | 3 weeks ago | An extensive Philips Hue client library for Go. |
| [eywa](https://github.com/xcodersun/eywa) | 45 | 8 | 2016-02-20 | 3 years ago | Project Eywa is essentially a connection manager that keeps track of connected devices. |

## Job Scheduler
        
*Libraries for scheduling jobs.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gron](https://github.com/roylee0704/gron) | 780 | 15 | 2016-06-04 | 1 month ago | Define time-based tasks using a simple Go API and Gron’s scheduler will run them accordingly. |
| [jobrunner](https://github.com/bamzi/jobrunner) | 712 | 24 | 2015-10-21 | 2 weeks ago | Smart and featureful cron job scheduler with job queuing and live monitoring built in. |
| [jobs](https://github.com/albrow/jobs) | 474 | 19 | 2015-02-09 | 2 years ago | Persistent and flexible background jobs library. |
| [scheduler](https://github.com/carlescere/scheduler) | 344 | 15 | 2015-02-03 | 2 years ago | Cronjobs scheduling made easy. |
| [go-cron](https://github.com/rk/go-cron) | 195 | 9 | 2011-04-15 | 6 months ago | Simple Cron library for go that can execute closures or functions at varying intervals, from once a second to once a year on a specific date and time. Primarily for web applications and long running daemons. |
| [go-quartz](https://github.com/reugn/go-quartz) | 85 | 5 | 2019-04-14 | 1 week ago | Simple, zero-dependency scheduling library for Go. |
| [leprechaun](https://github.com/kilgaloon/leprechaun) | 71 | 7 | 2018-04-08 | 6 months ago | Job scheduler that supports webhooks, crons and classic scheduling. |
| [clockwork](https://github.com/whiteShtef/clockwork) | 9 | 1 | 2018-04-23 | 6 months ago | Simple and intuitive job scheduling library in Go. |

## JSON
        
*Libraries for working with JSON.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gjson](https://github.com/tidwall/gjson) | 6971 | 144 | 2016-08-11 | 3 days ago | Get a JSON value with one line of code. |
| [gojson](https://github.com/ChimeraCoder/gojson) | 2254 | 45 | 2012-12-27 | 2 months ago | Automatically generate Go (golang) struct definitions from example JSON. |
| [kazaam](https://github.com/qntfy/kazaam) | 165 | 21 | 2016-07-19 | 4 months ago | API for arbitrary transformation of JSON documents. |
| [gojq](https://github.com/elgs/gojq) | 156 | 4 | 2015-12-30 | 2 years ago | JSON query in Golang. |
| [jsongo](https://github.com/ricardolonga/jsongo) | 95 | 1 | 2015-08-07 | 3 years ago | Fluent API to make it easier to create Json objects. |
| [gjo](https://github.com/skanehira/gjo) | 83 | 8 | 2019-02-23 | 4 months ago | Small utility to create JSON objects. |
| [jettison](https://github.com/wI2L/jettison) | 81 | 4 | 2019-08-30 | 2 weeks ago | High performance, reflection-less JSON encoder for Go. |
| [jaydiff](https://github.com/yazgazan/jaydiff) | 74 | 1 | 2017-04-24 | 11 months ago | JSON diff utility written in Go. |
| [jsonf](https://github.com/miolini/jsonf) | 57 | 3 | 2015-05-25 | 4 years ago | Console tool for highlighted formatting and struct query fetching JSON. |
| [json2go](https://github.com/m-zajac/json2go) | 54 | 2 | 2017-06-10 | 2 months ago | Advanced JSON to Go struct conversion. Provides package that can parse multiple JSON documents and create struct to fit them all. |
| [ajson](https://github.com/spyzhov/ajson) | 48 | 1 | 2019-03-07 | 1 month ago | Abstract JSON for golang with JSONPath support. |
| [mp](https://github.com/sanbornm/mp) | 41 | 2 | 2014-06-15 | 4 years ago | Simple cli email parser. It currently takes stdin and outputs JSON. |
| [go-respond](https://github.com/nicklaw5/go-respond) | 37 | 1 | 2017-03-12 | 1 year ago | Go package for handling common HTTP JSON responses. |
| [go-jsonerror](https://github.com/ddymko/go-jsonerror) | 9 | 1 | 2018-10-18 | 10 months ago | Go-JsonError is ment to allow us to easily create json response errors that follow the JsonApi spec. |
| [jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) | 9 | 1 | 2016-07-08 | 3 years ago | Go bindings based on the JSON API errors reference. |
| [jsonhal](https://github.com/RichardKnop/jsonhal) | 9 | 2 | 2016-01-15 | 5 months ago | Simple Go package to make custom structs marshal into HAL compatible JSON responses. |
| [dynjson](https://github.com/cocoonspace/dynjson) | 6 | 1 | 2020-05-06 | 2 weeks ago | Client-customizable JSON formats for dynamic APIs. |
| [ej](https://github.com/lucassscaravelli/ej) | 5 | 1 | 2020-01-04 | 4 months ago | Write and read JSON from different sources succinctly. |
| [mapslice-json](https://github.com/mickep76/mapslice-json) | 2 | 1 | 2020-02-19 | 6 months ago | Go MapSlice for ordered marshal/ unmarshal of maps in JSON. |

## Logging
        
*Libraries for generating and working with log files.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [logrus](https://github.com/sirupsen/logrus) | 15824 | 313 | 2013-10-16 | 2 weeks ago | Structured logger for Go. |
| [zap](https://github.com/uber-go/zap) | 10576 | 242 | 2016-02-18 | 59 minutes ago | Fast, structured, leveled logging in Go. |
| [go-spew](https://github.com/davecgh/go-spew) | 4018 | 61 | 2013-01-09 | 2 weeks ago | Implements a deep pretty printer for Go data structures to aid in debugging. |
| [zerolog](https://github.com/rs/zerolog) | 3720 | 56 | 2017-05-12 | 2 weeks ago | Zero-allocation JSON logger. |
| [glog](https://github.com/golang/glog) | 2589 | 87 | 2013-07-16 | 6 days ago | Leveled execution logs for Go. |
| [lumberjack](https://github.com/natefinch/lumberjack) | 2078 | 53 | 2014-06-14 | 3 weeks ago | Simple rolling logger, implements io.WriteCloser. |
| [tail](https://github.com/hpcloud/tail) | 1865 | 97 | 2013-02-05 | 1 month ago | Go package striving to emulate the features of the BSD tail program. |
| [seelog](https://github.com/cihub/seelog) | 1497 | 90 | 2011-11-17 | 1 year ago | Logging functionality with flexible dispatching, filtering, and formatting. |
| [log](https://github.com/apex/log) | 990 | 35 | 2015-12-21 | 2 weeks ago | Structured logging package for Go. |
| [log15](https://github.com/inconshreveable/log15) | 978 | 26 | 2014-05-20 | 4 months ago | Simple, powerful logging for Go. |
| [onelog](https://github.com/francoispqt/onelog) | 380 | 10 | 2018-05-06 | 1 year ago | Onelog is a dead simple but very efficient JSON logger. It is the fastest JSON logger out there in all scenario. Also, it is one of the logger with the lowest allocation. |
| [logxi](https://github.com/mgutz/logxi) | 346 | 10 | 2015-03-01 | 4 months ago | 12-factor app logger that is fast and makes you happy. |
| [logutils](https://github.com/hashicorp/logutils) | 287 | 209 | 2013-10-09 | 3 months ago | Utilities for slightly better logging in Go (Golang) extending the standard logger. |
| [log](https://github.com/go-playground/log) | 277 | 10 | 2016-02-07 | 9 months ago | Simple, configurable and scalable Structured Logging for Go. |
| [go-logger](https://github.com/apsdehal/go-logger) | 259 | 7 | 2014-09-26 | 1 year ago | Simple logger of Go Programs, with level handlers. |
| [httpretty](https://github.com/henvic/httpretty) | 189 | 5 | 2020-01-24 | 2 weeks ago | Pretty-prints your regular HTTP requests on your terminal for debugging (similar to http.DumpRequest). |
| [rollingwriter](https://github.com/arthurkiller/rollingwriter) | 149 | 7 | 2017-02-12 | 6 months ago | RollingWriter is an auto-rotate `io.Writer` implementation with multi policies to provide log file rotation. |
| [logger](https://github.com/azer/logger) | 144 | 5 | 2014-09-30 | 5 months ago | Minimalistic logging library for Go. |
| [xlog](https://github.com/rs/xlog) | 134 | 8 | 2015-10-22 | 7 months ago | Structured logger for `net/context` aware HTTP handlers with flexible dispatching. |
| [ozzo-log](https://github.com/go-ozzo/ozzo-log) | 113 | 10 | 2015-10-22 | 2 years ago | High performance logging supporting log severity, categorization, and filtering. Can send filtered log messages to various targets (e.g. console, network, mail). |
| [sqldb-logger](https://github.com/simukti/sqldb-logger) | 113 | 3 | 2019-11-02 | 2 weeks ago | A logger for Go SQL database driver without modify existing *sql.DB stdlib usage. |
| [glg](https://github.com/kpango/glg) | 94 | 5 | 2017-06-21 | 2 weeks ago | glg is simple and fast leveled logging library for Go. |
| [logur](https://github.com/logur/logur) | 90 | 5 | 2018-12-09 | 5 days ago | An opinionated logger interface and collection of logging best practices with adapters and integrations for well-known libraries ([logrus](https://github.com/sirupsen/logrus), [go-kit log](https://github.com/go-kit/kit/tree/master/log), [zap](https://github.com/uber-go/zap), [zerolog](https://github.com/rs/zerolog), etc). |
| [logvoyage](https://github.com/firstrow/logvoyage) | 89 | 5 | 2015-03-29 | 3 years ago | Full-featured logging saas written in golang. |
| [log](https://github.com/alexcesaro/log) | 45 | 6 | 2014-04-19 | 5 years ago | Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs. |
| [gologger](https://github.com/sadlil/gologger) | 38 | 5 | 2015-09-02 | 2 years ago | Simple easy to use log lib for go, logs in Colored Console, Simple Console, File or Elasticsearch. |
| [go-log](https://github.com/ian-kent/go-log) | 37 | 2 | 2014-05-02 | 2 years ago | Log4j implementation in Go. |
| [logex](https://github.com/chzyer/logex) | 36 | 7 | 2014-10-10 | 3 years ago | Golang log lib, supports tracking and level, wrap by standard log lib. |
| [go-cronowriter](https://github.com/utahta/go-cronowriter) | 31 | 1 | 2017-02-04 | 1 month ago | Simple writer that rotate log files automatically based on current date and time, like cronolog. |
| [go-log](https://github.com/siddontang/go-log) | 27 | 6 | 2014-05-18 | 1 year ago | Log lib supports level and multi handlers. |
| [logrusly](https://github.com/sebest/logrusly) | 26 | 4 | 2014-09-11 | 1 month ago | [logrus](https://github.com/sirupsen/logrus) plug-in to send errors to a [Loggly](https://www.loggly.com/). |
| [distillog](https://github.com/amoghe/distillog) | 23 | 1 | 2015-10-12 | 2 years ago | distilled levelled logging (think of it as stdlib + log levels). |
| [log](https://github.com/teris-io/log) | 23 | 1 | 2017-10-28 | 2 years ago | Structured log interface for Go cleanly separates logging facade from its implementation. |
| [journald](https://github.com/ssgreg/journald) | 22 | 2 | 2017-08-23 | 1 year ago | Go implementation of systemd Journal's native API for logging. |
| [mlog](https://github.com/jbrodriguez/mlog) | 22 | 1 | 2014-10-20 | 2 years ago | Simple logging module for go, with 5 levels, an optional rotating logfile feature and stdout/stderr output. |
| [gomol](https://github.com/aphistic/gomol) | 16 | 2 | 2015-08-30 | 1 year ago | Multiple-output, structured logging for Go with extensible logging outputs. |
| [glo](https://github.com/lajosbencz/glo) | 13 | 1 | 2019-01-19 | 1 year ago | PHP Monolog inspired logging facility with identical severity levels. |
| [go-log](https://github.com/subchen/go-log) | 11 | 2 | 2017-05-07 | 2 years ago | Simple and configurable Logging in Go, with level, formatters and writers. |
| [logrusiowriter](https://github.com/cabify/logrusiowriter) | 10 | 87 | 2019-08-09 | 1 month ago | `io.Writer` implementation using [logrus](https://github.com/sirupsen/logrus) logger. |
| [logdump](https://github.com/ewwwwwqm/logdump) | 9 | 2 | 2017-01-13 | 2 years ago | Package for multi-level logging. |
| [logmatic](https://github.com/borderstech/logmatic) | 9 | 2 | 2018-11-07 | 1 year ago | Colorized logger for Golang with dynamic log level configuration. |
| [logmatic](https://github.com/mborders/logmatic) | 9 | 2 | 2018-11-07 | 1 week ago | Colorized logger for Golang with dynamic log level configuration. |
| [go-log](https://github.com/pieterclaerhout/go-log) | 8 | 1 | 2019-10-01 | 1 month ago | A logging library with strack traces, object dumping and optional timestamps. |
| [log](https://github.com/aerogo/log) | 7 | 1 | 2017-06-10 | 10 months ago | An O(1) logging system that allows you to connect one log to multiple writers (e.g. stdout, a file and a TCP connection). |
| [logo](https://github.com/mbndr/logo) | 6 | 1 | 2017-02-07 | 2 years ago | Golang logger to different configurable writers. |
| [xlog](https://github.com/xfxdev/xlog) | 6 | 1 | 2016-05-05 | 1 year ago | Plugin architecture and flexible log system for Go, with level ctrl, multiple log target and custom log format. |
| [kemba](https://github.com/clok/kemba) | 1 | 0 | 2020-07-13 | 1 week ago | A tiny debug logging tool inspired by [debug](https://github.com/visionmedia/debug), great for CLI tools and applications. |

## Machine Learning
        
*Libraries for Machine Learning.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [golearn](https://github.com/sjwhitworth/golearn) | 7322 | 438 | 2013-12-26 | 2 days ago | General Machine Learning library for Go. |
| [gorgonia](https://github.com/gorgonia/gorgonia) | 3525 | 178 | 2016-09-14 | 5 hours ago | graph-based computational library like Theano for Go that provides primitives for building various machine learning and neural network algorithms. |
| [tfgo](https://github.com/galeone/tfgo) | 1402 | 47 | 2017-05-23 | 2 months ago | Easy to use Tensorflow bindings: simplifies the usage of the official Tensorflow Go bindings. Define computational graphs in Go, load and execute models trained in Python. |
| [gosseract](https://github.com/otiai10/gosseract) | 1263 | 43 | 2013-10-11 | 3 months ago | Go package for OCR (Optical Character Recognition), by using Tesseract C++ library. |
| [goml](https://github.com/cdipaolo/goml) | 1124 | 74 | 2015-06-27 | 1 year ago | On-line Machine Learning in Go. |
| [gorse](https://github.com/zhenghaoz/gorse) | 1027 | 43 | 2018-08-14 | 19 hours ago | An offline recommender system backend based on collaborative filtering written in Go. |
| [eaopt](https://github.com/MaxHalford/eaopt) | 695 | 28 | 2016-01-31 | 7 months ago | An evolutionary optimization library. |
| [CloudForest](https://github.com/ryanbressler/CloudForest) | 676 | 44 | 2012-10-22 | 1 year ago | Fast, flexible, multi-threaded ensembles of decision trees for machine learning in pure Go. |
| [bayesian](https://github.com/jbrukh/bayesian) | 674 | 32 | 2011-11-23 | 1 month ago | Naive Bayesian Classification for Golang. |
| [gobrain](https://github.com/goml/gobrain) | 447 | 26 | 2014-04-29 | 2 months ago | Neural Networks written in go. |
| [ocrserver](https://github.com/otiai10/ocrserver) | 320 | 11 | 2015-11-15 | 2 months ago | A simple OCR API server, seriously easy to be deployed by Docker and Heroku. |
| [go-deep](https://github.com/patrikeh/go-deep) | 280 | 13 | 2017-12-09 | 8 months ago | A feature-rich neural network library in Go. |
| [regommend](https://github.com/muesli/regommend) | 276 | 16 | 2014-02-05 | 1 year ago | Recommendation & collaborative filtering engine. |
| [onnx-go](https://github.com/owulveryck/onnx-go) | 274 | 11 | 2018-08-28 | 2 weeks ago | Go Interface to Open Neural Network Exchange (ONNX). |
| [go-galib](https://github.com/thoj/go-galib) | 181 | 13 | 2009-11-30 | 4 years ago | Genetic Algorithms library written in Go / golang. |
| [goRecommend](https://github.com/timkaye11/goRecommend) | 162 | 9 | 2014-07-16 | 6 years ago | Recommendation Algorithms library written in Go. |
| [goptuna](https://github.com/c-bata/goptuna) | 144 | 6 | 2019-07-24 | 3 weeks ago | Bayesian optimization framework for black-box functions written in Go. Everything will be optimized. |
| [shield](https://github.com/eaigner/shield) | 134 | 10 | 2013-04-10 | 6 months ago | Bayesian text classifier with flexible tokenizers and storage backends for Go. |
| [go-fann](https://github.com/vksnk/go-fann) | 102 | 7 | 2011-03-10 | 5 years ago | Go bindings for Fast Artificial Neural Networks(FANN) library. |
| [goga](https://github.com/tomcraven/goga) | 91 | 6 | 2015-10-20 | 3 years ago | Genetic algorithm library for Go. |
| [libsvm](https://github.com/datastream/libsvm) | 66 | 10 | 2012-07-31 | 4 years ago | libsvm golang version derived work based on LIBSVM 3.14. |
| [neural-go](https://github.com/schuyler/neural-go) | 62 | 2 | 2011-10-17 | 1 day ago | Multilayer perceptron network implemented in Go, with training via backpropagation. |
| [go-pr](https://github.com/daviddengcn/go-pr) | 59 | 6 | 2013-06-07 | 7 years ago | Pattern recognition package in Go lang. |
| [neat](https://github.com/jinyeom/neat) | 57 | 12 | 2016-11-17 | 2 years ago | Plug-and-play, parallel Go framework for NeuroEvolution of Augmenting Topologies (NEAT). |
| [gonet](https://github.com/dathoangnd/gonet) | 57 | 4 | 2020-01-11 | 4 months ago | Neural Network for Go. |
| [goscore](https://github.com/asafschers/goscore) | 55 | 6 | 2017-08-19 | 1 year ago | Go Scoring API for PMML. |
| [fonet](https://github.com/Fontinalis/fonet) | 43 | 3 | 2017-10-03 | 4 months ago | A Deep Neural Network library written in Go. |
| [golinear](https://github.com/danieldk/golinear) | 40 | 5 | 2013-04-05 | 2 years ago | liblinear bindings for Go. |
| [Varis](https://github.com/Xamber/Varis) | 30 | 5 | 2017-10-10 | 2 years ago | Golang Neural Network. |
| [go-cluster](https://github.com/e-XpertSolutions/go-cluster) | 26 | 5 | 2017-10-04 | 2 years ago | Go implementation of the k-modes and k-prototypes clustering algorithms. |
| [godist](https://github.com/e-dard/godist) | 25 | 2 | 2014-09-05 | 5 years ago | Various probability distributions, and associated methods. |
| [evoli](https://github.com/khezen/evoli) | 14 | 4 | 2015-06-12 | 3 months ago | Genetic Algorithm and Particle Swarm Optimization library. |
| [probab](https://github.com/ThePaw/probab) | 12 | 1 | 2015-09-14 | 5 years ago | Probability distribution functions. Bayesian inference. Written in pure Go. |
| [gomind](https://github.com/surenderthakran/gomind) | 7 | 2 | 2017-10-19 | 2 years ago | A simplistic Neural Network Library in Go. |
| [randomForest](https://github.com/malaschitz/randomForest) | 5 | 1 | 2018-10-25 | 9 months ago | Easy to use Random Forest library for Go. |

## Messaging
        
*Libraries that implement messaging systems.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [sarama](https://github.com/Shopify/sarama) | 6195 | 409 | 2013-07-05 | 45 minutes ago | Go library for Apache Kafka. |
| [gorush](https://github.com/appleboy/gorush) | 4913 | 189 | 2016-03-22 | 1 month ago | Push notification server using [APNs2](https://github.com/sideshow/apns2) and google [GCM](https://github.com/google/go-gcm). |
| [centrifugo](https://github.com/centrifugal/centrifugo) | 4541 | 192 | 2015-03-31 | 2 days ago | Real-time messaging (Websockets or SockJS) server in Go. |
| [machinery](https://github.com/RichardKnop/machinery) | 4374 | 142 | 2015-04-05 | 1 week ago | Asynchronous task queue/job queue based on distributed message passing. |
| [go-socket.io](https://github.com/googollee/go-socket.io) | 3646 | 131 | 2013-07-13 | 6 days ago | socket.io library for golang, a realtime application framework. |
| [nats.go](https://github.com/nats-io/nats.go) | 3002 | 164 | 2012-08-15 | 4 days ago | Lightweight and high performance publish-subscribe and distributed queueing messaging system - this is the Go library. |
| [benthos](https://github.com/Jeffail/benthos) | 2460 | 74 | 2016-03-22 | 1 day ago | A message streaming bridge between a range of protocols. |
| [apns2](https://github.com/sideshow/apns2) | 2365 | 75 | 2016-01-05 | 3 weeks ago | HTTP/2 Apple Push Notification provider for Go — Send push notifications to iOS, tvOS, Safari and OSX apps. |
| [confluent-kafka-go](https://github.com/confluentinc/confluent-kafka-go) | 2244 | 265 | 2016-07-12 | 13 hours ago | confluent-kafka-go is Confluent's Golang client for Apache Kafka and the Confluent Platform. |
| [mercure](https://github.com/dunglas/mercure) | 2128 | 59 | 2018-07-14 | 1 week ago | Server and library to dispatch server-sent updates using the Mercure protocol (built on top of Server-Sent Events). |
| [gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) | 1922 | 231 | 2013-12-27 | 3 years ago | gopush-cluster is a go push server cluster. |
| [melody](https://github.com/olahol/melody) | 1910 | 58 | 2015-05-13 | 7 months ago | Minimalist framework for dealing with websocket sessions, includes broadcasting and automatic ping/pong handling. |
| [go-nsq](https://github.com/nsqio/go-nsq) | 1759 | 65 | 2013-08-29 | 2 weeks ago | the official Go package for NSQ. |
| [mangos-v1](https://github.com/nanomsg/mangos-v1) | 1535 | 84 | 2014-10-25 | 10 months ago | Pure go implementation of the Nanomsg ("Scalable Protocols") with transport interoperability. |
| [uniqush-push](https://github.com/uniqush/uniqush-push) | 1191 | 78 | 2011-08-29 | 4 months ago | Redis backed unified push service for server-side notifications to mobile devices. |
| [Beaver](https://github.com/Clivern/Beaver) | 871 | 22 | 2018-10-20 | 2 weeks ago | A real time messaging server to build a scalable in-app notifications, multiplayer games, chat apps in web and mobile apps. |
| [gollum](https://github.com/trivago/gollum) | 869 | 39 | 2015-06-20 | 10 months ago | A n:m multiplexer that gathers messages from different sources and broadcasts them to a set of destinations. |
| [zmq4](https://github.com/pebbe/zmq4) | 866 | 44 | 2013-10-18 | 2 months ago | Go interface to ZeroMQ version 4. Also available for [version 3](https://github.com/pebbe/zmq3) and [version 2](https://github.com/pebbe/zmq2). |
| [EventBus](https://github.com/asaskevich/EventBus) | 770 | 27 | 2014-12-19 | 4 months ago | The lightweight event bus with async compatibility. |
| [asynq](https://github.com/hibiken/asynq) | 664 | 16 | 2019-11-15 | 4 hours ago | A simple, reliable, and efficient distributed task queue for Go built on top of Redis. |
| [dbus](https://github.com/godbus/dbus) | 483 | 16 | 2014-03-27 | 1 month ago | Native Go bindings for D-Bus. |
| [golongpoll](https://github.com/jcuga/golongpoll) | 478 | 23 | 2015-11-02 | 6 months ago | HTTP longpoll server library that makes web pub-sub simple. |
| [emitter](https://github.com/olebedev/emitter) | 373 | 9 | 2015-11-10 | 6 months ago | Emits events using Go way, with wildcard, predicates, cancellation possibilities and many other good wins. |
| [glue](https://github.com/desertbit/glue) | 345 | 15 | 2015-06-07 | 3 months ago | Robust Go and Javascript Socket Library (Alternative to Socket.io). |
| [pubsub](https://github.com/cskr/pubsub) | 329 | 8 | 2012-04-01 | 1 month ago | Simple pubsub package for go. |
| [bus](https://github.com/mustafaturan/bus) | 158 | 5 | 2019-04-27 | 6 months ago | Minimalist message bus implementation for internal communication. |
| [guble](https://github.com/smancke/guble) | 145 | 13 | 2015-11-15 | 2 years ago | Messaging server using push notifications (Google Firebase Cloud Messaging, Apple Push Notification services, SMS) as well as websockets, a REST API, featuring distributed operation and message-persistence. |
| [message-bus](https://github.com/vardius/message-bus) | 141 | 6 | 2017-10-04 | 2 months ago | messagebus is a Go simple async message bus, perfect for using as event bus when doing event sourcing, CQRS, DDD. |
| [rabtap](https://github.com/jandelgado/rabtap) | 136 | 9 | 2017-11-11 | 2 months ago | RabbitMQ swiss army knife cli app. |
| [oplog](https://github.com/dailymotion/oplog) | 104 | 92 | 2014-11-06 | 4 years ago | Generic oplog/replication system for REST APIs. |
| [rabbus](https://github.com/rafaeljesus/rabbus) | 75 | 9 | 2017-05-07 | 1 year ago | A tiny wrapper over amqp exchanges and queues. |
| [drone-line](https://github.com/appleboy/drone-line) | 71 | 5 | 2016-09-13 | 2 months ago | Sending [Line](https://at.line.me/en) notifications using a binary, docker or Drone CI. |
| [hub](https://github.com/leandro-lugaresi/hub) | 62 | 2 | 2018-04-13 | 1 month ago | A Message/Event Hub for Go applications, using publish/subscribe pattern with support for alias like rabbitMQ exchanges. |
| [nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus) | 62 | 9 | 2017-01-15 | 2 years ago | A tiny wrapper around NSQ topic and channel. |
| [RapidMQ](https://github.com/sybrexsys/RapidMQ) | 59 | 5 | 2016-10-04 | 2 years ago | RapidMQ is a lightweight and reliable library for managing of the local messages queue. |
| [go-notify](https://github.com/TheCreeper/go-notify) | 48 | 2 | 2015-03-01 | 1 year ago | Native implementation of the freedesktop notification spec. |
| [commander](https://github.com/jeroenrinzema/commander) | 47 | 1 | 2018-04-20 | 3 months ago | A high-level event driven consumer/producer supporting various "dialects" such as Apache Kafka. |
| [go-mq](https://github.com/cheshir/go-mq) | 43 | 5 | 2017-06-19 | 1 month ago | RabbitMQ client with declarative configuration. |
| [commander](https://github.com/CloudProud/commander) | 38 | 1 | 2018-04-20 | 8 months ago | A high-level event driven consumer/producer supporting various "dialects" such as Apache Kafka. |
| [go-res](https://github.com/jirenius/go-res) | 37 | 2 | 2018-07-15 | 2 months ago | Package for building REST/real-time services where clients are synchronized seamlessly, using NATS and Resgate. |
| [event](https://github.com/agoalofalife/event) | 36 | 4 | 2017-07-02 | 2 years ago | Implementation of the pattern observer. |
| [redisqueue](https://github.com/robinjoseph08/redisqueue) | 25 | 2 | 2019-07-07 | 3 months ago | redisqueue provides a producer and consumer of a queue that uses Redis streams. |
| [go-vitotrol](https://github.com/maxatome/go-vitotrol) | 14 | 6 | 2016-11-03 | 1 year ago | Client library to Viessmann Vitotrol web service. |
| [gosd](https://github.com/alexsniffin/gosd) | 12 | 1 | 2020-05-17 | 2 weeks ago | A library for scheduling when to dispatch a message to a channel. |
| [jazz](https://github.com/socifi/jazz) | 11 | 3 | 2018-10-22 | 1 year ago | A simple RabbitMQ abstraction layer for queue administration and publishing and consuming of messages. |
| [rmqconn](https://github.com/sbabiv/rmqconn) | 10 | 0 | 2019-01-14 | 7 months ago | RabbitMQ Reconnection. Wrapper over amqp.Connection and amqp.Dial. Allowing to do a reconnection when the connection is broken before forcing the call to the Close () method to be closed. |
| [gaurun-client](https://github.com/osamingo/gaurun-client) | 9 | 1 | 2017-06-29 | 1 year ago | Gaurun Client written in Go. |
| [ami](https://github.com/kak-tus/ami) | 8 | 1 | 2018-10-27 | 5 months ago | Go client to reliable queues based on Redis Cluster Streams. |

## Microsoft Office
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [unioffice](https://github.com/unidoc/unioffice) | 2507 | 64 | 2017-08-29 | 18 hours ago | Pure go library for creating and processing Office Word (.docx), Excel (.xlsx) and Powerpoint (.pptx) documents. |

### Microsoft Excel
        
*Libraries for working with Microsoft Excel.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [excelize](https://github.com/360EntSecGroup-Skylar/excelize) | 6822 | 177 | 2016-08-29 | 1 day ago | Golang library for reading and writing Microsoft Excel™ (XLSX) files. |
| [xlsx](https://github.com/tealeg/xlsx) | 4445 | 183 | 2011-06-28 | 5 days ago | Library to simplify reading the XML format used by recent version of Microsoft Excel in Go programs. |
| [xlsx](https://github.com/plandem/xlsx) | 120 | 12 | 2017-08-26 | 8 months ago | Fast and safe way to read/update your existing Microsoft Excel files in Go programs. |
| [go-excel](https://github.com/szyhf/go-excel) | 90 | 3 | 2017-09-03 | 8 months ago | A simple and light reader to read a relate-db-like excel as a table. |
| [goxlsxwriter](https://github.com/fterrag/goxlsxwriter) | 14 | 2 | 2017-03-13 | 2 years ago | Golang bindings for libxlsxwriter for writing XLSX (Microsoft Excel) files. |

## Miscellaneous
        

### Dependency Injection
        
*Libraries for working with dependency injection.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [dig](https://github.com/uber-go/dig) | 1556 | 43 | 2017-03-21 | 2 months ago | A reflection based dependency injection toolkit for Go. |
| [fx](https://github.com/uber-go/fx) | 1457 | 53 | 2016-10-27 | 1 week ago | A dependency injection based application framework for Go (built on top of dig). |
| [container](https://github.com/golobby/container) | 99 | 3 | 2019-09-23 | 1 day ago | A powerful IoC Container with fluent and easy-to-use interface. |
| [dingo](https://github.com/i-love-flamingo/dingo) | 83 | 24 | 2018-10-29 | 1 week ago | A dependency injection toolkit for Go, based on Guice. |
| [inject](https://github.com/defval/inject) | 53 | 1 | 2019-02-03 | 6 months ago | A reflection based dependency injection container with simple interface. |
| [alice](https://github.com/magic003/alice) | 43 | 2 | 2017-04-08 | 3 years ago | Additive dependency injection container for Golang. |
| [di](https://github.com/goava/di) | 34 | 4 | 2020-02-03 | 6 days ago | A dependency injection container for go programming language. |
| [di](https://github.com/goioc/di) | 33 | 2 | 2020-06-11 | 1 week ago | Spring-inspired Dependency Injection Container. |
| [wire](https://github.com/Fs02/wire) | 31 | 1 | 2018-07-05 | 6 months ago | Strict Runtime Dependency Injection for Golang. |
| [linker](https://github.com/logrange/linker) | 24 | 3 | 2018-12-04 | 2 months ago | A reflection based dependency injection and inversion of control library with components lifecycle support. |
| [gocontainer](https://github.com/vardius/gocontainer) | 12 | 0 | 2019-06-06 | 5 months ago | Simple Dependency Injection Container. |

### Project Layout
        
*Unofficial set of patterns for structuring projects.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [project-layout](https://github.com/golang-standards/project-layout) | 17632 | 466 | 2017-09-09 | 3 weeks ago | Set of common historical and emerging project layout patterns in the Go ecosystem. |
| [go-restful-api](https://github.com/qiangxue/go-restful-api) | 1038 | 52 | 2016-08-15 | 7 months ago | An idiomatic Go RESTful API starter kit following SOLID principles and Clean Architecture with a common project layout. |
| [modern-go-application](https://github.com/sagikazarmark/modern-go-application) | 743 | 16 | 2018-09-14 | 1 month ago | Go application boilerplate and example applying modern practices. |
| [cookiecutter-golang](https://github.com/lacion/cookiecutter-golang) | 377 | 7 | 2016-12-18 | 4 months ago | A Go application boilerplate template for quick starting projects following production best practices. |
| [scaffold](https://github.com/catchplay/scaffold) | 80 | 3 | 2018-12-11 | 1 year ago | Scaffold generates starter Go project layout. Lets you focus on business logic implemeted. |
| [go-sample](https://github.com/zitryss/go-sample) | 65 | 1 | 2019-01-24 | 1 year ago | A sample layout for Go application projects with the real code. |

### Strings
        
*Libraries for working with strings.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [xstrings](https://github.com/huandu/xstrings) | 794 | 24 | 2015-01-06 | 2 months ago | Collection of useful string functions ported from other languages. |
| [strutil](https://github.com/ozgio/strutil) | 102 | 1 | 2018-08-16 | 10 months ago | String utilities. |
| [stringy](https://github.com/gobeam/stringy) | 32 | 2 | 2020-04-03 | 1 month ago | String manipulation library to convert string to camel case, snake case, kebab case / slugify etc. |
| [Stringy](https://github.com/gobeam/Stringy) | 30 | 1 | 2020-04-03 | 4 months ago | String manipulation library to convert string to camel case, snake case, kebab case / slugify etc. |

### Uncategorized
        
*These libraries were placed here because none of the other categories seemed to fit.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gopsutil](https://github.com/shirou/gopsutil) | 5237 | 196 | 2014-04-18 | 3 hours ago | Cross-platform library for retrieving process and system utilization(CPU, Memory, Disks, etc). |
| [archiver](https://github.com/mholt/archiver) | 2887 | 50 | 2016-04-08 | 2 hours ago | Library and command for making and extracting .zip and .tar.gz archives. |
| [gosms](https://github.com/haxpax/gosms) | 1301 | 56 | 2015-01-23 | 1 month ago | Your own local SMS gateway in Go that can be used to send SMS. |
| [gofakeit](https://github.com/brianvoe/gofakeit) | 1241 | 10 | 2015-04-24 | 1 week ago | Random data generator written in go. |
| [go-resiliency](https://github.com/eapache/go-resiliency) | 1051 | 28 | 2014-11-29 | 9 months ago | Resiliency patterns for golang. |
| [base64Captcha](https://github.com/mojocn/base64Captcha) | 920 | 47 | 2017-12-12 | 2 months ago | Base64captch supports digit, number, alphabet, arithmetic, audio and digit-alphabet captcha. |
| [go-commons-pool](https://github.com/jolestar/go-commons-pool) | 835 | 47 | 2015-12-28 | 1 month ago | Generic object pool for Golang. |
| [shortid](https://github.com/teris-io/shortid) | 601 | 9 | 2016-01-04 | 1 week ago | Distributed generation of super short, unique, non-sequential, URL friendly IDs. |
| [llvm](https://github.com/llir/llvm) | 564 | 28 | 2014-09-19 | 3 weeks ago | Library for interacting with LLVM IR in pure Go. |
| [health](https://github.com/dimiro1/health) | 402 | 6 | 2016-03-08 | 10 months ago | Easy to use, extensible health check library. |
| [go-conv](https://github.com/cstockton/go-conv) | 358 | 8 | 2016-10-11 | 3 years ago | Package conv provides fast and intuitive conversions across Go types. |
| [banner](https://github.com/dimiro1/banner) | 281 | 5 | 2016-03-25 | 10 months ago | Add beautiful banners into your Go applications. |
| [gountries](https://github.com/pariz/gountries) | 269 | 8 | 2016-01-13 | 5 days ago | Package that exposes country and subdivision data. |
| [ghorg](https://github.com/gabrie30/ghorg) | 240 | 7 | 2018-03-29 | 2 weeks ago | Quickly clone an entire org/users repositories into one directory - Supports GitHub, GitLab, and Bitbucket. |
| [stateless](https://github.com/qmuntal/stateless) | 191 | 4 | 2019-09-11 | 2 weeks ago | A fluent library for creating state machines. |
| [antch](https://github.com/antchfx/antch) | 187 | 13 | 2017-09-28 | 3 months ago | A fast, powerful and extensible web crawling & scraping framework. |
| [ffmt](https://github.com/go-ffmt/ffmt) | 184 | 5 | 2015-02-14 | 1 month ago | Beautify data display for Humans. |
| [lk](https://github.com/hyperboloide/lk) | 167 | 6 | 2016-07-14 | 4 months ago | A simple licensing library for golang. |
| [battery](https://github.com/distatus/battery) | 157 | 3 | 2016-03-12 | 1 month ago | Cross-platform, normalized battery information library. |
| [stats](https://github.com/go-playground/stats) | 139 | 3 | 2015-09-14 | 4 years ago | Monitors Go MemStats + System stats such as Memory, Swap and CPU and sends via UDP anywhere you want for logging etc... |
| [healthcheck](https://github.com/etherlabsio/healthcheck) | 137 | 5 | 2017-08-18 | 8 months ago | An opinionated and concurrent health-check HTTP handler for RESTful services. |
| [bitio](https://github.com/icza/bitio) | 134 | 6 | 2016-05-31 | 8 months ago | Highly optimized bit-level Reader and Writer for Go. |
| [turtle](https://github.com/hackebrot/turtle) | 109 | 1 | 2017-09-08 | 2 months ago | Emojis for Go. |
| [go-unarr](https://github.com/gen2brain/go-unarr) | 108 | 6 | 2015-11-01 | 6 months ago | Decompression library for RAR, TAR, ZIP and 7z archives. |
| [shoutrrr](https://github.com/containrrr/shoutrrr) | 97 | 5 | 2019-04-11 | 3 days ago | Notification library providing easy access to various messaging services like slack, mattermost, gotify and smtp among others. |
| [gommit](https://github.com/antham/gommit) | 91 | 3 | 2016-08-30 | 1 week ago | Analyze git commit messages to ensure they follow defined patterns. |
| [gotoprom](https://github.com/cabify/gotoprom) | 82 | 90 | 2018-10-10 | 7 months ago | Type-safe metrics builder wrapper library for the official Prometheus client. |
| [captcha](https://github.com/steambap/captcha) | 68 | 5 | 2017-09-12 | 1 month ago | Package captcha provides an easy to use, unopinionated API for captcha generation. |
| [indigo](https://github.com/osamingo/indigo) | 61 | 1 | 2016-08-31 | 4 days ago | Distributed unique ID generator of using Sonyflake and encoded by Base58. |
| [morse](https://github.com/alwindoss/morse) | 61 | 2 | 2018-08-15 | 1 year ago | Library to convert to and from morse code. |
| [xkg](https://github.com/go-xkg/xkg) | 50 | 1 | 2015-01-05 | 5 years ago | X Keyboard Grabber. |
| [pdfgen](https://github.com/hyperboloide/pdfgen) | 45 | 3 | 2015-11-30 | 2 years ago | HTTP service to generate PDF from Json requests. |
| [persian](https://github.com/mavihq/persian) | 42 | 1 | 2017-10-16 | 2 years ago | Some utilities for Persian language in go. |
| [datacounter](https://github.com/miolini/datacounter) | 33 | 1 | 2015-10-14 | 6 months ago | Go counters for readers/writer/http.ResponseWriter. |
| [browscap_go](https://github.com/digitalcrab/browscap_go) | 31 | 6 | 2014-09-18 | 8 months ago | GoLang Library for [Browser Capabilities Project](http://browscap.org/). |
| [autoflags](https://github.com/artyom/autoflags) | 29 | 4 | 2014-05-15 | 1 year ago | Go package to automatically define command line flags from struct fields. |
| [sandid](https://github.com/aofei/sandid) | 26 | 1 | 2018-06-12 | 5 days ago | Every grain of sand on earth has its own ID. |
| [gosh](https://github.com/osamingo/gosh) | 23 | 0 | 2018-05-25 | 8 months ago | Provide Go Statistics Handler, Struct, Measure Method. |
| [url-shortener](https://github.com/pantrif/url-shortener) | 23 | 1 | 2018-06-04 | 2 years ago | A modern, powerful, and robust URL shortener microservice with mysql support. |
| [xdg](https://github.com/rkoesters/xdg) | 22 | 1 | 2013-12-15 | 1 year ago | FreeDesktop.org (xdg) Specs implemented in Go. |
| [metrics](https://github.com/pascaldekloe/metrics) | 13 | 1 | 2019-01-29 | 6 months ago | Library for metrics instrumentation and Prometheus exposition. |
| [anagent](https://github.com/mudler/anagent) | 11 | 2 | 2017-12-29 | 2 years ago | Minimalistic, pluggable Golang evloop/timer handler with dependency-injection. |
| [shellwords](https://github.com/Wing924/shellwords) | 11 | 1 | 2017-09-28 | 2 years ago | A Golang library to manipulate strings according to the word parsing rules of the UNIX Bourne shell. |
| [avgRating](https://github.com/kirillDanshin/avgRating) | 10 | 1 | 2017-08-05 | 3 years ago | Calculate average score and rating based on Wilson Score Equation. |
| [hostutils](https://github.com/Wing924/hostutils) | 9 | 1 | 2017-09-26 | 1 year ago | A golang library for packing and unpacking FQDNs list. |
| [numa](https://github.com/lrita/numa) | 3 | 1 | 2018-12-10 | 1 year ago | NUMA is a utility library, which is written in go. It help us to write some NUMA-AWARED code. |

## Natural Language Processing
        
*Libraries for working with human languages.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [prose](https://github.com/jdkato/prose) | 2582 | 58 | 2017-02-17 | 1 week ago | Library for text processing that supports tokenization, part-of-speech tagging, named-entity extraction, and more. English only. |
| [gse](https://github.com/go-ego/gse) | 1402 | 49 | 2017-06-23 | 1 week ago | Go efficient text segmentation; support english, chinese, japanese and other. |
| [gojieba](https://github.com/yanyiwu/gojieba) | 1207 | 69 | 2015-09-12 | 3 months ago | This is a Go implementation of [jieba](https://github.com/fxsjy/jieba) which a Chinese word splitting algorithm. |
| [when](https://github.com/olebedev/when) | 1086 | 24 | 2016-12-27 | 5 days ago | Natural EN and RU language date/time parser with pluggable rules. |
| [go-pinyin](https://github.com/mozillazg/go-pinyin) | 793 | 34 | 2014-11-09 | 2 months ago | CN Hanzi to Hanyu Pinyin converter. |
| [kagome](https://github.com/ikawaha/kagome) | 515 | 24 | 2014-06-26 | 2 weeks ago | JP morphological analyzer written in pure Go. |
| [whatlanggo](https://github.com/abadojack/whatlanggo) | 440 | 15 | 2017-02-20 | 1 year ago | Natural language detection package for Go. Supports 84 languages and 24 scripts (writing systems e.g. Latin, Cyrillic, etc). |
| [nlp](https://github.com/shixzie/nlp) | 364 | 23 | 2017-01-25 | 2 years ago | Extract values from strings and fill your structs with nlp. |
| [sentences](https://github.com/neurosnap/sentences) | 283 | 13 | 2015-08-07 | 1 year ago | Sentence tokenizer:  converts text into a list of sentences. |
| [nlp](https://github.com/james-bowman/nlp) | 278 | 23 | 2017-03-15 | 4 weeks ago | Go Natural Language Processing library supporting LSA (Latent Semantic Analysis). |
| [getlang](https://github.com/rylans/getlang) | 99 | 3 | 2018-03-01 | 3 months ago | Fast natural language detection package. |
| [go-nlp](https://github.com/nuance/go-nlp) | 86 | 7 | 2011-05-02 | 8 years ago | Utilities for working with discrete probability distributions and other tools useful for doing NLP work. |
| [go-unidecode](https://github.com/mozillazg/go-unidecode) | 74 | 2 | 2016-07-08 | 1 year ago | ASCII transliterations of Unicode text. |
| [gounidecode](https://github.com/fiam/gounidecode) | 71 | 3 | 2012-05-01 | 5 years ago | Unicode transliterator (also known as unidecode) for Go. |
| [RAKE.Go](https://github.com/afjoseph/RAKE.Go) | 66 | 6 | 2016-12-17 | 6 months ago | Go port of the Rapid Automatic Keyword Extraction Algorithm (RAKE). |
| [textcat](https://github.com/pebbe/textcat) | 62 | 6 | 2012-09-21 | 2 years ago | Go package for n-gram based text categorization, with support for utf-8 and raw text. |
| [MMSEGO](https://github.com/awsong/MMSEGO) | 59 | 5 | 2012-04-18 | 8 years ago | This is a GO implementation of [MMSEG](http://technology.chtsai.org/mmseg/) which a Chinese word splitting algorithm. |
| [go-stem](https://github.com/agonopol/go-stem) | 58 | 3 | 2011-09-23 | 2 years ago | Implementation of the porter stemming algorithm. |
| [stemmer](https://github.com/dchest/stemmer) | 49 | 4 | 2011-03-21 | 3 years ago | Stemmer packages for Go programming language. Includes English and German stemmers. |
| [go2vec](https://github.com/danieldk/go2vec) | 40 | 7 | 2015-01-27 | 2 years ago | Reader and utility functions for word2vec embeddings. |
| [porter2](https://github.com/zentures/porter2) | 38 | 2 | 2015-01-21 | 5 years ago | Really fast Porter 2 stemmer. |
| [petrovich](https://github.com/striker2000/petrovich) | 30 | 1 | 2016-12-26 | 3 months ago | Petrovich is the library which inflects Russian names to given grammatical case. |
| [snowball](https://github.com/goodsign/snowball) | 28 | 1 | 2012-12-11 | 3 years ago | Snowball stemmer port (cgo wrapper) for Go. Provides word stem extraction functionality [Snowball native](http://snowball.tartarus.org/). |
| [paicehusk](https://github.com/rookii/paicehusk) | 26 | 3 | 2012-09-29 | 6 years ago | Golang implementation of the Paice/Husk Stemming Algorithm. |
| [mystem](https://github.com/dveselov/mystem) | 25 | 3 | 2016-08-30 | 3 years ago | CGo bindings to Yandex.Mystem - russian morphology analyzer. |
| [icu](https://github.com/goodsign/icu) | 20 | 0 | 2012-12-11 | 3 years ago | Cgo binding for icu4c C library detection and conversion functions. Guaranteed compatibility with version 50.1. |
| [golibstemmer](https://github.com/rjohnsondev/golibstemmer) | 17 | 1 | 2012-08-06 | 6 years ago | Go bindings for the snowball libstemmer library including porter 2. |
| [iuliia-go](https://github.com/mehanizm/iuliia-go) | 14 | 1 | 2020-04-27 | 3 months ago | Transliterate Cyrillic → Latin in every possible way. |
| [shamoji](https://github.com/osamingo/shamoji) | 12 | 2 | 2017-07-23 | 8 months ago | The shamoji is word filtering package written in Go. |
| [libtextcat](https://github.com/goodsign/libtextcat) | 10 | 1 | 2012-12-10 | 7 years ago | Cgo binding for libtextcat C library. Guaranteed compatibility with version 2.2. |
| [gotokenizer](https://github.com/xujiajun/gotokenizer) | 9 | 1 | 2018-10-11 | 1 year ago | A tokenizer based on the dictionary and Bigram language models for Go. (Now only support chinese segmentation) |
| [porter](https://github.com/a2800276/porter) | 8 | 1 | 2013-09-17 | 7 years ago | This is a fairly straightforward port of Martin Porter's C implementation of the Porter stemming algorithm. |
| [go-localize](https://github.com/m1/go-localize) | 7 | 2 | 2019-12-23 | 8 months ago | Simple and easy to use i18n (Internationalization and localization) engine - used for translating locale strings. |
| [transliterator](https://github.com/alexsergivan/transliterator) | 6 | 1 | 2020-04-17 | 3 months ago | Provides one-way string transliteration with supporting of language-specific transliteration rules. |
| [detectlanguage-go](https://github.com/detectlanguage/detectlanguage-go) | 2 | 0 | 2019-12-14 | 8 months ago | Language Detection API Go Client. Supports batch requests, short phrase or single word language detection. |

## Networking
        
*Libraries for working with various layers of the network.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [fasthttp](https://github.com/valyala/fasthttp) | 13285 | 391 | 2015-10-18 | 6 days ago | Package fasthttp is a fast HTTP implementation for Go, up to 10 times faster than net/http. |
| [kcptun](https://github.com/xtaci/kcptun) | 12016 | 598 | 2016-02-26 | 3 weeks ago | Extremely simple & fast udp tunnel based on KCP protocol. |
| [webrtc](https://github.com/pion/webrtc) | 5319 | 204 | 2018-05-18 | 2 hours ago | A pure Go implementation of the WebRTC API. |
| [dns](https://github.com/miekg/dns) | 4786 | 169 | 2010-08-03 | 6 days ago | Go library for working with DNS. |
| [quic-go](https://github.com/lucas-clemente/quic-go) | 4359 | 176 | 2016-04-06 | 1 day ago | An implementation of the QUIC protocol in pure Go. |
| [gopacket](https://github.com/google/gopacket) | 3599 | 139 | 2015-03-16 | 10 hours ago | Go library for packet processing with libpcap bindings. |
| [httplab](https://github.com/gchaincl/httplab) | 3596 | 66 | 2017-02-08 | 1 year ago | HTTPLabs let you inspect HTTP requests and forge responses. |
| [gnet](https://github.com/panjf2000/gnet) | 2882 | 115 | 2019-02-24 | 1 week ago | `gnet` is a high-performance, lightweight, non-blocking, event-driven networking framework written in pure Go. |
| [kcp-go](https://github.com/xtaci/kcp-go) | 2695 | 146 | 2015-06-16 | 3 weeks ago | KCP - Fast and Reliable ARQ Protocol. |
| [gobgp](https://github.com/osrg/gobgp) | 1991 | 125 | 2014-09-14 | 1 day ago | BGP implemented in the Go Programming Language. |
| [ssh](https://github.com/gliderlabs/ssh) | 1684 | 50 | 2016-10-03 | 1 month ago | Higher-level API for building SSH servers (wraps crypto/ssh). |
| [fortio](https://github.com/fortio/fortio) | 1422 | 38 | 2017-10-10 | 1 week ago | Load testing library and command line tool, advanced echo server and web UI. Allows to specify a set query-per-second load and record latency histograms and other useful stats and graph them. Tcp, Http, gRPC. |
| [water](https://github.com/songgao/water) | 1088 | 43 | 2013-03-25 | 3 months ago | Simple TUN/TAP library. |
| [go-getter](https://github.com/hashicorp/go-getter) | 964 | 195 | 2015-10-12 | 9 hours ago | Go library for downloading files or directories from various sources using a URL. |
| [nff-go](https://github.com/intel-go/nff-go) | 926 | 76 | 2017-03-29 | 1 week ago | Framework for rapid development of performant network functions for cloud and bare-metal (former YANFF). |
| [gev](https://github.com/Allenxuxu/gev) | 903 | 32 | 2019-09-01 | 6 days ago | gev is a lightweight, fast non-blocking TCP network library based on Reactor mode. |
| [sftp](https://github.com/pkg/sftp) | 895 | 54 | 2013-11-05 | 2 days ago | Package sftp implements the SSH File Transfer Protocol as described in https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt. |
| [grab](https://github.com/cavaliercoder/grab) | 728 | 16 | 2016-01-05 | 2 months ago | Go package for managing file downloads. |
| [ftp](https://github.com/jlaffaye/ftp) | 705 | 25 | 2011-05-06 | 2 weeks ago | Package ftp implements a FTP client as described in [RFC 959](http://tools.ietf.org/html/rfc959). |
| [mdns](https://github.com/hashicorp/mdns) | 671 | 208 | 2014-01-29 | 6 months ago | Simple mDNS (Multicast DNS) client/server library in Golang. |
| [vssh](https://github.com/yahoo/vssh) | 600 | 21 | 2020-06-09 | 1 week ago | Go library for building network and server automation over SSH protocol. |
| [lhttp](https://github.com/fanux/lhttp) | 579 | 57 | 2015-12-29 | 2 years ago | Powerful websocket framework, build your IM server more easily. |
| [gosnmp](https://github.com/soniah/gosnmp) | 556 | 45 | 2012-08-27 | 1 week ago | Native Go library for performing SNMP actions. |
| [cidranger](https://github.com/yl2chen/cidranger) | 523 | 13 | 2017-08-21 | 3 days ago | Fast IP to CIDR lookup for Go. |
| [gotcp](https://github.com/gansidui/gotcp) | 467 | 42 | 2014-04-13 | 3 years ago | Go package for quickly writing tcp applications. |
| [peerdiscovery](https://github.com/schollz/peerdiscovery) | 433 | 18 | 2018-04-22 | 22 hours ago | Pure Go library for cross-platform local peer discovery using UDP multicast. |
| [stun](https://github.com/gortc/stun) | 401 | 16 | 2016-04-24 | 4 months ago | Go implementation of RFC 5389 STUN protocol. |
| [gopcap](https://github.com/akrennmair/gopcap) | 397 | 22 | 2009-11-19 | 5 months ago | Go wrapper for libpcap. |
| [go-stun](https://github.com/ccding/go-stun) | 383 | 11 | 2013-08-17 | 1 month ago | Go implementation of the STUN client (RFC 3489 and RFC 5389). |
| [raw](https://github.com/mdlayher/raw) | 363 | 12 | 2015-07-06 | 3 months ago | Package raw enables reading and writing data at the device driver level for a network interface. |
| [tcp_server](https://github.com/firstrow/tcp_server) | 339 | 18 | 2014-10-13 | 1 year ago | Go library for building tcp servers faster. |
| [winrm](https://github.com/masterzen/winrm) | 266 | 18 | 2013-12-30 | 2 months ago | Go WinRM client to remotely execute commands on Windows machines. |
| [buffstreams](https://github.com/StabbyCutyou/buffstreams) | 239 | 13 | 2015-06-29 | 2 weeks ago | Streaming protocolbuffer data over TCP made easy. |
| [arp](https://github.com/mdlayher/arp) | 228 | 10 | 2015-07-06 | 8 months ago | Package arp implements the ARP protocol, as described in RFC 826. |
| [ethernet](https://github.com/mdlayher/ethernet) | 205 | 13 | 2015-07-03 | 1 year ago | Package ethernet implements marshaling and unmarshaling of IEEE 802.3 Ethernet II frames and IEEE 802.1Q VLAN tags. |
| [gaio](https://github.com/xtaci/gaio) | 205 | 12 | 2019-12-20 | 2 months ago | High performance async-io networking for Golang in proactor mode. |
| [gmqtt](https://github.com/DrmagicE/gmqtt) | 161 | 14 | 2018-09-16 | 1 day ago | Gmqtt is a flexible, high-performance MQTT broker library that fully implements the MQTT protocol V3.1.1. |
| [jazigo](https://github.com/udhos/jazigo) | 154 | 12 | 2016-06-07 | 11 months ago | Jazigo is a tool written in Go for retrieving configuration for multiple network devices. |
| [utp](https://github.com/anacrolix/utp) | 152 | 16 | 2015-03-20 | 2 years ago | Go uTP micro transport protocol implementation. |
| [gnxi](https://github.com/google/gnxi) | 145 | 26 | 2017-09-26 | 8 hours ago | A collection of tools for Network Management that use the gNMI and gNOI protocols. |
| [canopus](https://github.com/zubairhamed/canopus) | 142 | 14 | 2015-02-24 | 2 years ago | CoAP Client/Server implementation (RFC 7252). |
| [sslb](https://github.com/eduardonunesp/sslb) | 127 | 8 | 2015-10-18 | 11 months ago | It's a Super Simples Load Balancer, just a little project to achieve some kind of performance. |
| [xtcp](https://github.com/xfxdev/xtcp) | 103 | 14 | 2016-03-31 | 6 months ago | TCP Server Framework with simultaneous full duplex communication,graceful shutdown,custom protocol. |
| [dhcp6](https://github.com/mdlayher/dhcp6) | 67 | 4 | 2015-05-22 | 1 year ago | Package dhcp6 implements a DHCPv6 server, as described in RFC 3315. |
| [ether](https://github.com/songgao/ether) | 66 | 3 | 2014-05-21 | 4 years ago | Cross-platform Go package for sending and receiving ethernet frames. |
| [packet](https://github.com/aerogo/packet) | 52 | 3 | 2017-10-29 | 9 months ago | Send packets over TCP and UDP. It can buffer messages and hot-swap connections if needed. |
| [linkio](https://github.com/ian-kent/linkio) | 49 | 2 | 2014-12-24 | 3 years ago | Network link speed simulation for Reader/Writer interfaces. |
| [portproxy](https://github.com/aybabtme/portproxy) | 44 | 0 | 2014-12-13 | 5 years ago | Simple TCP proxy which adds CORS support to API's which don't support it. |
| [graval](https://github.com/koofr/graval) | 26 | 8 | 2014-04-22 | 2 years ago | Experimental FTP server framework. |
| [publicip](https://github.com/polera/publicip) | 21 | 2 | 2016-12-28 | 3 years ago | Package publicip returns your public facing IPv4 address (internet egress). |
| [golibwireshark](https://github.com/sunwxg/golibwireshark) | 18 | 2 | 2015-11-16 | 2 years ago | Package golibwireshark use libwireshark library to decode pcap file and analyse dissection data. |
| [go-powerdns](https://github.com/joeig/go-powerdns) | 17 | 2 | 2018-06-21 | 2 months ago | PowerDNS API bindings for Golang. |
| [goshark](https://github.com/sunwxg/goshark) | 10 | 1 | 2015-11-01 | 2 years ago | Package goshark use tshark to decode IP packet and create data struct to analyse packet. |
| [llb](https://github.com/kirillDanshin/llb) | 10 | 1 | 2016-02-21 | 4 years ago | It's a very simple but quick backend for proxy servers. Can be useful for fast redirection to predefined domain with zero memory allocation and fast response. |
| [tspool](https://github.com/two/tspool) | 7 | 0 | 2018-10-27 | 1 year ago | A TCP Library use worker pool to improve performance and protect your server. |
| [gosocsvr](https://github.com/Rakeki/gosocsvr) | 5 | 2 | 2019-11-12 | 9 months ago | Socket server made simple. |
| [httpproxy](https://github.com/wzshiming/httpproxy) | 3 | 1 | 2018-07-18 | 3 months ago | HTTP proxy handler and dialer. |

### HTTP Clients
        
*Libraries for making HTTP requests.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [resty](https://github.com/go-resty/resty) | 3231 | 76 | 2015-08-28 | 1 week ago | Simple HTTP and REST client for Go inspired by Ruby rest-client. |
| [grequests](https://github.com/levigross/grequests) | 1636 | 34 | 2015-06-11 | 7 months ago | A Go "clone" of the great and famous Requests library. |
| [heimdall](https://github.com/gojek/heimdall) | 1587 | 50 | 2018-01-19 | 1 week ago | An enchanced http client with retry and hystrix capabilities. |
| [sling](https://github.com/dghubble/sling) | 1176 | 33 | 2015-04-02 | 1 month ago | Sling is a Go HTTP client library for creating and sending API requests. |
| [gentleman](https://github.com/h2non/gentleman) | 823 | 21 | 2016-02-21 | 3 weeks ago | Full-featured plugin-driven HTTP client library. |
| [pester](https://github.com/sethgrid/pester) | 515 | 6 | 2015-05-20 | 2 months ago | Go HTTP client calls with retries, backoff, and concurrency. |
| [request](https://github.com/monaco-io/request) | 67 | 6 | 2020-03-25 | 1 month ago | HTTP client for golang. If you have experience about axios or requests, you will love it. No 3rd dependency. |
| [sreq](https://github.com/winterssy/sreq) | 50 | 0 | 2019-12-04 | 7 months ago | A simple, user-friendly and concurrent safe HTTP request library for Go. |
| [rq](https://github.com/ddo/rq) | 36 | 2 | 2017-12-26 | 1 year ago | A nicer interface for golang stdlib HTTP client. |
| [httpretry](https://github.com/ybbus/httpretry) | 10 | 2 | 2020-02-05 | 6 months ago | Enriches the default go HTTP client with retry functionality. |
| [go-http-client](https://github.com/bozd4g/go-http-client) | 10 | 1 | 2019-12-14 | 2 months ago | Make http calls simply and easily. |

## OpenGL
        
*Libraries for using OpenGL in Go.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [glfw](https://github.com/go-gl/glfw) | 975 | 42 | 2013-05-19 | 1 month ago | Go bindings for GLFW 3. |
| [gl](https://github.com/go-gl/gl) | 744 | 39 | 2015-02-22 | 1 year ago | Go bindings for OpenGL (generated via glow). |
| [mathgl](https://github.com/go-gl/mathgl) | 340 | 25 | 2013-02-13 | 10 months ago | Pure Go math package specialized for 3D math, with inspiration from GLM. |
| [gl](https://github.com/goxjs/gl) | 140 | 15 | 2015-05-18 | 5 months ago | Go cross-platform OpenGL bindings (OS X, Linux, Windows, browsers, iOS, Android). |
| [glfw](https://github.com/goxjs/glfw) | 66 | 6 | 2014-12-27 | 5 months ago | Go cross-platform glfw library for creating an OpenGL context and receiving events. |
| [go-glmatrix](https://github.com/technohippy/go-glmatrix) | 1 | 1 | 2020-07-02 | 1 month ago | Go port of [glMatrix](http://glmatrix.net/) library. |

## ORM
        
*Libraries that implement Object-Relational Mapping or datamapping techniques.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [xorm](https://github.com/go-xorm/xorm) | 6158 | 263 | 2013-05-09 | 5 months ago | Simple and powerful ORM for Go. |
| [ent](https://github.com/facebook/ent) | 4717 | 102 | 2019-06-12 | 2 hours ago | An entity framework for Go. Simple, yet powerful ORM for modeling and querying data. |
| [pg](https://github.com/go-pg/pg) | 4009 | 87 | 2013-04-24 | 10 hours ago | PostgreSQL ORM with focus on PostgreSQL specific features and performance. |
| [gorp](https://github.com/go-gorp/gorp) | 3413 | 115 | 2012-01-04 | 2 months ago | Go Relational Persistence, ORM-ish library for Go. |
| [sqlboiler](https://github.com/volatiletech/sqlboiler) | 3324 | 78 | 2016-02-21 | 4 days ago | ORM generator. Generate a featureful and blazing-fast ORM tailored to your database schema. |
| [ent](https://github.com/facebookincubator/ent) | 3067 | 65 | 2019-06-12 | 2 weeks ago | An entity framework for Go. Simple, yet powerful ORM for modeling and querying data. |
| [db](https://github.com/upper/db) | 2247 | 59 | 2013-10-23 | 2 days ago | Single interface for interacting with different data sources through the use of adapters that wrap mature database drivers. |
| [reform](https://github.com/go-reform/reform) | 1008 | 26 | 2016-02-25 | 1 day ago | Better ORM for Go, based on non-empty interfaces and code generation. |
| [pop](https://github.com/gobuffalo/pop) | 948 | 24 | 2018-02-07 | 2 weeks ago | Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite. |
| [gormt](https://github.com/xxjwxc/gormt) | 715 | 16 | 2019-05-05 | 1 week ago | Mysql database to golang gorm struct. |
| [go-queryset](https://github.com/jirfag/go-queryset) | 559 | 20 | 2017-09-03 | 1 month ago | 100% type-safe ORM with code generation and MySQL, PostgreSQL, Sqlite3, SQL Server support based on GORM. |
| [qbs](https://github.com/coocood/qbs) | 553 | 45 | 2013-02-02 | 3 years ago | Stands for Query By Struct. A Go ORM. |
| [go-sqlbuilder](https://github.com/huandu/go-sqlbuilder) | 414 | 15 | 2017-12-27 | 2 days ago | A flexible and powerful SQL string builder library plus a zero-config ORM. |
| [zoom](https://github.com/albrow/zoom) | 265 | 17 | 2013-07-17 | 3 months ago | Blazing-fast datastore and querying engine built on Redis. |
| [rel](https://github.com/Fs02/rel) | 178 | 6 | 2019-10-06 | 5 hours ago | Golang SQL Repository Layer for Clean (Onion) Architecture. |
| [grimoire](https://github.com/Fs02/grimoire) | 142 | 5 | 2018-03-05 | 1 month ago | Grimoire is a database access layer and validation for golang. (Support: MySQL, PostgreSQL and SQLite3). |
| [gorm](https://github.com/jinzhu/gorm) | 122 | 10 | 2013-10-25 | 2 days ago | The fantastic ORM library for Golang, aims to be developer friendly. |
| [gosql](https://github.com/rushteam/gosql) | 113 | 6 | 2020-04-27 | 1 week ago | A easy ORM for mysql. |
| [go-store](https://github.com/gosuri/go-store) | 99 | 9 | 2015-03-22 | 3 years ago | Simple and fast Redis backed key-value store library for Go. |
| [marlow](https://github.com/dadleyy/marlow) | 83 | 5 | 2017-09-15 | 2 weeks ago | Generated ORM from project structs for compile time safety assurances. |
| [go-firestorm](https://github.com/jschoedt/go-firestorm) | 15 | 1 | 2018-12-04 | 1 month ago | A simple ORM for Google/Firebase Cloud Firestore. |
| [lore](https://github.com/abrahambotros/lore) | 6 | 1 | 2017-04-29 | 2 years ago | Simple and lightweight pseudo-ORM/pseudo-struct-mapping environment for Go. |
| [marlow](https://github.com/marlow/marlow) | 1 | 2 | 2020-08-11 | 2 weeks ago | Generated ORM from project structs for compile time safety assurances. |

## Package Management
        
*Unofficial libraries for package and dependency management.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [dep](https://github.com/golang/dep) | 13251 | 285 | 2016-10-07 | 1 week ago | Go dependency tool. |
| [glide](https://github.com/Masterminds/glide) | 8043 | 192 | 2014-07-09 | 4 months ago | Manage your golang vendor and vendored packages with ease. Inspired by tools like Maven, Bundler, and Pip. |
| [godep](https://github.com/tools/godep) | 5629 | 147 | 2013-05-01 | 2 years ago | dependency tool for go, godep helps build packages reproducibly by fixing their dependencies. |
| [govendor](https://github.com/kardianos/govendor) | 5011 | 101 | 2015-04-12 | 6 months ago | Go Package Manager. Go vendor tool that works with the standard vendor file. |
| [gopm](https://github.com/gpmgo/gopm) | 2490 | 84 | 2013-05-15 | 1 year ago | Go Package Manager. |
| [gom](https://github.com/mattn/gom) | 1382 | 36 | 2013-09-11 | 1 year ago | Go Manager - bundle for go. |
| [gpm](https://github.com/pote/gpm) | 1202 | 31 | 2013-09-05 | 2 years ago | Barebones dependency manager for Go. |
| [goop](https://github.com/petejkim/goop) | 779 | 37 | 2014-06-18 | 4 years ago | Simple dependency manager for Go (golang), inspired by Bundler. |
| [nut](https://github.com/jingweno/nut) | 242 | 6 | 2015-01-23 | 5 years ago | Vendor Go dependencies. |
| [johnny-deps](https://github.com/VividCortex/johnny-deps) | 215 | 20 | 2013-07-19 | 2 months ago | Minimal dependency version using Git. |
| [gigo](https://github.com/LyricalSecurity/gigo) | 199 | 5 | 2015-05-01 | 1 year ago | PIP-like dependency tool for golang, with support for private repositories and hashes. |
| [VenGO](https://github.com/DamnWidget/VenGO) | 120 | 10 | 2014-10-17 | 4 years ago | create and manage exportable isolated go virtual environments. |
| [mvn-golang](https://github.com/raydac/mvn-golang) | 107 | 10 | 2016-03-24 | 2 weeks ago | plugin that provides way for auto-loading of Golang SDK, dependency management and start build environment in Maven project infrastructure. |
| [gop](https://github.com/lunny/gop) | 50 | 7 | 2017-02-18 | 1 year ago | Build and manage your Go applications out of GOPATH. |

## Performance
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [jaeger](https://github.com/jaegertracing/jaeger) | 11643 | 334 | 2016-04-15 | 55 minutes ago | A distributed tracing system. |
| [profile](https://github.com/pkg/profile) | 1291 | 39 | 2014-10-22 | 2 months ago | Simple profiling support package for Go. |
| [pixie](https://github.com/pixie-labs/pixie) | 114 | 24 | 2020-02-27 | 4 days ago | No instrumentation tracing for Golang applications via eBPF. |
| [tracer](https://github.com/kamilsk/tracer) | 34 | 2 | 2019-06-22 | 2 months ago | Simple, lightweight tracing. |

## Query Language
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [graphql](https://github.com/graphql-go/graphql) | 6764 | 148 | 2015-07-19 | 1 week ago | Implementation of GraphQL for Go. |
| [graphql-go](https://github.com/graph-gophers/graphql-go) | 3437 | 89 | 2016-10-18 | 1 week ago | GraphQL server with a focus on ease of use. |
| [gojsonq](https://github.com/thedevsaddam/gojsonq) | 1493 | 32 | 2018-05-19 | 5 months ago | A simple Go package to Query over JSON Data. |
| [jsonql](https://github.com/elgs/jsonql) | 236 | 8 | 2015-12-29 | 5 months ago | JSON query expression library in Golang. |
| [rql](https://github.com/a8m/rql) | 165 | 7 | 2018-06-05 | 5 days ago | Resource Query Language for REST API. |
| [graphql](https://github.com/tmc/graphql) | 52 | 10 | 2015-04-18 | 3 years ago | graphql parser + utilities. |
| [jsonslice](https://github.com/bhmj/jsonslice) | 47 | 0 | 2018-05-02 | 3 months ago | Jsonpath queries with advanced filters. |
| [straf](https://github.com/SonicRoshan/straf) | 19 | 1 | 2019-08-16 | 3 months ago | Easily Convert Golang structs to GraphQL objects. |
| [api-fu](https://github.com/ccbrown/api-fu) | 13 | 2 | 2019-07-30 | 1 month ago | Comprehensive GraphQL implementation. |
| [rest-query-parser](https://github.com/timsolov/rest-query-parser) | 10 | 1 | 2020-02-10 | 3 months ago | Query Parser for REST API. Filtering, validations, both `AND`, `OR` operations are supported directly in the query. |
| [gws](https://github.com/Zaba505/gws) | 3 | 1 | 2020-06-08 | 1 month ago | Apollos' "GraphQL over Websocket" client and server implementation. |

## Resource Embedding
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [packr](https://github.com/gobuffalo/packr) | 2959 | 45 | 2017-03-15 | 3 months ago | The simple and easy way to embed static files into Go binaries. |
| [statik](https://github.com/rakyll/statik) | 2880 | 47 | 2014-02-04 | 3 months ago | Embeds static files into a Go executable. |
| [go.rice](https://github.com/GeertJohan/go.rice) | 2039 | 52 | 2013-10-23 | 1 month ago | go.rice is a Go package that makes working with resources such as html,js,css,images and templates very easy. |
| [vfsgen](https://github.com/shurcooL/vfsgen) | 872 | 22 | 2015-05-18 | 1 week ago | Generates a vfsdata.go file that statically implements the given virtual filesystem. |
| [esc](https://github.com/mjibson/esc) | 571 | 15 | 2014-01-26 | 9 months ago | Embeds files into Go programs and provides http.FileSystem interfaces to them. |
| [fileb0x](https://github.com/UnnoTed/fileb0x) | 560 | 16 | 2016-01-23 | 3 weeks ago | Simple tool to embed files in go with focus on "customization" and ease to use. |
| [go-resources](https://github.com/omeid/go-resources) | 169 | 8 | 2015-02-21 | 2 months ago | Unfancy resources embedding with Go. |
| [statics](https://github.com/go-playground/statics) | 59 | 3 | 2015-10-07 | 3 years ago | Embeds static resources into go files for single binary compilation + works with http.FileSystem + symlinks. |
| [templify](https://github.com/wlbr/templify) | 25 | 2 | 2016-05-22 | 1 year ago | Embed external template files into Go code to create single file binaries. |
| [go-embed](https://github.com/pyros2097/go-embed) | 24 | 2 | 2015-12-06 | 3 months ago | Generates go code to embed resource files into your library or executable. |
| [mule](https://github.com/wlbr/mule) | 9 | 1 | 2020-01-17 | 3 weeks ago | Embed external resources like images, movies ... into Go source code to create single file binaries using `go generate`. Focussed on simplicity. |

## Science and Data Analysis
        
*Libraries for scientific computing and data analyzing.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gonum](https://github.com/gonum/gonum) | 4118 | 109 | 2017-03-25 | 1 day ago | Gonum is a set of numeric libraries for the Go programming language. It contains libraries for matrices, statistics, optimization, and more. |
| [stats](https://github.com/montanaflynn/stats) | 1806 | 52 | 2014-12-16 | 6 months ago | Statistics package with common functions missing from the Golang standard library. |
| [plot](https://github.com/gonum/plot) | 1676 | 60 | 2013-07-23 | 4 days ago | gonum/plot provides an API for building and drawing plots in Go. |
| [gosl](https://github.com/cpmech/gosl) | 1500 | 69 | 2015-02-09 | 1 week ago | Go scientific library for linear algebra, FFT, geometry, NURBS, numerical methods, probabilities, optimisation, differential equations, and more. |
| [streamtools](https://github.com/nytlabs/streamtools) | 1315 | 72 | 2013-07-05 | 5 years ago | general purpose, graphical tool for dealing with streams of data. |
| [go-dsp](https://github.com/mjibson/go-dsp) | 692 | 28 | 2011-11-02 | 2 years ago | Digital Signal Processing for Go. |
| [chart](https://github.com/vdobler/chart) | 655 | 46 | 2011-06-27 | 2 months ago | Simple Chart Plotting library for Go. Supports many graphs types. |
| [goraph](https://github.com/gyuho/goraph) | 632 | 39 | 2014-02-27 | 2 years ago | Pure Go graph theory library(data structure, algorith visualization). |
| [graph](https://github.com/yourbasic/graph) | 365 | 19 | 2017-04-27 | 4 days ago | Library of basic graph algorithms. |
| [dataframe-go](https://github.com/rocketlaunchr/dataframe-go) | 318 | 17 | 2018-10-01 | 2 days ago | Dataframes for machine-learning and statistics (similar to pandas). |
| [orb](https://github.com/paulmach/orb) | 318 | 19 | 2016-03-28 | 3 weeks ago | 2D geometry types with clipping, GeoJSON and Mapbox Vector Tile support. |
| [ewma](https://github.com/VividCortex/ewma) | 309 | 23 | 2013-07-05 | 1 month ago | Exponentially-weighted moving averages. |
| [calendarheatmap](https://github.com/nikolaydubina/calendarheatmap) | 226 | 6 | 2020-07-01 | 1 month ago | Calendar heatmap in plain Go inspired by Github contribution activity. |
| [gohistogram](https://github.com/VividCortex/gohistogram) | 146 | 15 | 2013-07-02 | 2 months ago | Approximate histograms for data streams. |
| [TextRank](https://github.com/DavidBelicza/TextRank) | 113 | 6 | 2018-01-09 | 5 months ago | TextRank implementation in Golang with extendable features (summarization, weighting, phrase extraction) and multithreading (goroutine) support. |
| [sparse](https://github.com/james-bowman/sparse) | 99 | 7 | 2017-05-16 | 2 weeks ago | Go Sparse matrix formats for linear algebra supporting scientific and machine learning applications, compatible with gonum matrix libraries. |
| [pagerank](https://github.com/alixaxel/pagerank) | 59 | 6 | 2015-08-06 | 4 months ago | Weighted PageRank algorithm implemented in Go. |
| [geom](https://github.com/skelterjohn/geom) | 45 | 4 | 2011-06-07 | 2 years ago | 2D geometry for golang. |
| [evaler](https://github.com/soniah/evaler) | 42 | 4 | 2012-09-04 | 2 years ago | Simple floating point arithmetic expression evaluator. |
| [goent](https://github.com/kzahedi/goent) | 21 | 1 | 2017-08-08 | 1 year ago | GO Implementation of Entropy Measures. |
| [decimal](https://github.com/db47h/decimal) | 19 | 1 | 2020-05-27 | 1 month ago | Package decimal implements arbitrary-precision decimal floating-point arithmetic. |
| [triangolatte](https://github.com/tchayen/triangolatte) | 14 | 1 | 2018-07-18 | 2 weeks ago | 2D triangulation library. Allows translating lines and polygons (both based on points) to the language of GPUs. |
| [GoStats](https://github.com/OGFris/GoStats) | 12 | 2 | 2018-07-22 | 1 year ago | GoStats is an Open Source GoLang library for math statistics mostly used in Machine Learning domains, it covers most of the Statistical measures functions. |
| [ode](https://github.com/ChristopherRabotin/ode) | 11 | 3 | 2016-11-11 | 3 years ago | Ordinary differential equation (ODE) solver which supports extended states and channel-based iteration stop conditions. |
| [piecewiselinear](https://github.com/sgreben/piecewiselinear) | 11 | 2 | 2018-10-21 | 8 months ago | Tiny linear interpolation library. |
| [PiHex](https://github.com/claygod/PiHex) | 10 | 3 | 2016-07-22 | 1 month ago | Implementation of the "Bailey-Borwein-Plouffe" algorithm for the hexadecimal number Pi. |
| [assocentity](https://github.com/ndabAP/assocentity) | 6 | 1 | 2018-12-21 | 4 months ago | Package assocentity returns the average distance from words to a given entity. |
| [go-gt](https://github.com/ThePaw/go-gt) | 5 | 0 | 2015-09-14 | 5 years ago | Graph theory algorithms written in "Go" language. |
| [rootfinding](https://github.com/khezen/rootfinding) | 3 | 2 | 2018-10-30 | 5 months ago | root-finding algorithms library for finding roots of quadratic functions. |
| [bradleyterry](https://github.com/seanhagen/bradleyterry) | 2 | 1 | 2019-04-30 | 1 year ago | Provides a Bradley-Terry Model for pairwise comparisons. |

## Security
        
*Libraries that are used to help make your application more secure.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [lego](https://github.com/go-acme/lego) | 4164 | 104 | 2015-06-08 | 4 hours ago | Pure Go ACME client library and CLI tool (for use with Let's Encrypt). |
| [cameradar](https://github.com/Ullaakut/cameradar) | 2319 | 107 | 2016-05-20 | 2 weeks ago | Tool and library to remotely hack RTSP streams from surveillance cameras. |
| [memguard](https://github.com/awnumar/memguard) | 1797 | 46 | 2017-04-22 | 3 weeks ago | A pure Go library for handling sensitive values in memory. |
| [acmetool](https://github.com/hlandau/acmetool) | 1786 | 67 | 2015-11-15 | 1 month ago | ACME (Let's Encrypt) client tool with automatic renewal. |
| [secure](https://github.com/unrolled/secure) | 1542 | 36 | 2014-05-20 | 2 weeks ago | HTTP middleware for Go that facilitates some quick security wins. |
| [themis](https://github.com/cossacklabs/themis) | 1100 | 43 | 2015-05-06 | 1 hour ago | high-level cryptographic library for solving typical data security tasks (secure data storage, secure messaging, zero-knowledge proof authentication), available for 14 languages, best fit for multi-platform apps. |
| [acra](https://github.com/cossacklabs/acra) | 624 | 36 | 2016-11-14 | 3 hours ago | Network encryption proxy to protect database-based applications from data leaks: strong selective encryption, SQL injections prevention, intrusion detection system. |
| [nacl](https://github.com/kevinburke/nacl) | 486 | 12 | 2017-07-20 | 1 year ago | Go implementation of the NaCL set of API's. |
| [badactor](https://github.com/jaredfolkins/badactor) | 282 | 8 | 2014-12-12 | 3 months ago | In-memory, application-driven jailer built in the spirit of fail2ban. |
| [ssh-vault](https://github.com/ssh-vault/ssh-vault) | 255 | 10 | 2016-09-29 | 6 months ago | encrypt/decrypt using ssh keys. |
| [passlib](https://github.com/hlandau/passlib) | 235 | 10 | 2014-12-21 | 1 year ago | Futureproof password hashing library. |
| [optimus-go](https://github.com/pjebs/optimus-go) | 231 | 5 | 2015-05-05 | 4 months ago | ID hashing and Obfuscation using Knuth's Algorithm. |
| [go-yara](https://github.com/hillu/go-yara) | 178 | 18 | 2015-01-25 | 1 week ago | Go Bindings for [YARA](https://github.com/plusvic/yara), the "pattern matching swiss knife for malware researchers (and everyone else)". |
| [simple-scrypt](https://github.com/elithrar/simple-scrypt) | 163 | 7 | 2015-04-14 | 1 week ago | Scrypt package with a simple, obvious API and automatic cost calibration built-in. |
| [argon2pw](https://github.com/raja/argon2pw) | 82 | 4 | 2018-03-13 | 2 years ago | Argon2 password hash generation with constant-time password comparison. |
| [goSecretBoxPassword](https://github.com/dwin/goSecretBoxPassword) | 38 | 1 | 2017-10-19 | 1 year ago | A probably paranoid package for securely hashing and encrypting passwords. |
| [certificates](https://github.com/mvmaasakkers/certificates) | 18 | 1 | 2019-03-04 | 2 months ago | An opinionated tool for generating tls certificates. |
| [go-generate-password](https://github.com/m1/go-generate-password) | 12 | 1 | 2019-11-14 | 9 months ago | Password generator that can be used on the cli or as a library. |
| [goArgonPass](https://github.com/dwin/goArgonPass) | 12 | 2 | 2018-05-30 | 6 months ago | Argon2 password hash and verification designed to be compatible with existing Python and PHP implementations. |
| [secureio](https://github.com/xaionaro-go/secureio) | 12 | 1 | 2018-12-25 | 2 months ago | An keyexchanging+authenticating+encrypting wrapper and multiplexer for `io.ReadWriteCloser` based on XChaCha20-poly1305, ECDH and ED25519. |
| [sslmgr](https://github.com/adrianosela/sslmgr) | 9 | 2 | 2019-04-02 | 1 year ago | SSL certificates made easy with a high level wrapper around acme/autocert. |
| [argon2-hashing](https://github.com/andskur/argon2-hashing) | 9 | 1 | 2019-01-02 | 4 months ago | light wrapper around Go's argon2 package that closely mirrors with Go's standard library Bcrypt and simple-scrypt package. |
| [firewalld-rest](https://github.com/prashantgupta24/firewalld-rest) | 8 | 1 | 2020-06-12 | 1 month ago | A rest application to dynamically update firewalld rules on a linux server. |

## Serialization
        
*Libraries and tools for binary serialization.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go](https://github.com/json-iterator/go) | 8138 | 225 | 2016-11-30 | 9 hours ago | High-performance 100% compatible drop-in replacement of "encoding/json". |
| [protobuf](https://github.com/golang/protobuf) | 6972 | 218 | 2014-11-23 | 1 month ago | Go support, in the form of a library and protocol compiler plugin, for Google's protocol buffers. |
| [protobuf](https://github.com/gogo/protobuf) | 4032 | 100 | 2014-12-03 | 1 week ago | Protocol Buffers for Go with Gadgets. |
| [mapstructure](https://github.com/mitchellh/mapstructure) | 3662 | 62 | 2013-05-20 | 1 day ago | Go library for decoding generic map values into native Go structures. |
| [go](https://github.com/ugorji/go) | 1448 | 55 | 2013-05-30 | 2 months ago | High Performance, feature-Rich, idiomatic encode, decode and rpc library for msgpack, cbor and json, with runtime-based OR code-generation support. |
| [colfer](https://github.com/pascaldekloe/colfer) | 556 | 33 | 2015-09-05 | 1 month ago | Code generation for the Colfer binary format. |
| [csvutil](https://github.com/jszwec/csvutil) | 406 | 9 | 2017-10-30 | 1 month ago | High Performance, idiomatic CSV record encoding and decoding to native Go structures. |
| [go-capnproto](https://github.com/glycerine/go-capnproto) | 276 | 11 | 2013-11-07 | 7 months ago | Cap'n Proto library and parser for go. |
| [cbor](https://github.com/fxamacker/cbor) | 200 | 6 | 2019-05-15 | 1 week ago | Small, safe, and easy CBOR encoding and decoding library. |
| [php_session_decoder](https://github.com/yvasiyarov/php_session_decoder) | 140 | 9 | 2012-12-23 | 1 year ago | GoLang library for working with PHP session format and PHP Serialize/Unserialize functions. |
| [structomap](https://github.com/danhper/structomap) | 115 | 7 | 2015-05-13 | 1 year ago | Library to easily and dynamically generate maps from static structures. |
| [bambam](https://github.com/glycerine/bambam) | 60 | 4 | 2014-09-17 | 3 years ago | generator for Cap'n Proto schemas from go. |
| [asn1](https://github.com/Logicalis/asn1) | 47 | 8 | 2016-02-29 | 1 year ago | Asn.1 BER and DER encoding library for golang. |
| [binstruct](https://github.com/ghostiam/binstruct) | 21 | 1 | 2018-10-23 | 1 year ago | Golang binary decoder for mapping data into the structure. |
| [fwencoder](https://github.com/o1egl/fwencoder) | 13 | 1 | 2017-12-25 | 6 months ago | Fixed width file parser (encoding and decoding library) for Go. |
| [pletter](https://github.com/vimeda/pletter) | 11 | 0 | 2019-07-09 | 2 months ago | A standard way to wrap a proto message for message brokers. |
| [bel](https://github.com/csweichel/bel) | 10 | 2 | 2019-02-20 | 3 weeks ago | Generate TypeScript interfaces from Go structs/interfaces. Useful for JSON RPC. |
| [elastic](https://github.com/epiclabs-io/elastic) | 10 | 0 | 2020-02-25 | 6 months ago | Convert slices, maps or any other unknown value across different types at run-time, no matter what. |
| [bel](https://github.com/32leaves/bel) | 8 | 1 | 2019-02-20 | 1 year ago | Generate TypeScript interfaces from Go structs/interfaces. Useful for JSON RPC. |
| [fixedwidth](https://github.com/huydang284/fixedwidth) | 4 | 1 | 2019-08-11 | 8 months ago | Fixed-width text formatting (UTF-8 supported). |
| [go-lctree](https://github.com/sbourlon/go-lctree) | 0 | 1 | 2020-05-04 | 2 months ago | Provides a CLI and primitives to serialize and deserialize [LeetCode binary trees](https://support.leetcode.com/hc/en-us/articles/360011883654-What-does-1-null-2-3-mean-in-binary-tree-representation). |

## Server Applications
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [etcd](https://github.com/etcd-io/etcd) | 32585 | 1353 | 2013-07-06 | 13 hours ago | Highly-available key value store for shared configuration and service discovery. |
| [caddy](https://github.com/caddyserver/caddy) | 29841 | 752 | 2015-01-13 | 18 hours ago | Caddy is an alternative, HTTP/2 web server that's easy to configure and use. |
| [minio](https://github.com/minio/minio) | 23634 | 530 | 2015-01-14 | 35 minutes ago | Minio is a distributed object storage server. |
| [roadrunner](https://github.com/spiral/roadrunner) | 4499 | 157 | 2017-12-26 | 4 days ago | High-performance PHP application server, load-balancer and process manager. |
| [devd](https://github.com/cortesi/devd) | 3034 | 68 | 2015-09-27 | 4 months ago | Local webserver for developers. |
| [sftpgo](https://github.com/drakkan/sftpgo) | 1905 | 43 | 2019-07-20 | 2 hours ago | Fully featured and highly configurable SFTP server with optional FTP/S and WebDAV support. It can serve local filesystem and Cloud Storage backends such as S3 and Google Cloud Storage. |
| [algernon](https://github.com/xyproto/algernon) | 1715 | 50 | 2015-03-10 | 4 days ago | HTTP/2 web server with built-in support for Lua, Markdown, GCSS and Amber. |
| [flipt](https://github.com/markphelps/flipt) | 1292 | 16 | 2016-11-05 | 1 day ago | A self contained feature flag solution written in Go and Vue. |
| [fider](https://github.com/getfider/fider) | 1277 | 34 | 2017-01-17 | 2 weeks ago | Fider is an open platform to collect and organize customer feedback. |
| [flagr](https://github.com/checkr/flagr) | 1233 | 74 | 2017-10-03 | 1 week ago | Flagr is an open-source feature flagging and A/B testing service. |
| [trickster](https://github.com/tricksterproxy/trickster) | 1177 | 34 | 2018-03-29 | 19 hours ago | HTTP reverse proxy cache and time series accelerator. |
| [trickster](https://github.com/Comcast/trickster) | 1053 | 35 | 2018-03-29 | 5 months ago | HTTP reverse proxy cache and time series accelerator. |
| [discovery](https://github.com/bilibili/discovery) | 999 | 53 | 2018-04-20 | 5 months ago | A registry for resilient mid-tier load balancing and failover. |
| [jackal](https://github.com/ortuman/jackal) | 850 | 38 | 2017-11-13 | 17 hours ago | An XMPP server written in Go. |
| [dudeldu](https://github.com/krotik/dudeldu) | 115 | 3 | 2016-09-07 | 11 months ago | A simple SHOUTcast server. |
| [lets-proxy2](https://github.com/rekby/lets-proxy2) | 39 | 2 | 2019-04-12 | 1 month ago | Reverse proxy for handle https with issue certificates in fly from lets-encrypt. |
| [psql-streamer](https://github.com/blind-oracle/psql-streamer) | 20 | 4 | 2019-04-28 | 5 months ago | Stream database events from PostgreSQL to Kafka. |
| [nginx-prometheus](https://github.com/blind-oracle/nginx-prometheus) | 14 | 1 | 2018-10-23 | 1 year ago | Nginx log parser and exporter to Prometheus. |
| [riemann-relay](https://github.com/blind-oracle/riemann-relay) | 0 | 1 | 2019-04-23 | 10 months ago | Relay to load-balance Riemann events and/or convert them to Carbon. |

## Stream Processing
        
*Libraries and tools for stream processing and reactive programming.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-streams](https://github.com/reugn/go-streams) | 395 | 12 | 2019-04-30 | 1 week ago | Go stream processing library. |

## Template Engines
        
*Libraries and tools for templating and lexing.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gofpdf](https://github.com/jung-kurt/gofpdf) | 3613 | 96 | 2015-03-13 | 9 months ago | PDF document generator with high level support for text, drawing and images. |
| [quicktemplate](https://github.com/valyala/quicktemplate) | 1821 | 57 | 2016-03-06 | 3 weeks ago | Fast, powerful, yet easy to use template engine. Converts templates into Go code and then compiles it. |
| [pongo2](https://github.com/flosch/pongo2) | 1736 | 57 | 2013-08-23 | 3 weeks ago | Django-like template-engine for Go. |
| [hero](https://github.com/shiyanhui/hero) | 1382 | 44 | 2017-01-15 | 7 months ago | Hero is a handy, fast and powerful go template engine. |
| [mustache](https://github.com/hoisie/mustache) | 991 | 35 | 2009-12-30 | 1 month ago | Go implementation of the Mustache template language. |
| [amber](https://github.com/eknkc/amber) | 849 | 20 | 2012-10-31 | 2 years ago | Amber is an elegant templating engine for Go Programming Language It is inspired from HAML and Jade. |
| [ace](https://github.com/yosssi/ace) | 787 | 23 | 2014-07-13 | 2 years ago | Ace is an HTML template engine for Go, inspired by Slim and Jade. Ace is a refinement of Gold. |
| [gorazor](https://github.com/sipin/gorazor) | 751 | 55 | 2014-05-01 | 1 month ago | Razor view engine for Golang. |
| [jet](https://github.com/CloudyKit/jet) | 688 | 23 | 2016-03-31 | 11 hours ago | Jet template engine. |
| [ego](https://github.com/benbjohnson/ego) | 451 | 16 | 2014-02-23 | 8 months ago | Lightweight templating language that lets you write templates in Go. Templates are translated into Go and compiled. |
| [fasttemplate](https://github.com/valyala/fasttemplate) | 418 | 17 | 2015-08-19 | 2 weeks ago | Simple and fast template engine. Substitutes template placeholders up to 10x faster than [text/template](http://golang.org/pkg/text/template/). |
| [raymond](https://github.com/aymerick/raymond) | 389 | 11 | 2015-04-22 | 1 week ago | Complete handlebars implementation in Go. |
| [maroto](https://github.com/johnfercher/maroto) | 212 | 7 | 2019-05-20 | 2 months ago | A maroto way to create PDFs. Maroto is inspired in Bootstrap and uses gofpdf. Fast and simple. |
| [goview](https://github.com/foolin/goview) | 171 | 5 | 2019-04-14 | 2 weeks ago | Goview is a lightweight, minimalist and idiomatic template library based on golang html/template for building Go web application. |
| [soy](https://github.com/robfig/soy) | 151 | 13 | 2013-12-15 | 1 month ago | Closure templates (aka Soy templates) for Go, following the [official spec](https://developers.google.com/closure/templates/). |
| [liquid](https://github.com/osteele/liquid) | 106 | 6 | 2017-06-26 | 8 months ago | Go implementation of Shopify Liquid templates. |
| [kasia.go](https://github.com/ziutek/kasia.go) | 71 | 2 | 2010-12-07 | 5 years ago | Templating system for HTML and other text documents - go implementation. |
| [velvet](https://github.com/gobuffalo/velvet) | 71 | 5 | 2016-12-29 | 3 years ago | Complete handlebars implementation in Go. |
| [extemplate](https://github.com/dannyvankooten/extemplate) | 25 | 3 | 2018-08-10 | 3 months ago | Tiny wrapper around html/template to allow for easy file-based template inheritance. |
| [damsel](https://github.com/dskinner/damsel) | 24 | 4 | 2012-05-02 | 4 years ago | Markup language featuring html outlining via css-selectors, extensible via pkg html/template and others. |
| [gospin](https://github.com/m1/gospin) | 15 | 1 | 2019-02-22 | 3 months ago | Article spinning and spintax/spinning syntax engine, useful for A/B, testing pieces of text/articles and creating more natural conversations. |

## Testing
        
*Libraries for testing codebases and generating test data.*

### Testing Frameworks
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [testify](https://github.com/stretchr/testify) | 11288 | 170 | 2012-10-16 | 1 week ago | Sacred extension to the standard go testing package. |
| [go-cmp](https://github.com/google/go-cmp) | 1885 | 27 | 2017-07-07 | 1 week ago | Package for comparing Go values in tests. |
| [httpexpect](https://github.com/gavv/httpexpect) | 1469 | 37 | 2016-04-29 | 3 weeks ago | Concise, declarative, and easy to use end-to-end HTTP and REST API testing. |
| [godog](https://github.com/cucumber/godog) | 1104 | 101 | 2015-06-10 | 1 month ago | Cucumber or Behat like BDD framework for Go. |
| [godog](https://github.com/DATA-DOG/godog) | 895 | 30 | 2015-06-10 | 7 months ago | Cucumber or Behat like BDD framework for Go. |
| [goblin](https://github.com/franela/goblin) | 706 | 14 | 2013-09-19 | 6 days ago | Mocha like testing framework fo Go. |
| [baloo](https://github.com/h2non/baloo) | 689 | 11 | 2016-05-29 | 1 year ago | Expressive and versatile end-to-end HTTP API testing made easy. |
| [testfixtures](https://github.com/go-testfixtures/testfixtures) | 545 | 5 | 2016-04-05 | 2 weeks ago | A helper for Rails' like test fixtures to test database applications. |
| [go-vcr](https://github.com/dnaeon/go-vcr) | 450 | 7 | 2015-12-14 | 3 months ago | Record and replay your HTTP interactions for fast, deterministic and accurate tests. |
| [go-mutesting](https://github.com/zimmski/go-mutesting) | 352 | 7 | 2014-12-26 | 10 months ago | Mutation testing for Go source code. |
| [gofight](https://github.com/appleboy/gofight) | 329 | 11 | 2016-03-29 | 1 week ago | API Handler Testing for Golang Router framework. |
| [frisby](https://github.com/hofstadter-io/frisby) | 259 | 8 | 2015-09-15 | 6 months ago | REST API testing framework. |
| [frisby](https://github.com/verdverm/frisby) | 257 | 8 | 2015-09-15 | 6 months ago | REST API testing framework. |
| [go-carpet](https://github.com/msoap/go-carpet) | 210 | 4 | 2016-02-28 | 5 months ago | Tool for viewing test coverage in terminal. |
| [charlatan](https://github.com/percolate/charlatan) | 191 | 45 | 2017-10-06 | 1 year ago | Tool to generate fake interface implementations for tests. |
| [gotest.tools](https://github.com/gotestyourself/gotest.tools) | 169 | 6 | 2017-08-08 | 2 weeks ago | A collection of packages to augment the go testing package and support common patterns. |
| [commander](https://github.com/commander-cli/commander) | 158 | 8 | 2019-02-22 | 3 weeks ago | Tool for testing cli applications on windows, linux and osx. |
| [endly](https://github.com/viant/endly) | 156 | 15 | 2017-08-28 | 1 week ago | Declarative end to end functional testing. |
| [commander](https://github.com/SimonBaeumer/commander) | 154 | 9 | 2019-02-22 | 1 month ago | Tool for testing cli applications on windows, linux and osx. |
| [goc](https://github.com/qiniu/goc) | 150 | 7 | 2020-05-07 | 3 hours ago | Goc is a comprehensive coverage testing system for The Go Programming Language. |
| [dbcleaner](https://github.com/khaiql/dbcleaner) | 118 | 2 | 2017-01-17 | 5 months ago | Clean database for testing purpose, inspired by `database_cleaner` in Ruby. |
| [cupaloy](https://github.com/bradleyjkemp/cupaloy) | 115 | 2 | 2017-08-07 | 1 day ago | Simple snapshot testing addon for your test framework. |
| [gospec](https://github.com/luontola/gospec) | 115 | 4 | 2009-11-24 | 6 years ago | BDD-style testing framework for the Go programming language. |
| [go-testdeep](https://github.com/maxatome/go-testdeep) | 107 | 2 | 2018-05-26 | 2 weeks ago | Extremely flexible golang deep comparison, extends the go testing package. |
| [wstest](https://github.com/posener/wstest) | 78 | 2 | 2017-03-31 | 5 months ago | Websocket client for unit-testing a websocket http.Handler. |
| [embedded-postgres](https://github.com/fergusstrange/embedded-postgres) | 70 | 4 | 2019-11-16 | 2 months ago | Run a real Postgres database locally on Linux, OSX or Windows as part of another Go application or test. |
| [gospecify](https://github.com/stesla/gospecify) | 55 | 6 | 2009-11-20 | 9 years ago | This provides a BDD syntax for testing your Go code. It should be familiar to anybody who has used libraries such as rspec. |
| [restit](https://github.com/go-restit/restit) | 52 | 6 | 2014-06-25 | 10 months ago | Go micro framework to help writing RESTful API integration test. |
| [testcase](https://github.com/adamluzsi/testcase) | 48 | 4 | 2019-04-22 | 1 month ago | Idiomatic testing framework for Behavior Driven Development. |
| [jsonassert](https://github.com/kinbiko/jsonassert) | 47 | 0 | 2018-10-26 | 2 months ago | Package for verifying that your JSON payloads are serialized correctly. |
| [gomatch](https://github.com/jfilipczyk/gomatch) | 39 | 2 | 2019-01-27 | 1 year ago | library created for testing JSON against patterns. |
| [dsunit](https://github.com/viant/dsunit) | 33 | 9 | 2016-06-13 | 6 months ago | Datastore testing for SQL, NoSQL, structured files. |
| [hamcrest](https://github.com/rdrdr/hamcrest) | 27 | 3 | 2010-12-22 | 9 years ago | fluent framework for declarative Matcher objects that, when applied to input values, produce self-describing results. |
| [assert](https://github.com/go-playground/assert) | 21 | 1 | 2015-07-20 | 4 months ago | Basic Assertion Library used along side native go testing, with building blocks for custom assertions. |
| [covergates](https://github.com/covergates/covergates) | 17 | 4 | 2020-05-29 | 5 days ago | Self-hosted code coverage report review and management service. |
| [flute](https://github.com/suzuki-shunsuke/flute) | 15 | 0 | 2019-07-06 | 2 weeks ago | HTTP client testing framework. |
| [schema](https://github.com/jgroeneveld/schema) | 13 | 3 | 2015-08-13 | 10 months ago | Quick and easy expression matching for JSON schemas used in requests and responses. |
| [badio](https://github.com/cavaliercoder/badio) | 10 | 1 | 2016-02-11 | 4 years ago | Extensions to Go's `testing/iotest` package. |
| [biff](https://github.com/fulldump/biff) | 10 | 1 | 2018-03-28 | 2 weeks ago | Bifurcation testing framework, BDD compatible. |
| [gocrest](https://github.com/corbym/gocrest) | 10 | 1 | 2017-12-23 | 2 years ago | Composable hamcrest-like matchers for Go assertions. |
| [testsql](https://github.com/zhulongcheng/testsql) | 10 | 2 | 2018-09-22 | 11 months ago | Generate test data from SQL files before testing and clear it after finished. |
| [gogiven](https://github.com/corbym/gogiven) | 9 | 4 | 2017-12-31 | 2 years ago | YATSPEC-like BDD testing framework for Go. |
| [gosuite](https://github.com/pavlo/gosuite) | 9 | 1 | 2016-10-15 | 3 years ago | Brings lightweight test suites with setup/teardown facilities to `testing` by leveraging Go1.7's Subtests. |
| [tt](https://github.com/vcaesar/tt) | 9 | 1 | 2018-04-03 | 2 weeks ago | Simple and colorful test tools. |
| [trial](https://github.com/jgroeneveld/trial) | 4 | 1 | 2015-06-18 | 10 months ago | Quick and easy extendable assertions without introducing much boilerplate. |

### Mock
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [chromedp](https://github.com/chromedp/chromedp) | 5201 | 149 | 2017-01-24 | 2 days ago | a way to drive/test Chrome, Safari, Edge, Android Webviews, and other browsers supporting the Chrome Debugging Protocol. |
| [mock](https://github.com/golang/mock) | 4582 | 77 | 2015-06-12 | 3 hours ago | Mocking framework for the Go programming language. |
| [go-fuzz](https://github.com/dvyukov/go-fuzz) | 3602 | 89 | 2015-04-15 | 6 days ago | Randomized testing system. |
| [go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) | 2757 | 31 | 2014-02-07 | 2 weeks ago | Mock SQL driver for testing database interactions. |
| [selenoid](https://github.com/aerokube/selenoid) | 1695 | 96 | 2016-08-22 | 3 days ago | alternative Selenium hub server that launches browsers within containers. |
| [hoverfly](https://github.com/SpectoLabs/hoverfly) | 1626 | 62 | 2015-11-30 | 1 day ago | HTTP(S) proxy for recording and simulating REST/SOAP APIs with extensible middleware and easy-to-use CLI. |
| [gock](https://github.com/h2non/gock) | 1058 | 17 | 2016-03-02 | 3 months ago | Versatile HTTP mocking made easy. |
| [httpmock](https://github.com/jarcoal/httpmock) | 888 | 10 | 2014-02-24 | 2 weeks ago | Easy mocking of HTTP responses from external resources. |
| [gofuzz](https://github.com/google/gofuzz) | 855 | 24 | 2014-07-31 | 5 days ago | Library for populating go objects with random values. |
| [rod](https://github.com/go-rod/rod) | 723 | 18 | 2020-01-21 | 1 day ago | A Devtools driver to make web automation and scraping easy. |
| [cdp](https://github.com/mafredri/cdp) | 465 | 18 | 2017-03-12 | 2 months ago | Type-safe bindings for the Chrome Debugging Protocol that can be used with browsers or other debug targets that implement it. |
| [counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) | 432 | 6 | 2014-05-21 | 2 months ago | Tool for generating self-contained mock objects. |
| [minimock](https://github.com/gojuno/minimock) | 323 | 10 | 2016-08-03 | 2 months ago | Mock generator for Go interfaces. |
| [go-txdb](https://github.com/DATA-DOG/go-txdb) | 297 | 6 | 2015-07-08 | 1 week ago | Single transaction based database driver mainly for testing purposes. |
| [rod](https://github.com/ysmood/rod) | 273 | 8 | 2020-01-21 | 2 months ago | A chrome devtools controller that is easy and safe to use. |
| [ggr](https://github.com/aerokube/ggr) | 260 | 26 | 2016-06-16 | 3 days ago | a lightweight server that routes and proxies Selenium WebDriver requests to multiple Selenium hubs. |
| [tavor](https://github.com/zimmski/tavor) | 222 | 12 | 2014-05-18 | 1 year ago | Generic fuzzing and delta-debugging framework. |
| [govcr](https://github.com/seborama/govcr) | 92 | 2 | 2016-07-10 | 11 months ago | HTTP mock for Golang: record and replay HTTP interactions for offline testing. |
| [timex](https://github.com/cabify/timex) | 45 | 74 | 2020-01-02 | 4 weeks ago | A test-friendly replacement for the native `time` package. |
| [mockhttp](https://github.com/tv42/mockhttp) | 22 | 1 | 2011-06-11 | 5 years ago | Mock object for Go http.ResponseWriter. |
| [go-localstack](https://github.com/elgohr/go-localstack) | 3 | 1 | 2020-03-18 | 20 hours ago | Tool for using localstack in AWS testing. |

### Fail injection
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [failpoint](https://github.com/pingcap/failpoint) | 530 | 79 | 2019-04-02 | 2 months ago | An implementation of [failpoints](http://www.freebsd.org/cgi/man.cgi?query=fail) for Golang. |

## Text Processing
        
*Libraries for parsing and manipulating texts.*

### Specific Formats
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [colly](https://github.com/gocolly/colly) | 11787 | 293 | 2017-09-29 | 1 day ago | Fast and Elegant Scraping Framework for Gophers. |
| [goquery](https://github.com/PuerkitoBio/goquery) | 9209 | 268 | 2012-08-29 | 1 month ago | GoQuery brings a syntax and a set of features similar to jQuery to the Go language. |
| [blackfriday](https://github.com/russross/blackfriday) | 4460 | 92 | 2011-05-27 | 3 weeks ago | Markdown processor in Go. |
| [toml](https://github.com/BurntSushi/toml) | 3308 | 87 | 2013-02-26 | 3 weeks ago | TOML configuration format (encoder/decoder with reflection). |
| [sh](https://github.com/mvdan/sh) | 3103 | 51 | 2016-01-16 | 2 days ago | Shell parser and formatter. |
| [go-humanize](https://github.com/dustin/go-humanize) | 2316 | 33 | 2012-01-13 | 4 months ago | Formatters for time, numbers, and memory size to human readable format. |
| [bluemonday](https://github.com/microcosm-cc/bluemonday) | 1635 | 31 | 2013-11-20 | 2 weeks ago | HTML Sanitizer. |
| [gofeed](https://github.com/mmcdole/gofeed) | 1339 | 39 | 2016-01-23 | 2 days ago | Parse RSS and Atom feeds in Go. |
| [inject](https://github.com/facebookarchive/inject) | 1260 | 45 | 2013-10-21 | 1 year ago | Package inject provides a reflect based injector. |
| [go-toml](https://github.com/pelletier/go-toml) | 813 | 32 | 2013-02-24 | 1 month ago | Go library for the TOML format with query support and handy cli tools. |
| [commonregex](https://github.com/mingrammer/commonregex) | 658 | 20 | 2017-03-23 | 9 months ago | A collection of common regular expressions for Go. |
| [slug](https://github.com/gosimple/slug) | 585 | 11 | 2014-03-31 | 7 months ago | URL-friendly slugify with multiple languages support. |
| [dataflowkit](https://github.com/slotix/dataflowkit) | 413 | 19 | 2017-02-09 | 2 months ago | Web scraping Framework to turn websites into structured data. |
| [mxj](https://github.com/clbanning/mxj) | 394 | 25 | 2014-02-03 | 4 days ago | Encode / decode XML as JSON or map[string]interface{}; extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages. |
| [gographviz](https://github.com/awalterschulze/gographviz) | 385 | 13 | 2015-03-14 | 4 hours ago | Parses the Graphviz DOT language. |
| [go-runewidth](https://github.com/mattn/go-runewidth) | 284 | 11 | 2013-06-21 | 2 weeks ago | Functions to get fixed width of the character or string. |
| [gotext](https://github.com/leonelquinteros/gotext) | 274 | 6 | 2016-06-19 | 2 weeks ago | GNU gettext utilities for Go. |
| [htmlquery](https://github.com/antchfx/htmlquery) | 274 | 10 | 2017-12-05 | 3 weeks ago | An XPath query package for HTML, lets you extract data or evaluate from HTML documents by an XPath expression. |
| [goq](https://github.com/andrewstuart/goq) | 175 | 7 | 2017-02-20 | 1 year ago | Declarative unmarshaling of HTML using struct tags with jQuery syntax (uses GoQuery). |
| [goribot](https://github.com/zhshch2002/goribot) | 168 | 9 | 2019-09-08 | 1 month ago | A simple golang spider/scraping framework,build a spider in 3 lines. |
| [go-nmea](https://github.com/adrianmo/go-nmea) | 130 | 7 | 2015-07-22 | 6 days ago | NMEA parser library for the Go language. |
| [sdp](https://github.com/gortc/sdp) | 102 | 7 | 2016-05-13 | 4 months ago | SDP: Session Description Protocol [[RFC 4566](https://tools.ietf.org/html/rfc4566)]. |
| [html-to-markdown](https://github.com/JohannesKaufmann/html-to-markdown) | 99 | 6 | 2018-05-15 | 3 days ago | Convert HTML to Markdown. Even works with entire websites and can be extended through rules. |
| [go-zero-width](https://github.com/trubitsyn/go-zero-width) | 89 | 1 | 2018-06-18 | 3 weeks ago | Zero-width character detection and removal for Go. |
| [podcast](https://github.com/eduncan911/podcast) | 78 | 3 | 2017-02-02 | 3 months ago | iTunes Compliant and RSS 2. |
| [editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) | 73 | 8 | 2016-07-05 | 3 days ago | Editorconfig file parser and manipulator for Go. |
| [align](https://github.com/Guitarbum722/align) | 64 | 4 | 2017-04-29 | 9 months ago | A general purpose application that aligns text. |
| [go-slugify](https://github.com/mozillazg/go-slugify) | 64 | 2 | 2016-07-16 | 3 months ago | Make pretty slug with multiple languages support. |
| [genex](https://github.com/alixaxel/genex) | 58 | 3 | 2015-03-09 | 7 months ago | Count and expand Regular Expressions into all matching Strings. |
| [guesslanguage](https://github.com/endeveit/guesslanguage) | 48 | 1 | 2014-12-16 | 2 years ago | Functions to determine the natural language of a unicode text. |
| [go-fixedwidth](https://github.com/ianlopshire/go-fixedwidth) | 46 | 3 | 2017-11-15 | 4 months ago | Fixed-width text formatting (encoder/decoder with reflection). |
| [go-vcard](https://github.com/emersion/go-vcard) | 46 | 3 | 2017-03-21 | 3 months ago | Parse and format vCard. |
| [allot](https://github.com/sbstjn/allot) | 45 | 1 | 2016-10-16 | 1 year ago | Placeholder and wildcard text parsing for CLI tools and bots. |
| [goregen](https://github.com/zach-klippenstein/goregen) | 45 | 2 | 2014-12-27 | 11 months ago | Library for generating random strings from regular expressions. |
| [did](https://github.com/ockam-network/did) | 37 | 9 | 2018-11-02 | 1 month ago | DID (Decentralized Identifiers) Parser and Stringer in Go. |
| [gonameparts](https://github.com/polera/gonameparts) | 32 | 0 | 2015-05-17 | 1 year ago | Parses human names into individual name parts. |
| [slugify](https://github.com/avelino/slugify) | 28 | 2 | 2015-04-13 | 2 years ago | Go slugify application that handles string. |
| [codetree](https://github.com/aerogo/codetree) | 16 | 2 | 2016-11-26 | 10 months ago | Parses indented code (python, pixy, scarlet, etc.) and returns a tree structure. |
| [pagser](https://github.com/foolin/pagser) | 13 | 1 | 2020-04-19 | 3 months ago | Pagser is a simple, extensible, configurable parse and deserialize html page to struct based on goquery and struct tags for golang crawler. |
| [enca](https://github.com/endeveit/enca) | 10 | 1 | 2014-12-17 | 4 years ago | Minimal cgo bindings for [libenca](http://cihar.com/software/enca/). |
| [syndfeed](https://github.com/zhengchun/syndfeed) | 7 | 1 | 2017-04-07 | 2 years ago | A syndication feed for Atom 1.0 and RSS 2.0. |
| [bbConvert](https://github.com/CalebQ42/bbConvert) | 6 | 1 | 2016-04-15 | 4 years ago | Converts bbCode to HTML that allows you to add support for custom bbCode tags. |
| [doi](https://github.com/hscells/doi) | 5 | 1 | 2017-08-02 | 3 years ago | Document object identifier (doi) parser in Go. |
| [ltsv](https://github.com/Wing924/ltsv) | 5 | 1 | 2019-05-12 | 1 year ago | High performance [LTSV (Labeled Tab Separated Value)](http://ltsv.org/) reader for Go. |
| [encoding](https://github.com/mickep76/encoding) | 3 | 1 | 2018-04-06 | 9 months ago | Package provides a generic interface to encoders and decodersa. |

### Utility
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [xurls](https://github.com/mvdan/xurls) | 677 | 17 | 2015-01-12 | 1 month ago | Extract urls from text. |
| [gotabulate](https://github.com/bndr/gotabulate) | 246 | 7 | 2014-08-21 | 3 years ago | Easily pretty-print your tabular data with Go. |
| [radix](https://github.com/yourbasic/radix) | 161 | 5 | 2017-06-09 | 2 years ago | fast string sorting algorithm. |
| [parth](https://github.com/codemodus/parth) | 38 | 3 | 2015-04-06 | 1 year ago | URL path segmentation parsing. |
| [gofuckyourself](https://github.com/JoshuaDoes/gofuckyourself) | 27 | 2 | 2018-09-09 | 1 year ago | A sanitization-based swear filter for Go. |
| [xj2go](https://github.com/wk30/xj2go) | 20 | 2 | 2017-09-19 | 1 month ago | Convert xml or json to go struct. |
| [xj2go](https://github.com/stackerzzq/xj2go) | 19 | 2 | 2017-09-19 | 6 months ago | Convert xml or json to go struct. |
| [kace](https://github.com/codemodus/kace) | 15 | 1 | 2015-06-04 | 2 years ago | Common case conversions covering common initialisms. |
| [tagify](https://github.com/zoomio/tagify) | 12 | 1 | 2018-03-20 | 5 months ago | Produces a set of tags from given source. |
| [parseargs-go](https://github.com/txgruppi/parseargs-go) | 8 | 1 | 2016-02-24 | 3 years ago | string argument parser that understands quotes and backslashes. |
| [TySug](https://github.com/Dynom/TySug) | 7 | 1 | 2018-06-05 | 4 weeks ago | Alternative suggestions with respect to keyboard layouts. |
| [textwrap](https://github.com/isbm/textwrap) | 2 | 1 | 2019-07-26 | 1 year ago | Implementation of `textwrap` module from Python. |

## Third-party APIs
        
*Libraries for accessing third party APIs.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-github](https://github.com/google/go-github) | 6790 | 226 | 2013-05-24 | 13 hours ago | Go library for accessing the GitHub REST API v3. |
| [aws-sdk-go](https://github.com/aws/aws-sdk-go) | 6041 | 259 | 2014-12-05 | 13 hours ago | The official AWS SDK for the Go programming language. |
| [google-api-go-client](https://github.com/googleapis/google-api-go-client) | 2389 | 136 | 2014-11-24 | 2 hours ago | Auto-generated Google APIs for Go. |
| [google-cloud-go](https://github.com/googleapis/google-cloud-go) | 2307 | 228 | 2014-05-09 | 1 hour ago | Google Cloud APIs Go Client Library. |
| [discordgo](https://github.com/bwmarrin/discordgo) | 1452 | 45 | 2015-11-01 | 3 days ago | Go bindings for the Discord Chat API. |
| [stripe-go](https://github.com/stripe/stripe-go) | 1187 | 39 | 2014-06-05 | 11 hours ago | Go client for the Stripe API. |
| [minio-go](https://github.com/minio/minio-go) | 1080 | 43 | 2015-05-02 | 43 minutes ago | Minio Go Library for Amazon S3 compatible cloud storage. |
| [go-twitter](https://github.com/dghubble/go-twitter) | 1063 | 31 | 2015-04-11 | 1 month ago | Go client library for the Twitter v1.1 APIs. |
| [anaconda](https://github.com/ChimeraCoder/anaconda) | 1055 | 21 | 2013-03-04 | 2 weeks ago | Go client library for the Twitter 1.1 API. |
| [facebook](https://github.com/huandu/facebook) | 898 | 99 | 2012-07-28 | 2 days ago | Go Library that supports the Facebook Graph API. |
| [githubv4](https://github.com/shurcooL/githubv4) | 684 | 20 | 2017-05-27 | 4 weeks ago | Go library for accessing the GitHub GraphQL API v4. |
| [webhooks](https://github.com/go-playground/webhooks) | 532 | 15 | 2015-10-25 | 1 month ago | Webhook receiver for GitHub and Bitbucket. |
| [paypal](https://github.com/plutov/paypal) | 379 | 17 | 2015-10-14 | 6 days ago | Wrapper for PayPal payment API. |
| [geo-golang](https://github.com/codingsince1985/geo-golang) | 364 | 13 | 2014-12-04 | 6 days ago | Go Library to access [Google Maps](https://developers.google.com/maps/documentation/geocoding/intro), [MapQuest](http://open.mapquestapi.com/geocoding/), [Nominatim](https://developer.mapquest.com/documentation/open/nominatim-search), [OpenCage](http://geocoder.opencagedata.com/api.html), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx), [Mapbox](https://www.mapbox.com/developers/api/geocoding/), and [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) geocoding / reverse geocoding APIs. |
| [go-marathon](https://github.com/gambol99/go-marathon) | 192 | 13 | 2015-02-11 | 5 months ago | Go library for interacting with Mesosphere's Marathon PAAS. |
| [ethrpc](https://github.com/onrik/ethrpc) | 188 | 13 | 2017-01-24 | 1 week ago | Go bindings for Ethereum JSON RPC API. |
| [trello](https://github.com/adlio/trello) | 146 | 6 | 2016-09-24 | 1 month ago | Go wrapper for the Trello API. |
| [medium-sdk-go](https://github.com/Medium/medium-sdk-go) | 125 | 122 | 2015-09-26 | 1 year ago | Golang SDK for Medium's OAuth2 API. |
| [gostorm](https://github.com/jsgilmore/gostorm) | 124 | 11 | 2013-07-22 | 2 years ago | GoStorm is a Go library that implements the communications protocol required to write Storm spouts and Bolts in Go that communicate with the Storm shells. |
| [hipchat](https://github.com/daneharrigan/hipchat) | 112 | 7 | 2013-04-28 | 3 years ago | A golang package to communicate with HipChat over XMPP. |
| [go-trending](https://github.com/andygrunwald/go-trending) | 109 | 7 | 2015-07-04 | 6 months ago | Go library for accessing [trending repositories](https://github.com/trending) and [developers](https://github.com/trending/developers) at Github. |
| [hipchat](https://github.com/andybons/hipchat) | 107 | 8 | 2012-10-20 | 4 years ago | This project implements a golang client library for the Hipchat API. |
| [wit-go](https://github.com/wit-ai/wit-go) | 90 | 15 | 2018-08-20 | 3 months ago | Go client for wit.ai HTTP API. |
| [cachet](https://github.com/andygrunwald/cachet) | 83 | 8 | 2015-10-31 | 2 years ago | Go client library for [Cachet (open source status page system)](https://cachethq.io/). |
| [pushover](https://github.com/gregdel/pushover) | 75 | 3 | 2015-02-19 | 1 week ago | Go wrapper for the Pushover API. |
| [igdb](https://github.com/Henry-Sarabia/igdb) | 60 | 2 | 2017-08-24 | 6 months ago | Go client for the [Internet Game Database API](https://api.igdb.com/). |
| [clarifai-go](https://github.com/Clarifai/clarifai-go) | 58 | 36 | 2015-09-28 | 3 years ago | Go client library for interfacing with the Clarifai API. |
| [megos](https://github.com/andygrunwald/megos) | 56 | 5 | 2015-10-02 | 2 years ago | Client library for accessing an [Apache Mesos](http://mesos.apache.org/) cluster. |
| [go-circleci](https://github.com/jszwedko/go-circleci) | 53 | 3 | 2015-08-14 | 9 months ago | Go client library for interacting with CircleCI's API. |
| [gads](https://github.com/emiddleton/gads) | 48 | 7 | 2014-01-20 | 11 months ago | Google Adwords Unofficial API. |
| [gosip](https://github.com/koltyakov/gosip) | 45 | 3 | 2019-01-26 | 1 week ago | Go client library SharePoint API. |
| [simples3](https://github.com/rhnvrm/simples3) | 44 | 2 | 2018-12-06 | 4 months ago | Simple no frills AWS S3 Library using REST with V4 Signing written in Go. |
| [go-amazon-product-advertising-api](https://github.com/ngs/go-amazon-product-advertising-api) | 42 | 1 | 2016-11-15 | 2 years ago | Go Client Library for [Amazon Product Advertising API](https://affiliate-program.amazon.com/gp/advertising/api/detail/main.html). |
| [gomusicbrainz](https://github.com/michiwend/gomusicbrainz) | 42 | 7 | 2014-09-10 | 2 months ago | Go MusicBrainz WS2 client library. |
| [go-xkcd](https://github.com/nishanths/go-xkcd) | 40 | 4 | 2016-02-26 | 3 months ago | Go client for the xkcd API. |
| [fcm](https://github.com/maddevsio/fcm) | 38 | 4 | 2017-01-06 | 5 months ago | Go library for Firebase Cloud Messaging. |
| [uptimerobot](https://github.com/bitfield/uptimerobot) | 38 | 3 | 2018-05-29 | 4 months ago | Go wrapper and command-line client for the Uptime Robot v2 API. |
| [gogtrends](https://github.com/groovili/gogtrends) | 38 | 3 | 2018-12-27 | 2 months ago | Google Trends Unofficial API. |
| [golang-tmdb](https://github.com/cyruzin/golang-tmdb) | 35 | 1 | 2019-01-11 | 1 month ago | Golang wrapper for The Movie Database API v3. |
| [golyrics](https://github.com/mamal72/golyrics) | 34 | 3 | 2016-11-18 | 2 years ago | Golyrics is a Go library to fetch music lyrics data from the Wikia website. |
| [twitter-scraper](https://github.com/n0madic/twitter-scraper) | 34 | 3 | 2018-11-29 | 1 week ago | Scrape the Twitter Frontend API without authentication and limits. |
| [mixpanel](https://github.com/dukex/mixpanel) | 33 | 3 | 2014-05-20 | 7 months ago | Mixpanel is a library for tracking events and sending Mixpanel profile updates to Mixpanel from your go applications. |
| [go-unsplash](https://github.com/hbagdi/go-unsplash) | 30 | 1 | 2017-01-19 | 5 months ago | Go client library for the [Unsplash.com](https://unsplash.com) API. |
| [gcm](https://github.com/TheOrioli/gcm) | 29 | 3 | 2015-11-09 | 4 years ago | Go library for Google Cloud Messaging. |
| [translate](https://github.com/nuveo/translate) | 29 | 28 | 2015-07-13 | 4 years ago | Go online translation package. |
| [ynab.go](https://github.com/brunomvsouza/ynab.go) | 29 | 2 | 2018-07-13 | 8 months ago | Go wrapper for the YNAB API. |
| [gami](https://github.com/bit4bit/gami) | 28 | 4 | 2014-05-14 | 2 years ago | Go library for Asterisk Manager Interface. |
| [go-spotify](https://github.com/rapito/go-spotify) | 27 | 2 | 2014-10-30 | 2 years ago | Go Library to access Spotify WEB API. |
| [patreon-go](https://github.com/mxpv/patreon-go) | 21 | 4 | 2017-08-06 | 11 months ago | Go library for Patreon API. |
| [go-steam](https://github.com/sostronk/go-steam) | 21 | 10 | 2014-11-23 | 7 months ago | Go Library to interact with Steam game servers. |
| [go-shopify](https://github.com/rapito/go-shopify) | 20 | 1 | 2014-10-28 | 2 years ago | Go Library to make CRUD request to the Shopify API. |
| [go-twitch](https://github.com/knspriggs/go-twitch) | 19 | 5 | 2016-06-28 | 3 years ago | Go client for interacting with the Twitch v3 API. |
| [brewerydb](https://github.com/naegelejd/brewerydb) | 17 | 3 | 2015-04-15 | 5 years ago | Go library for accessing the BreweryDB API. |
| [go-myanimelist](https://github.com/nstratos/go-myanimelist) | 17 | 2 | 2015-05-03 | 5 days ago | Go client library for accessing the [MyAnimeList API](http://myanimelist.net/modules.php?go=api). |
| [textbelt](https://github.com/farmergreg/textbelt) | 17 | 2 | 2015-09-01 | 5 years ago | Go client for the textbelt.com txt messaging API. |
| [codeship-go](https://github.com/codeship/codeship-go) | 16 | 23 | 2017-09-08 | 1 year ago | Go client library for interacting with Codeship's API v2. |
| [airtable](https://github.com/mehanizm/airtable) | 13 | 1 | 2020-04-12 | 4 months ago | Go client library for the [Airtable API](https://airtable.com/api). |
| [coinpaprika-api-go-client](https://github.com/coinpaprika/coinpaprika-api-go-client) | 12 | 8 | 2018-09-25 | 3 months ago | Go client library for interacting with Coinpaprika's API. |
| [go-google-analytics](https://github.com/chonthu/go-google-analytics) | 12 | 2 | 2015-06-01 | 5 years ago | Simple wrapper for easy google analytics reporting. |
| [lastpass-go](https://github.com/ansd/lastpass-go) | 12 | 0 | 2019-07-11 | 1 month ago | Go client library for the [LastPass](https://www.lastpass.com/) API. |
| [go-hacknews](https://github.com/PaulRosset/go-hacknews) | 11 | 2 | 2017-08-10 | 3 years ago | Tiny Go client for HackerNews API. |
| [smitego](https://github.com/sergiotapia/smitego) | 10 | 0 | 2013-12-11 | 6 years ago | Go package to wraps access to the Smite game API. |
| [go-here](https://github.com/abdullahselek/go-here) | 9 | 1 | 2019-07-07 | 2 months ago | Go client library around the HERE location based APIs. |
| [go-sophos](https://github.com/esurdam/go-sophos) | 8 | 2 | 2018-09-05 | 10 months ago | Go client library for the [Sophos UTM REST API](https://www.sophos.com/en-us/medialibrary/PDFs/documentation/UTMonAWS/Sophos-UTM-RESTful-API.pdf?la=en) with zero dependencies. |
| [rrdaclient](https://github.com/Omie/rrdaclient) | 8 | 1 | 2014-09-15 | 6 years ago | Go Library to access statdns.com API, which is in turn RRDA API. DNS Queries over HTTP. |
| [slack](https://github.com/nlopes/slack) | 8 | 1 | 2015-01-24 | 6 months ago | Slack API in Go. |
| [go-postman-collection](https://github.com/rbretecher/go-postman-collection) | 8 | 2 | 2019-11-16 | 2 weeks ago | Go module to work with [Postman Collections](https://learning.getpostman.com/docs/postman/collections/creating-collections/) (compatible with Insomnia). |
| [go-sptrans](https://github.com/sergioaugrod/go-sptrans) | 7 | 3 | 2017-09-11 | 2 years ago | Go client library for the SPTrans Olho Vivo API. |
| [go-google-email-audit-api](https://github.com/ngs/go-google-email-audit-api) | 7 | 0 | 2016-10-24 | 3 years ago | Go client library for [Google G Suite Email Audit API](https://developers.google.com/admin-sdk/email-audit/). |
| [google-play-scraper](https://github.com/n0madic/google-play-scraper) | 7 | 1 | 2019-09-20 | 6 hours ago | Get data from Google Play Store. |
| [gumblr](https://github.com/mattcunningham/gumblr) | 6 | 1 | 2015-07-09 | 3 years ago | Go wrapper for the Tumblr v2 API. |
| [gopaapi5](https://github.com/utekaravinash/gopaapi5) | 6 | 2 | 2020-02-15 | 5 months ago | Go Client Library for [Amazon Product Advertising API 5.0](https://webservices.amazon.com/paapi5/documentation/). |
| [go-zooz](https://github.com/gojuno/go-zooz) | 5 | 15 | 2017-07-04 | 1 month ago | Go client for the Zooz API. |
| [go-chronos](https://github.com/axelspringer/go-chronos) | 3 | 9 | 2017-10-23 | 2 years ago | Go library for interacting with the [Chronos](https://mesos.github. |
| [libgoffi](https://github.com/clevabit/libgoffi) | 2 | 7 | 2019-08-03 | 1 week ago | Library adapter toolbox for native [libffi](http://sourceware. |
| [playlyfe-go-sdk](https://github.com/playlyfe/playlyfe-go-sdk) | 1 | 4 | 2015-05-25 | 4 years ago | The Playlyfe Rest API Go SDK. |
| [tripadvisor-golang](https://github.com/mrbenosborne/tripadvisor-golang) | 1 | 1 | 2019-04-15 | 10 months ago | Go wrapper for the TripAdvisor API. |
| [vl-go](https://github.com/verifid/vl-go) | 1 | 1 | 2019-02-09 | 6 months ago | Go client library around the VerifID identity verification layer API. |
| [kanka](https://github.com/Henry-Sarabia/kanka) | 0 | 1 | 2019-12-26 | 3 weeks ago | Go client for the [Kanka API](https://kanka.io/en-US/docs/1.0). |

## Utilities
        
*General utilities and tools to make your life easier.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [fzf](https://github.com/junegunn/fzf) | 31507 | 382 | 2013-10-23 | 3 days ago | Command-line fuzzy finder written in Go. |
| [hub](https://github.com/github/hub) | 20207 | 472 | 2009-12-05 | 1 week ago | wrap git commands with additional functionality to interact with github from the terminal. |
| [delve](https://github.com/go-delve/delve) | 13355 | 387 | 2014-05-20 | 6 months ago | Go debugger. |
| [ctop](https://github.com/bcicen/ctop) | 10372 | 166 | 2016-12-27 | 4 days ago | [Top-like](http://ctop.sh) interface (e.g. htop) for container metrics. |
| [wuzz](https://github.com/asciimoo/wuzz) | 9122 | 181 | 2017-01-30 | 3 weeks ago | Interactive cli tool for HTTP inspection. |
| [sqlx](https://github.com/jmoiron/sqlx) | 8899 | 183 | 2013-01-28 | 1 week ago | provides a set of extensions on top of the excellent built-in database/sql package. |
| [goreleaser](https://github.com/goreleaser/goreleaser) | 6107 | 83 | 2016-12-21 | 1 day ago | Deliver Go binaries as fast and easily as possible. |
| [peco](https://github.com/peco/peco) | 5988 | 139 | 2014-06-06 | 2 weeks ago | Simplistic interactive filtering tool. |
| [usql](https://github.com/xo/usql) | 5961 | 123 | 2017-03-02 | 1 day ago | usql is a universal command-line interface for SQL databases. |
| [godropbox](https://github.com/dropbox/godropbox) | 3902 | 246 | 2014-06-22 | 1 month ago | Common libraries for writing Go services/applications from Dropbox. |
| [realize](https://github.com/oxequa/realize) | 3774 | 71 | 2016-07-12 | 3 months ago | Go build system with file watchers and live reload. Run, build and watch file changes with custom paths. |
| [task](https://github.com/go-task/task) | 2756 | 44 | 2017-02-27 | 5 hours ago | simple "Make" alternative. |
| [hystrix-go](https://github.com/afex/hystrix-go) | 2746 | 90 | 2013-12-15 | 4 months ago | Implements Hystrix patterns of programmer-defined fallbacks aka circuit breaker. |
| [goreporter](https://github.com/360EntSecGroup-Skylar/goreporter) | 2724 | 99 | 2017-03-27 | 1 year ago | Golang tool that does static analysis, unit testing, code review and generate code quality report. |
| [panicparse](https://github.com/maruel/panicparse) | 2388 | 38 | 2015-02-02 | 1 week ago | Groups similar goroutines and colorizes stack dump. |
| [minify](https://github.com/tdewolff/minify) | 2260 | 49 | 2014-05-21 | 2 hours ago | Fast minifiers for HTML, CSS, JS, XML, JSON and SVG file formats. |
| [go-funk](https://github.com/thoas/go-funk) | 2048 | 34 | 2016-12-30 | 1 day ago | Modern Go utility library which provides helpers (map, find, contains, filter, chunk, reverse, ...). |
| [mc](https://github.com/minio/mc) | 1607 | 50 | 2015-01-16 | 22 minutes ago | Minio Client provides minimal tools to work with Amazon S3 compatible cloud storage and filesystems. |
| [storm](https://github.com/asdine/storm) | 1597 | 44 | 2016-01-10 | 1 month ago | Simple and powerful toolkit for BoltDB. |
| [mmake](https://github.com/tj/mmake) | 1515 | 28 | 2017-02-15 | 6 months ago | Modern Make. |
| [mole](https://github.com/davrodpin/mole) | 1391 | 32 | 2018-10-04 | 17 hours ago | cli app to easily create ssh tunnels. |
| [mergo](https://github.com/imdario/mergo) | 1228 | 19 | 2013-03-11 | 2 weeks ago | Helper to merge structs and maps in Golang. Useful for configuration default values, avoiding messy if-statements. |
| [spinner](https://github.com/briandowns/spinner) | 1210 | 15 | 2014-12-13 | 1 month ago | Go package to easily provide a terminal spinner with options. |
| [boilr](https://github.com/tmrts/boilr) | 1153 | 30 | 2015-12-19 | 3 months ago | Blazingly fast CLI tool for creating projects from boilerplate templates. |
| [filetype](https://github.com/h2non/filetype) | 1150 | 26 | 2015-09-24 | 3 weeks ago | Small package to infer the file type checking the magic numbers signature. |
| [circuitbreaker](https://github.com/rubyist/circuitbreaker) | 902 | 21 | 2014-07-17 | 10 months ago | Circuit Breakers in Go. |
| [jump](https://github.com/gsamokovarov/jump) | 887 | 15 | 2015-08-16 | 4 months ago | Jump helps you navigate faster by learning your habits. |
| [gtm](https://github.com/git-time-metric/gtm) | 818 | 28 | 2016-06-19 | 1 year ago | Simple, seamless, lightweight time tracking for Git. |
| [immortal](https://github.com/immortal/immortal) | 660 | 14 | 2016-06-30 | 2 months ago | \*nix cross-platform (OS agnostic) supervisor. |
| [hostctl](https://github.com/guumaster/hostctl) | 527 | 9 | 2020-03-14 | 1 month ago | A CLI tool to manage /etc/hosts with easy commands. |
| [htcat](https://github.com/htcat/htcat) | 520 | 18 | 2013-08-05 | 1 year ago | Parallel and Pipelined HTTP GET Utility. |
| [circuit](https://github.com/cep21/circuit) | 479 | 13 | 2017-12-23 | 3 months ago | An efficient and feature complete Hystrix like Go implementation of the circuit breaker pattern. |
| [go-dry](https://github.com/ungerik/go-dry) | 451 | 13 | 2014-02-28 | 2 years ago | DRY (don't repeat yourself) package for Go. |
| [godaemon](https://github.com/VividCortex/godaemon) | 447 | 29 | 2013-08-01 | 2 months ago | Utility to write daemons. |
| [gopencils](https://github.com/bndr/gopencils) | 431 | 14 | 2014-06-23 | 1 year ago | Small and simple package to easily consume REST APIs. |
| [koazee](https://github.com/wesovilabs/koazee) | 416 | 11 | 2018-11-09 | 5 months ago | Library inspired in Lazy evaluation and functional programming that takes the hassle out of working with arrays. |
| [ergo](https://github.com/cristianoliveira/ergo) | 403 | 6 | 2017-08-19 | 3 weeks ago | The management of multiple local services running over different ports made easy. |
| [request](https://github.com/mozillazg/request) | 387 | 15 | 2014-12-21 | 9 months ago | Go HTTP Requests for Humans™. |
| [go-rate](https://github.com/beefsack/go-rate) | 312 | 10 | 2014-08-25 | 4 days ago | Timed rate limiter for Go. |
| [mimetype](https://github.com/gabriel-vasile/mimetype) | 304 | 6 | 2018-07-02 | 3 days ago | Package for MIME type detection based on magic numbers. |
| [deepcopier](https://github.com/ulule/deepcopier) | 291 | 18 | 2015-07-24 | 4 months ago | Simple struct copying for Go. |
| [clockwork](https://github.com/jonboulle/clockwork) | 290 | 6 | 2014-09-09 | 1 month ago | A simple fake clock for golang. |
| [gubrak](https://github.com/novalagung/gubrak) | 272 | 5 | 2018-03-09 | 3 months ago | Golang utility library with syntactic sugar. It's like lodash, but for golang. |
| [gohper](https://github.com/cosiner/gohper) | 253 | 20 | 2015-03-23 | 3 years ago | Various tools/modules help for development. |
| [gohper](https://github.com/zhuah/gohper) | 252 | 20 | 2015-03-23 | 3 years ago | Various tools/modules help for development. |
| [retry](https://github.com/kamilsk/retry) | 248 | 3 | 2016-11-02 | 3 months ago | The most advanced functional mechanism to perform actions repetitively until successful. |
| [serve](https://github.com/syntaqx/serve) | 222 | 5 | 2019-01-10 | 1 month ago | A static http server anywhere you need. |
| [go-trigger](https://github.com/sadlil/go-trigger) | 205 | 12 | 2015-10-19 | 3 years ago | Go-lang global event triggerer, Register Events with an id and trigger the event from anywhere from your project. |
| [delve](https://github.com/derekparker/delve) | 188 | 2 | 2020-02-18 | 3 months ago | Go debugger. |
| [gotenv](https://github.com/subosito/gotenv) | 182 | 3 | 2013-08-27 | 1 week ago | Load environment variables from `.env` or any `io.Reader` in Go. |
| [util](https://github.com/shomali11/util) | 182 | 9 | 2017-05-24 | 5 months ago | Collection of useful utility functions. (strings, concurrency, manipulations, ...). |
| [go-bind-plugin](https://github.com/wendigo/go-bind-plugin) | 166 | 4 | 2016-11-08 | 1 year ago | go:generate tool for wrapping symbols exported by golang plugins (1.8 only). |
| [death](https://github.com/vrecan/death) | 160 | 4 | 2015-03-09 | 1 month ago | Managing go application shutdown with signals. |
| [rerun](https://github.com/ivpusic/rerun) | 158 | 7 | 2014-12-10 | 2 years ago | Recompiling and rerunning go apps when source changes. |
| [moldova](https://github.com/StabbyCutyou/moldova) | 154 | 5 | 2016-01-30 | 3 years ago | Utility for generating random data based on an input template. |
| [toolbox](https://github.com/viant/toolbox) | 150 | 15 | 2016-06-13 | 1 month ago | Slice, map, multimap, struct, function, data conversion utilities. Service router, macro evaluator, tokenizer. |
| [robustly](https://github.com/VividCortex/robustly) | 145 | 16 | 2013-07-08 | 2 months ago | Runs functions resiliently, catching and restarting panics. |
| [apm](https://github.com/topfreegames/apm) | 144 | 16 | 2015-11-18 | 3 years ago | Process manager for Golang applications with an HTTP API. |
| [go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) | 135 | 6 | 2015-10-12 | 11 months ago | XML Sitemap generator written in Go. |
| [chyle](https://github.com/antham/chyle) | 130 | 6 | 2016-11-17 | 1 day ago | Changelog generator using a git repository with multiple configuration possibilities. |
| [onecache](https://github.com/adelowo/onecache) | 113 | 6 | 2017-04-14 | 3 months ago | Caching library with support for multiple backend stores (Redis, Memcached, filesystem etc). |
| [lrserver](https://github.com/jaschaephraim/lrserver) | 108 | 5 | 2014-07-15 | 2 years ago | LiveReload server for Go. |
| [go-bsdiff](https://github.com/gabstv/go-bsdiff) | 106 | 1 | 2019-02-23 | 1 year ago | Pure Go bsdiff and bspatch libraries and CLI tools. |
| [cli](https://github.com/create-go-app/cli) | 87 | 5 | 2019-12-30 | 2 weeks ago | A powerful CLI for create a new production-ready project with backend (Golang), frontend (JavaScript, TypeScript) & deploy automation (Ansible, Docker) by running one command. |
| [scany](https://github.com/georgysavva/scany) | 86 | 3 | 2020-07-02 | 2 days ago | Library for scanning data from a database into Go structs and more. |
| [xferspdy](https://github.com/monmohan/xferspdy) | 82 | 4 | 2015-05-22 | 4 years ago | Xferspdy provides binary diff and patch library in golang. |
| [mssqlx](https://github.com/linxGnu/mssqlx) | 79 | 9 | 2016-12-26 | 3 months ago | Database client library, proxy for any master slave, master master structures. Lightweight and auto balancing in mind. |
| [pm](https://github.com/VividCortex/pm) | 78 | 17 | 2013-11-17 | 1 month ago | Process (i.e. goroutine) manager with an HTTP API. |
| [go-health](https://github.com/Talento90/go-health) | 76 | 2 | 2018-02-13 | 2 years ago | Health package simplifies the way you add health check to your services. |
| [nostromo](https://github.com/pokanop/nostromo) | 76 | 3 | 2019-07-13 | 2 months ago | CLI for building powerful aliases. |
| [unis](https://github.com/esemplastic/unis) | 68 | 4 | 2017-05-06 | 3 years ago | Common Architecture™ for String Utilities in Go. |
| [goseaweedfs](https://github.com/linxGnu/goseaweedfs) | 67 | 7 | 2017-07-20 | 5 months ago | SeaweedFS client library with almost full features. |
| [repeat](https://github.com/ssgreg/repeat) | 67 | 5 | 2017-11-22 | 1 month ago | Go implementation of different backoff strategies useful for retrying operations and heartbeating. |
| [netbug](https://github.com/e-dard/netbug) | 66 | 1 | 2015-03-05 | 4 years ago | Easy remote profiling of your services. |
| [multitick](https://github.com/VividCortex/multitick) | 63 | 15 | 2013-12-10 | 1 month ago | Multiplexor for aligned tickers. |
| [sorty](https://github.com/jfcg/sorty) | 61 | 2 | 2019-02-18 | 1 month ago | Fast Concurrent / Parallel Sorting. |
| [handy](https://github.com/miguelpragier/handy) | 57 | 7 | 2018-06-13 | 1 week ago | Many utilities and helpers like string handlers/formatters and validators. |
| [minquery](https://github.com/icza/minquery) | 57 | 3 | 2016-11-16 | 5 months ago | MongoDB / mgo.v2 query that supports efficient pagination (cursors to continue listing documents where we left off). |
| [countries](https://github.com/biter777/countries) | 56 | 4 | 2019-04-22 | 1 month ago | Full implementation of ISO-3166-1, ISO-4217, ITU-T E.164, Unicode CLDR and IANA ccTLD standarts. |
| [mimemagic](https://github.com/zRedShift/mimemagic) | 54 | 1 | 2018-10-11 | 1 year ago | Pure Go ultra performant MIME sniffing library/utility. |
| [go-pattern-match](https://github.com/alexpantyukhin/go-pattern-match) | 54 | 2 | 2018-12-11 | 2 months ago | Pattern matching libray. |
| [go-astitodo](https://github.com/asticode/go-astitodo) | 53 | 2 | 2016-10-17 | 2 weeks ago | Parse TODOs in your GO code. |
| [golog](https://github.com/mlimaloureiro/golog) | 50 | 3 | 2016-01-09 | 1 year ago | Easy and lightweight CLI tool to time track your tasks. |
| [goreadability](https://github.com/philipjkim/goreadability) | 50 | 6 | 2016-04-20 | 1 year ago | Webpage summary extractor using Facebook Open Graph and arc90's readability. |
| [taskctl](https://github.com/taskctl/taskctl) | 46 | 2 | 2019-11-12 | 1 month ago | Concurrent task runner. |
| [gaper](https://github.com/maxcnunes/gaper) | 44 | 0 | 2018-06-16 | 9 months ago | Builds and restarts a Go project when it crashes or some watched file changes. |
| [golarm](https://github.com/msempere/golarm) | 43 | 1 | 2015-08-14 | 5 years ago | Fire alarms with system events. |
| [intrinsic](https://github.com/mengzhuo/intrinsic) | 43 | 3 | 2017-06-13 | 3 years ago | Use x86 SIMD without writing any assembly code. |
| [pgo](https://github.com/arthurkushman/pgo) | 43 | 5 | 2018-12-26 | 3 days ago | Convenient functions for PHP community. |
| [retry](https://github.com/thedevsaddam/retry) | 43 | 1 | 2018-02-25 | 5 months ago | Simple and easy retry mechanism package for Go. |
| [copy-pasta](https://github.com/jutkko/copy-pasta) | 42 | 4 | 2017-01-28 | 2 months ago | Universal multi-workstation clipboard that uses S3 like backend for the storage. |
| [goback](https://github.com/carlescere/goback) | 42 | 1 | 2015-03-13 | 2 years ago | Go simple exponential backoff package. |
| [beyond](https://github.com/wesovilabs/beyond) | 37 | 1 | 2019-10-18 | 9 months ago | The Go tool that will drive you to the AOP world! |
| [gpath](https://github.com/tenntenn/gpath) | 37 | 3 | 2017-05-24 | 3 years ago | Library to simplify access struct fields with Go's expression in reflection. |
| [retry-go](https://github.com/rafaeljesus/retry-go) | 37 | 1 | 2017-06-09 | 1 year ago | Retrying made simple and easy for golang. |
| [dbt](https://github.com/nikogura/dbt) | 34 | 2 | 2017-11-30 | 2 months ago | A framework for running self-updating signed binaries from a central, trusted repository. |
| [scan](https://github.com/blockloop/scan) | 34 | 1 | 2017-11-27 | 1 day ago | Scan golang `sql.Rows` directly to structs, slices, or primitive types. |
| [myhttp](https://github.com/inancgumus/myhttp) | 33 | 1 | 2017-09-13 | 2 years ago | Simple API to make HTTP GET requests with timeout support. |
| [rclient](https://github.com/zpatrick/rclient) | 31 | 3 | 2017-02-28 | 9 months ago | Readable, flexible, simple-to-use client for REST APIs. |
| [slice](https://github.com/psampaz/slice) | 31 | 1 | 2019-11-26 | 4 months ago | Type-safe functions for common Go slice operations. |
| [mongo-go-pagination](https://github.com/gobeam/mongo-go-pagination) | 31 | 1 | 2020-02-04 | 1 month ago | Mongodb Pagination for official mongodb/mongo-go-driver package which supports  both normal queries and Aggregation pipelines. |
| [cmd](https://github.com/commander-cli/cmd) | 28 | 3 | 2019-09-27 | 1 month ago | Library for executing shell commands on osx, windows and linux. |
| [filter](https://github.com/gookit/filter) | 27 | 5 | 2018-09-26 | 1 day ago | provide filtering, sanitizing, and conversion of Go data. |
| [evaluator](https://github.com/nullne/evaluator) | 26 | 2 | 2017-04-27 | 2 months ago | Evaluate an expression dynamicly based on s-expression. It's simple and easy to extend. |
| [cmd](https://github.com/SimonBaeumer/cmd) | 25 | 2 | 2019-09-27 | 5 months ago | Library for executing shell commands on osx, windows and linux. |
| [generate](https://github.com/go-playground/generate) | 24 | 3 | 2015-11-15 | 3 years ago | runs go generate recursively on a specified path or environment variable and can filter by regex. |
| [go-lock](https://github.com/viney-shih/go-lock) | 24 | 0 | 2020-04-30 | 3 months ago | go-lock is a lock library implementing read-write mutex and read-write trylock without starvation. |
| [gostrutils](https://github.com/ik5/gostrutils) | 23 | 3 | 2018-09-19 | 2 weeks ago | Collections of string manipulation and conversion functions. |
| [ugo](https://github.com/alxrm/ugo) | 23 | 1 | 2016-02-17 | 4 years ago | ugo is slice toolbox with concise syntax for Go. |
| [goplaceholder](https://github.com/michiwend/goplaceholder) | 21 | 2 | 2014-10-12 | 4 years ago | a small golang lib to generate placeholder images. |
| [slicer](https://github.com/leaanthony/slicer) | 21 | 1 | 2019-01-10 | 7 months ago | Makes working with slices easier. |
| [r](https://github.com/is5/r) | 18 | 3 | 2020-02-20 | 6 months ago | Python-like `range()` experience for Go. |
| [go-httpheader](https://github.com/mozillazg/go-httpheader) | 17 | 2 | 2017-06-24 | 1 year ago | Go library for encoding structs into Header fields. |
| [ctxutil](https://github.com/posener/ctxutil) | 16 | 1 | 2018-07-30 | 6 months ago | A collection of utility functions for contexts. |
| [rerate](https://github.com/abo/rerate) | 16 | 4 | 2016-05-24 | 3 years ago | Redis-based rate counter and rate limiter for Go. |
| [structs](https://github.com/PumpkinSeed/structs) | 16 | 2 | 2017-08-26 | 2 years ago | Implement simple functions to manipulate structs. |
| [filler](https://github.com/yaronsumel/filler) | 15 | 1 | 2017-04-05 | 3 years ago | small utility to fill structs using "fill" tag. |
| [ghokin](https://github.com/antham/ghokin) | 15 | 2 | 2018-08-03 | 1 week ago | Parallelized formatter with no external dependencies for gherkin (cucumber, behat...). |
| [limiters](https://github.com/mennanov/limiters) | 15 | 1 | 2019-08-28 | 6 days ago | Rate limiters for distributed applications in Golang with configurable back-ends and distributed locks. |
| [okrun](https://github.com/xta/okrun) | 15 | 2 | 2014-10-01 | 5 years ago | go run error steamroller. |
| [equalizer](https://github.com/reugn/equalizer) | 15 | 1 | 2019-06-14 | 1 year ago | Quota manager and rate limiter collection for Go. |
| [dlog](https://github.com/kirillDanshin/dlog) | 14 | 2 | 2016-07-04 | 3 years ago | Compile-time controlled logger to make your release smaller without removing debug calls. |
| [jsend](https://github.com/clevergo/jsend) | 14 | 3 | 2020-01-14 | 14 hours ago | JSend's implementation writen in Go. |
| [rest-go](https://github.com/edermanoel94/rest-go) | 13 | 3 | 2019-07-29 | 2 weeks ago | A package that provide many helpful methods for working with rest api. |
| [command](https://github.com/txgruppi/command) | 12 | 1 | 2015-08-24 | 4 years ago | Command pattern for Go with thread safe serial and parallel dispatcher. |
| [tome](https://github.com/cyruzin/tome) | 12 | 1 | 2019-04-12 | 4 months ago | Tome was designed to paginate simple RESTful APIs. |
| [backscanner](https://github.com/icza/backscanner) | 11 | 2 | 2017-10-18 | 6 months ago | A scanner similar to bufio.Scanner, but it reads and returns lines in reverse order, starting at a given position and going backward. |
| [mimesniffer](https://github.com/aofei/mimesniffer) | 11 | 1 | 2018-12-20 | 1 week ago | A MIME type sniffer for Go. |
| [retry](https://github.com/shafreeck/retry) | 11 | 0 | 2018-07-18 | 6 months ago | A pretty simple library to ensure your work to be done. |
| [shutdown](https://github.com/ztrue/shutdown) | 10 | 1 | 2018-11-17 | 1 year ago | App shutdown hooks for `os.Signal` handling. |
| [go-convert](https://github.com/Eun/go-convert) | 8 | 0 | 2019-06-07 | 2 weeks ago | Package go-convert enbles you to convert a value into another type. |
| [go-problemdetails](https://github.com/mvmaasakkers/go-problemdetails) | 7 | 1 | 2019-05-16 | 6 months ago | Go package for working with Problem Details. |
| [retry](https://github.com/percolate/retry) | 7 | 34 | 2018-06-15 | 1 year ago | A simple but highly configurable retry package for Go. |
| [ptr](https://github.com/gotidy/ptr) | 6 | 1 | 2019-12-25 | 8 months ago | Package that provide functions for simplified creation of pointers from constants of basic types. |
| [sliceconv](https://github.com/Henry-Sarabia/sliceconv) | 6 | 1 | 2019-02-15 | 7 months ago | Slice conversion between primitive types. |
| [blank](https://github.com/Henry-Sarabia/blank) | 5 | 2 | 2019-02-13 | 1 year ago | Verify or remove blanks and whitespace from strings. |
| [silk](https://github.com/chrispassas/silk) | 4 | 1 | 2018-12-18 | 4 months ago | Read silk netflow files. |
| [nfdump](https://github.com/chrispassas/nfdump) | 2 | 1 | 2020-04-08 | 4 months ago | Read nfdump netflow files. |
| [olaf](https://github.com/btnguyen2k/olaf) | 1 | 1 | 2019-01-03 | 1 year ago | Twitter Snowflake implemented in Go. |
| [compare](https://github.com/posener/compare) | 1 | 1 | 2020-03-13 | 5 months ago | Enables more readable and easier comparison tasks. |
| [go-safe](https://github.com/kenkyu392/go-safe) | 0 | 0 | 2019-10-29 | 4 months ago | Panic-safe sandbox. |

## UUID
        
*Libraries for working with UUIDs.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [uuid](https://github.com/google/uuid) | 2075 | 48 | 2016-02-12 | 2 days ago | Go package for UUIDs based on RFC 4122 and DCE 1.1: Authentication and Security Services. |
| [ulid](https://github.com/oklog/ulid) | 2001 | 41 | 2016-12-06 | 1 day ago | Go implementation of ULID (Universally Unique Lexicographically Sortable Identifier). |
| [uuid](https://github.com/gofrs/uuid) | 825 | 19 | 2018-07-13 | 3 months ago | Implementation of Universally Unique Identifier (UUID). Supports both creation and parsing of UUIDs. Actively maintained fork of satori uuid. |
| [wuid](https://github.com/edwingeng/wuid) | 368 | 16 | 2018-01-27 | 1 week ago | An extremely fast unique number generator, 10-135 times faster than UUID. |
| [sno](https://github.com/muyo/sno) | 36 | 2 | 2019-05-26 | 4 months ago | Compact, sortable and fast unique IDs with embedded metadata. |
| [Goid](https://github.com/JakeHL/Goid) | 29 | 4 | 2017-05-19 | 1 year ago | Generate and Parse RFC4122 compliant V4 UUIDs. |
| [nanoid](https://github.com/aidarkhanov/nanoid) | 24 | 1 | 2019-07-02 | 2 months ago | A tiny and efficient Go unique string ID generator. |
| [uuid](https://github.com/agext/uuid) | 12 | 2 | 2016-02-03 | 5 months ago | Generate, encode, and decode UUIDs v1 with fast or cryptographic-quality random node identifier. |

## Validation
        
*Libraries for validation.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [validator](https://github.com/go-playground/validator) | 6058 | 97 | 2015-02-12 | 3 hours ago | Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving. |
| [govalidator](https://github.com/asaskevich/govalidator) | 4367 | 103 | 2014-06-20 | 1 week ago | Validators and sanitizers for strings, numerics, slices and structs. |
| [ozzo-validation](https://github.com/go-ozzo/ozzo-validation) | 1608 | 27 | 2016-06-22 | 2 weeks ago | Supports validation of various data types (structs, strings, maps, slices, etc.) with configurable and extensible validation rules specified in usual code constructs instead of struct tags. |
| [govalidator](https://github.com/thedevsaddam/govalidator) | 919 | 20 | 2017-09-13 | 2 weeks ago | Validate Golang request data with simple rules. Highly inspired by Laravel's request validation. |
| [validate](https://github.com/gookit/validate) | 285 | 14 | 2018-07-16 | 9 hours ago | Go package for data validation and filtering. support validate Map, Struct, Request(Form, JSON, url.Values, Uploaded Files) data and more features. |
| [checkdigit](https://github.com/osamingo/checkdigit) | 59 | 0 | 2019-04-05 | 8 months ago | Provide check digit algorithms (Luhn, Verhoeff, Damm) and calculators (ISBN, EAN, JAN, UPC, etc.). |
| [jio](https://github.com/faceair/jio) | 46 | 2 | 2018-10-28 | 3 months ago | jio is a json schema validator similar to [joi](https://github.com/hapijs/joi). |
| [validate](https://github.com/gobuffalo/validate) | 42 | 6 | 2018-02-10 | 3 weeks ago | This package provides a framework for writing validations for Go applications. |
| [gody](https://github.com/guiferpa/gody) | 35 | 0 | 2018-11-01 | 4 months ago | :balloon: A lightweight struct validator for Go. |
| [terraform-validator](https://github.com/thazelart/terraform-validator) | 34 | 2 | 2019-05-29 | 1 week ago | A norms and conventions validator for Terraform. |
| [govalid](https://github.com/twharmon/govalid) | 18 | 1 | 2019-02-17 | 1 week ago | Fast, tag-based validation for structs. |

## Version Control
        
*Libraries for version control.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-git](https://github.com/src-d/go-git) | 5023 | 101 | 2015-10-22 | 4 months ago | highly extensible Git implementation in pure Go. |
| [git2go](https://github.com/libgit2/git2go) | 1520 | 52 | 2013-03-05 | 2 weeks ago | Go bindings for libgit2. |
| [hercules](https://github.com/src-d/hercules) | 1100 | 21 | 2016-12-12 | 4 months ago | gaining advanced insights from Git repository history. |
| [gh](https://github.com/rjeczalik/gh) | 75 | 6 | 2015-03-08 | 1 year ago | Scriptable server and net/http middleware for GitHub Webhooks. |
| [go-vcs](https://github.com/sourcegraph/go-vcs) | 74 | 44 | 2013-06-02 | 3 months ago | manipulate and inspect VCS repositories in Go. |
| [hgo](https://github.com/beyang/hgo) | 13 | 3 | 2014-06-18 | 5 years ago | Hgo is a collection of Go packages providing read-access to local Mercurial repositories. |

## Video
        
*Libraries for manipulating video.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [goav](https://github.com/giorgisio/goav) | 1344 | 48 | 2015-05-21 | 5 days ago | Comphrensive Go bindings for FFmpeg. |
| [m3u8](https://github.com/grafov/m3u8) | 742 | 35 | 2013-02-05 | 2 months ago | Parser and generator library of M3U8 playlists for Apple HLS. |
| [gmf](https://github.com/3d0c/gmf) | 623 | 31 | 2013-04-03 | 2 months ago | Go bindings for FFmpeg av\* libraries. |
| [go-astits](https://github.com/asticode/go-astits) | 323 | 16 | 2017-07-04 | 2 months ago | Parse and demux MPEG Transport Streams (.ts) natively in GO. |
| [go-astisub](https://github.com/asticode/go-astisub) | 273 | 7 | 2016-12-16 | 4 hours ago | Manipulate subtitles in GO (.srt, .stl, .ttml, .webvtt, .ssa/.ass, teletext, .smi, etc.). |
| [gst](https://github.com/ziutek/gst) | 157 | 9 | 2011-07-26 | 2 years ago | Go bindings for GStreamer. |
| [libvlc-go](https://github.com/adrg/libvlc-go) | 149 | 11 | 2015-01-06 | 1 month ago | Go bindings for libvlc 2.X/3.X/4.X (used by the VLC media player). |
| [go-m3u8](https://github.com/quangngotan95/go-m3u8) | 64 | 1 | 2018-11-06 | 3 months ago | Parser and generator library for Apple m3u8 playlists. |
| [v4l](https://github.com/korandiz/v4l) | 47 | 4 | 2016-10-25 | 2 years ago | Video capture library for Linux, written in Go. |
| [libgosubs](https://github.com/wargarblgarbl/libgosubs) | 14 | 1 | 2017-05-03 | 3 months ago | Subtitle format support for go. Supports .srt, .ttml, and .ass. |
| [go-mpd](https://github.com/unki2aut/go-mpd) | 3 | 1 | 2018-11-02 | 2 weeks ago | Parser and generator library for MPEG-DASH manifest files. |

## Web Frameworks
        
*Full stack web frameworks.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gin](https://github.com/gin-gonic/gin) | 41243 | 1299 | 2014-06-16 | 15 hours ago | Gin is a web framework written in Go! It features a martini-like API with much better performance, up to 40 times faster. If you need performance and good productivity. |
| [beego](https://github.com/astaxie/beego) | 24760 | 1257 | 2012-02-29 | 40 minutes ago | beego is an open-source, high-performance web framework for the Go programming language. |
| [echo](https://github.com/labstack/echo) | 18007 | 547 | 2015-03-01 | 2 hours ago | High performance, minimalist Go web framework. |
| [revel](https://github.com/revel/revel) | 11842 | 549 | 2011-12-09 | 1 month ago | High-productivity web framework for the Go language. |
| [fiber](https://github.com/gofiber/fiber) | 7594 | 148 | 2020-01-16 | 4 hours ago | An Express.js inspired web framework build on Fasthttp. |
| [goa](https://github.com/goadesign/goa) | 3954 | 172 | 2014-12-05 | 1 week ago | Goa provides a holistic approach for developing remote APIs and microservices in Go. |
| [go-json-rest](https://github.com/ant0ine/go-json-rest) | 3430 | 160 | 2013-02-19 | 1 year ago | Quick and easy way to setup a RESTful JSON API. |
| [gizmo](https://github.com/nytimes/gizmo) | 3228 | 115 | 2015-12-15 | 6 hours ago | Microservice toolkit used by the New York Times. |
| [macaron](https://github.com/go-macaron/macaron) | 3037 | 147 | 2014-07-10 | 2 weeks ago | Macaron is a high productive and modular design web framework in Go. |
| [utron](https://github.com/gernest/utron) | 2163 | 69 | 2015-09-16 | 1 year ago | Lightweight MVC framework for Go(Golang). |
| [go-tigertonic](https://github.com/rcrowley/go-tigertonic) | 1000 | 46 | 2013-02-09 | 2 years ago | Go framework for building JSON web services inspired by Dropwizard. |
| [tango](https://github.com/lunny/tango) | 838 | 77 | 2014-12-17 | 1 year ago | Micro & pluggable web framework for Go. |
| [goyave](https://github.com/System-Glitch/goyave) | 452 | 19 | 2019-10-21 | 1 day ago | Feature-complete web framework aimed at clean code and fast development, with powerful built-in functionalities. |
| [gongular](https://github.com/mustafaakin/gongular) | 434 | 22 | 2016-06-22 | 1 month ago | Fast Go web framework with input mapping/validation and (DI) Dependency Injection. |
| [neo](https://github.com/ivpusic/neo) | 411 | 34 | 2015-02-04 | 2 years ago | Neo is minimal and fast Go Web Framework with extremely simple API. |
| [air](https://github.com/aofei/air) | 387 | 18 | 2016-07-20 | 1 week ago | An ideally refined web framework for Go. |
| [gearbox](https://github.com/gogearbox/gearbox) | 366 | 9 | 2020-04-25 | 2 weeks ago | A web framework written in Go with a focus on high performance and memory optimization. |
| [mango](https://github.com/paulbellamy/mango) | 353 | 22 | 2011-05-25 | 2 years ago | Mango is a modular web-application framework for Go, inspired by Rack, and PEP333. |
| [gondola](https://github.com/rainycape/gondola) | 313 | 15 | 2014-07-25 | 1 year ago | The web framework for writing faster sites, faster. |
| [aero](https://github.com/aerogo/aero) | 298 | 17 | 2016-11-09 | 3 months ago | High-performance web framework for Go, reaches top scores in Lighthouse. |
| [golf](https://github.com/dinever/golf) | 244 | 17 | 2015-11-18 | 3 years ago | Golf is a fast, simple and lightweight micro-web framework for Go. It comes with powerful features and has no dependencies other than the Go Standard Library. |
| [gearbox](https://github.com/abahmed/gearbox) | 176 | 4 | 2020-04-25 | 3 months ago | A web framework written in Go with a focus on high performance and memory optimization. |
| [flamingo](https://github.com/i-love-flamingo/flamingo) | 159 | 22 | 2019-04-02 | 1 day ago | Framework for pluggable web projects. Including a concept for modules and offering features for DI, Configareas, i18n, template engines, graphql, observability, security, events, routing & reverse routing etc. |
| [webgo](https://github.com/bnkamalesh/webgo) | 137 | 7 | 2015-12-16 | 1 month ago | A micro-framework to build web apps; with handler chaining, middleware and context injection. With standard library compliant HTTP handlers(i.e. http.HandlerFunc). |
| [hiboot](https://github.com/hidevopsio/hiboot) | 135 | 12 | 2018-03-16 | 1 month ago | hiboot is a high performance web application framework with auto configuration and dependency injection support. |
| [go-rest](https://github.com/ungerik/go-rest) | 120 | 10 | 2012-07-13 | 3 years ago | Small and evil REST framework for Go. |
| [ginrpc](https://github.com/xxjwxc/ginrpc) | 117 | 6 | 2019-06-22 | 3 weeks ago | Gin parameter automatic binding tool,gin rpc tools. |
| [flamingo-commerce](https://github.com/i-love-flamingo/flamingo-commerce) | 107 | 18 | 2019-04-02 | 23 hours ago | Providing e-commerce features using clean architecture like DDD and ports and adapters, that you can use to build flexible e-commerce applications. |
| [uadmin](https://github.com/uadmin/uadmin) | 107 | 8 | 2018-10-05 | 1 week ago | Fully featured web framework for Golang, inspired by Django. |
| [golax](https://github.com/fulldump/golax) | 73 | 7 | 2016-01-30 | 2 years ago | A non Sinatra fast HTTP framework with support for Google custom methods, deep interceptors, recursion and more. |
| [microservice](https://github.com/claygod/microservice) | 73 | 9 | 2016-12-15 | 1 year ago | The framework for the creation of microservices, written in Golang. |
| [vox](https://github.com/aisk/vox) | 66 | 2 | 2014-12-24 | 3 months ago | A golang web framework for humans, inspired by Koa heavily. |
| [patron](https://github.com/beatlabs/patron) | 63 | 17 | 2019-01-30 | 5 hours ago | Patron is a microservice framework following best cloud practices with a focus on productivity. |
| [yarf](https://github.com/yarf-framework/yarf) | 58 | 3 | 2015-09-02 | 1 year ago | Fast micro-framework designed to build REST APIs and web services in a fast and simple way. |
| [appy](https://github.com/appist/appy) | 54 | 3 | 2019-05-27 | 5 days ago | An opinionated productive web framework that helps scaling business easier. |
| [fireball](https://github.com/zpatrick/fireball) | 53 | 4 | 2016-07-20 | 1 year ago | More "natural" feeling web framework. |
| [rux](https://github.com/gookit/rux) | 40 | 3 | 2018-08-05 | 1 day ago | Simple and fast web framework for build golang HTTP applications. |
| [goa](https://github.com/goa-go/goa) | 34 | 2 | 2019-07-26 | 9 months ago | goa is just like koajs for golang, it is a flexible, light, high-performance and extensible web framework based on middleware. |
| [api](https://github.com/resoursea/api) | 31 | 6 | 2015-01-24 | 5 years ago | REST framework for quickly writing resource based services. |
| [rex](https://github.com/goanywhere/rex) | 30 | 1 | 2014-10-16 | 2 years ago | Rex is a library for modular development built upon gorilla/mux, fully compatible with `net/http`. |
| [banjo](https://github.com/nsheremet/banjo) | 12 | 1 | 2017-12-09 | 2 years ago | Very simple and fast web framework for Go. |
| [goweb](https://github.com/twharmon/goweb) | 6 | 1 | 2019-05-07 | 1 week ago | Web framework with routing, websockets, logging, middleware, static file server (optional gzip), and automatic TLS. |

### Middlewares
        

#### Actual middlewares
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [tollbooth](https://github.com/didip/tollbooth) | 1717 | 50 | 2015-05-17 | 3 months ago | Rate limit HTTP request handler. |
| [cors](https://github.com/rs/cors) | 1582 | 28 | 2014-10-25 | 2 months ago | Easily add CORS capabilities to your API. |
| [limiter](https://github.com/ulule/limiter) | 1020 | 25 | 2015-10-02 | 2 weeks ago | Dead simple rate limit middleware for Go. |
| [go-server-timing](https://github.com/mitchellh/go-server-timing) | 781 | 19 | 2018-02-12 | 2 months ago | Add/parse Server-Timing header. |
| [go-fault](https://github.com/github/go-fault) | 348 | 86 | 2020-05-14 | 2 weeks ago | Fault injection middleware for Go. |
| [ln-paywall](https://github.com/philippgille/ln-paywall) | 107 | 5 | 2018-06-29 | 1 year ago | Go middleware for monetizing APIs on a per-request basis with the Lightning Network (Bitcoin). |
| [xff](https://github.com/sebest/xff) | 75 | 2 | 2014-12-22 | 1 year ago | Handle `X-Forwarded-For` header and friends. |
| [formjson](https://github.com/rs/formjson) | 35 | 2 | 2015-03-19 | 4 years ago | Transparently handle JSON input as a standard form POST. |
| [client-timing](https://github.com/posener/client-timing) | 18 | 1 | 2018-02-23 | 5 months ago | An HTTP client for Server-Timing header. |

#### Libraries for creating HTTP middlewares
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [negroni](https://github.com/urfave/negroni) | 6760 | 238 | 2014-05-18 | 1 month ago | Idiomatic HTTP middleware for Golang. |
| [alice](https://github.com/justinas/alice) | 2096 | 52 | 2014-05-25 | 5 months ago | Painless middleware chaining for Go. |
| [render](https://github.com/unrolled/render) | 1385 | 39 | 2014-06-10 | 4 months ago | Go package for easily rendering JSON, XML, and HTML template responses. |
| [stats](https://github.com/thoas/stats) | 569 | 16 | 2015-03-05 | 1 year ago | Go middleware that stores various information about your web application. |
| [interpose](https://github.com/carbocation/interpose) | 289 | 12 | 2014-07-20 | 3 years ago | Minimalist net/http middleware for golang. |
| [muxchain](https://github.com/stephens2424/muxchain) | 208 | 5 | 2014-05-03 | 1 year ago | Lightweight middleware for net/http. |
| [renderer](https://github.com/thedevsaddam/renderer) | 199 | 7 | 2017-11-07 | 1 year ago | Simple, lightweight and faster response (JSON, JSONP, XML, YAML, HTML, File) rendering package for Go. |
| [rye](https://github.com/InVisionApp/rye) | 95 | 191 | 2016-10-06 | 1 year ago | Tiny Go middleware library (with canned Middlewares) that supports JWT, CORS, Statsd, and Go 1.7 context. |
| [gores](https://github.com/alioygur/gores) | 92 | 5 | 2015-12-25 | 3 months ago | Go package that handles HTML, JSON, XML and etc. responses. Useful for RESTful APIs. |
| [mediary](https://github.com/HereMobilityDevelopers/mediary) | 65 | 3 | 2020-03-23 | 2 months ago | add interceptors to `http.Client` to allow dumping/shaping/tracing/... of requests/responses. |
| [chain](https://github.com/codemodus/chain) | 64 | 6 | 2015-05-14 | 2 years ago | Handler wrapper chaining with scoped data (net/context-based "middleware"). |
| [wrap](https://github.com/go-on/wrap) | 59 | 2 | 2014-02-16 | 2 years ago | Small middlewares package for net/http. |
| [catena](https://github.com/codemodus/catena) | 7 | 1 | 2015-07-30 | 2 years ago | http.Handler wrapper catenation (same API as "chain"). |

### Routers
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [mux](https://github.com/gorilla/mux) | 12634 | 306 | 2012-10-02 | 1 day ago | Powerful URL router and dispatcher for golang. |
| [httprouter](https://github.com/julienschmidt/httprouter) | 11711 | 312 | 2013-12-05 | 1 week ago | High performance router. Use this and the standard http handlers to form a very high performance web framework. |
| [chi](https://github.com/go-chi/chi) | 8070 | 190 | 2015-10-15 | 3 weeks ago | Small, fast and expressive HTTP router built on net/context. |
| [web](https://github.com/gocraft/web) | 1425 | 59 | 2013-11-16 | 1 year ago | Mux and middleware package in Go. |
| [bone](https://github.com/go-zoo/bone) | 1261 | 36 | 2014-11-19 | 1 year ago | Lightning Fast HTTP Multiplexer. |
| [fasthttprouter](https://github.com/buaazp/fasthttprouter) | 863 | 33 | 2015-12-13 | 1 year ago | High performance router forked from `httprouter`. The first router fit for `fasthttp`. |
| [goji](https://github.com/goji/goji) | 823 | 42 | 2015-11-16 | 1 year ago | Goji is a minimalistic and flexible HTTP request multiplexer with support for `net/context`. |
| [gorouter](https://github.com/xujiajun/gorouter) | 486 | 15 | 2018-01-29 | 11 months ago | A simple and fast HTTP router for Go. |
| [httptreemux](https://github.com/dimfeld/httptreemux) | 442 | 23 | 2014-05-14 | 4 months ago | High-speed, flexible tree-based HTTP router for Go. Inspiration from httprouter. |
| [ozzo-routing](https://github.com/go-ozzo/ozzo-routing) | 387 | 28 | 2015-10-27 | 6 months ago | An extremely fast Go (golang) HTTP router that supports regular expression route matching. Comes with full support for building RESTful APIs. |
| [lars](https://github.com/go-playground/lars) | 383 | 15 | 2015-12-24 | 1 year ago | Is a lightweight, fast and extensible zero allocation HTTP router for Go used to create customizable frameworks. |
| [siesta](https://github.com/VividCortex/siesta) | 352 | 27 | 2014-09-23 | 3 weeks ago | Composable framework to write middleware and handlers. |
| [vestigo](https://github.com/husobee/vestigo) | 264 | 16 | 2015-09-22 | 11 months ago | Performant, stand-alone, HTTP compliant URL Router for go web applications. |
| [router](https://github.com/gowww/router) | 158 | 6 | 2017-05-25 | 4 months ago | Lightning fast HTTP router fully compatible with the net/http.Handler interface. |
| [alien](https://github.com/gernest/alien) | 111 | 4 | 2016-01-30 | 1 year ago | Lightweight and fast http router from outer space. |
| [pure](https://github.com/go-playground/pure) | 105 | 5 | 2016-09-23 | 2 months ago | Is a lightweight HTTP router that sticks to the std "net/http" implementation. |
| [violetear](https://github.com/nbari/violetear) | 99 | 4 | 2015-06-19 | 10 months ago | Go HTTP router. |
| [Bxog](https://github.com/claygod/Bxog) | 97 | 8 | 2016-05-19 | 2 months ago | Simple and fast HTTP router for Go. It works with routes of varying difficulty, length and nesting. And he knows how to create a URL from the received parameters. |
| [xmux](https://github.com/rs/xmux) | 88 | 6 | 2015-12-14 | 3 years ago | High performance muxer based on `httprouter` with `net/context` support. |
| [gorouter](https://github.com/vardius/gorouter) | 83 | 5 | 2016-07-14 | 3 weeks ago | GoRouter is a Server/API micro framwework, HTTP request router, multiplexer, mux that provides request router with middleware supporting `net/context`. |
| [bellt](https://github.com/GuilhermeCaruso/bellt) | 48 | 4 | 2019-02-21 | 2 months ago | A simple Go HTTP router. |
| [fastrouter](https://github.com/razonyang/fastrouter) | 19 | 2 | 2017-11-01 | 2 years ago | a fast, flexible HTTP router written in Go. |
| [route](https://github.com/goroute/route) | 7 | 3 | 2019-07-06 | 8 months ago | Simple yet powerful HTTP request multiplexer. |

## Windows
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-ole](https://github.com/go-ole/go-ole) | 658 | 38 | 2011-01-21 | 3 weeks ago | Win32 OLE implementation for golang. |
| [d3d9](https://github.com/gonutz/d3d9) | 110 | 7 | 2015-12-12 | 10 months ago | Go bindings for Direct3D9. |
| [gosddl](https://github.com/MonaxGT/gosddl) | 3 | 1 | 2018-12-04 | 1 year ago | Converter from SDDL-string to user-friendly JSON. SDDL consist of four part: Owner, Primary Group, DACL, SACL. |

## XML
        
*Libraries and tools for manipulating XML.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [zek](https://github.com/miku/zek) | 408 | 21 | 2017-11-23 | 1 month ago | Generate a Go struct from XML. |
| [xpath](https://github.com/antchfx/xpath) | 326 | 8 | 2016-10-09 | 1 month ago | XPath package for Go. |
| [xquery](https://github.com/antchfx/xquery) | 154 | 11 | 2016-10-09 | 2 years ago | XQuery lets you extract data from HTML/XML documents using XPath expression. |
| [xml2map](https://github.com/sbabiv/xml2map) | 24 | 1 | 2018-08-06 | 6 months ago | XML to MAP converter written Golang. |
| [XML-Comp](https://github.com/XML-Comp/XML-Comp) | 16 | 1 | 2016-10-25 | 2 years ago | Simple command line XML comparer that generates diffs of folders, files and tags. |
| [xmlwriter](https://github.com/shabbyrobe/xmlwriter) | 11 | 2 | 2017-04-11 | 6 months ago | Procedural XML generation API based on libxml2's xmlwriter module. |

## WebAssembly
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [tinygo](https://github.com/tinygo-org/tinygo) | 6763 | 146 | 2018-06-07 | 7 hours ago | Go compiler for small places. Microcontrollers, WebAssembly, and command-line tools. Based on LLVM. |
| [dom](https://github.com/dennwc/dom) | 408 | 15 | 2018-06-30 | 11 months ago | DOM library. |
| [go-canvas](https://github.com/markfarnan/go-canvas) | 87 | 6 | 2019-05-05 | 1 month ago | Library to use HTML5 Canvas, with all drawing within go code. |
| [webapi](https://github.com/gowebapi/webapi) | 63 | 3 | 2019-02-08 | 5 months ago | Bindings for DOM and HTML generated from WebIDL. |
| [wasmbrowsertest](https://github.com/agnivade/wasmbrowsertest) | 53 | 3 | 2018-07-14 | 3 months ago | Run Go WASM tests in your browser. |
| [vert](https://github.com/norunners/vert) | 43 | 4 | 2018-03-25 | 2 weeks ago | Interop between Go and JS values. |

## Files
        

## File Handling
        
*Libraries for handling files and file systems.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [afero](https://github.com/spf13/afero) | 3181 | 98 | 2014-10-28 | 1 week ago | FileSystem Abstraction System for Go. |
| [pdfcpu](https://github.com/pdfcpu/pdfcpu) | 1659 | 40 | 2017-06-18 | 1 day ago | PDF processor. |
| [notify](https://github.com/rjeczalik/notify) | 580 | 27 | 2014-09-08 | 1 month ago | File system event notification library with simple API, similar to os/signal. |
| [copy](https://github.com/otiai10/copy) | 187 | 5 | 2017-09-01 | 3 months ago | Copy directory recursively. |
| [bigfile](https://github.com/bigfile/bigfile) | 149 | 14 | 2019-07-15 | 6 months ago | A file transfer system, support to manage files with http api, rpc call and ftp client. |
| [go-csv-tag](https://github.com/artonge/go-csv-tag) | 74 | 1 | 2017-06-18 | 2 months ago | Load csv file using tag. |
| [afs](https://github.com/viant/afs) | 71 | 10 | 2019-08-19 | 1 month ago | Abstract File Storage (mem, scp, zip, tar, cloud: s3, gs) for Go. |
| [opc](https://github.com/qmuntal/opc) | 64 | 1 | 2018-11-06 | 1 month ago | Load Open Packaging Conventions (OPC) files for Go. |
| [vfs](https://github.com/C2FO/vfs) | 59 | 20 | 2017-08-01 | 1 month ago | A pluggable, extensible, and opinionated set of filesystem functionality for Go across a number of filesystem types such as os, S3, and GCS. |
| [skywalker](https://github.com/dixonwille/skywalker) | 57 | 4 | 2017-08-01 | 3 years ago | Package to allow one to concurrently go through a filesystem with ease. |
| [tarfs](https://github.com/posener/tarfs) | 42 | 2 | 2017-03-10 | 5 months ago | Implementation of the [`FileSystem` interface](https://godoc.org/github.com/kr/fs#FileSystem) for tar files. |
| [go-exiftool](https://github.com/barasher/go-exiftool) | 40 | 2 | 2019-05-12 | 6 days ago | Go bindings for ExifTool, the well-known library used to extract as much metadata as possible (EXIF, IPTC, ...) from files (pictures, PDF, office, ...). |
| [checksum](https://github.com/codingsince1985/checksum) | 23 | 1 | 2014-11-05 | 1 week ago | Compute message digest, like MD5 and SHA256, for large files. |
| [go-gtfs](https://github.com/artonge/go-gtfs) | 21 | 2 | 2017-07-09 | 2 months ago | Load gtfs files in go. |
| [flop](https://github.com/homedepot/flop) | 16 | 16 | 2019-03-01 | 1 month ago | File operations library which aims to mirror feature parity with [GNU cp](https://www.gnu.org/software/coreutils/manual/html_node/cp-invocation.html). |
| [gut](https://github.com/1set/gut) | 14 | 1 | 2019-10-05 | 1 month ago | Simple and reliable package for file operations like copy/move/diff/list on files, directories and symbolic links. |
| [go-decent-copy](https://github.com/hugocarreira/go-decent-copy) | 13 | 2 | 2018-10-16 | 8 months ago | Copy files for humans. |
| [parquet](https://github.com/parsyl/parquet) | 7 | 4 | 2019-01-29 | 10 months ago | Read and write [parquet](https://parquet.apache.org) files. |
| [baraka](https://github.com/xis/baraka) | 6 | 1 | 2020-07-12 | 4 days ago | A library for handling file uploads, simple, memory-friendly. |

# Tools
        
*Go software and plugins.*

## Code Analysis
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [lint](https://github.com/golang/lint) | 3643 | 111 | 2013-06-02 | 1 month ago | Golint is a linter for Go source code. |
| [errcheck](https://github.com/kisielk/errcheck) | 1562 | 25 | 2013-02-24 | 1 day ago | Errcheck is a program for checking for unchecked errors in Go programs. |
| [gcvis](https://github.com/davecheney/gcvis) | 986 | 35 | 2014-07-10 | 1 year ago | Visualise Go program GC trace data in real time. |
| [go-critic](https://github.com/go-critic/go-critic) | 776 | 22 | 2018-05-05 | 3 days ago | source code linter that brings checks that are currently not implemented in other linters. |
| [php-parser](https://github.com/z7zmey/php-parser) | 761 | 26 | 2017-11-07 | 1 hour ago | A Parser for PHP written in Go. |
| [goast-viewer](https://github.com/yuroyoro/goast-viewer) | 463 | 16 | 2014-06-30 | 1 year ago | Web based Golang AST visualizer. |
| [go-mod-outdated](https://github.com/psampaz/go-mod-outdated) | 430 | 8 | 2019-04-19 | 1 month ago | An easy way to find outdated dependencies of your Go projects. |
| [go-cleanarch](https://github.com/roblaszczak/go-cleanarch) | 351 | 10 | 2017-04-12 | 4 months ago | go-cleanarch was created to validate Clean Architecture rules, like a The Dependency Rule and interaction between packages in your Go projects. |
| [unconvert](https://github.com/mdempsky/unconvert) | 300 | 8 | 2016-02-19 | 3 months ago | Remove unnecessary type conversions from Go source. |
| [gostatus](https://github.com/shurcooL/gostatus) | 243 | 6 | 2013-11-27 | 1 year ago | Command line tool, shows the status of repositories that contain Go packages. |
| [dupl](https://github.com/mibk/dupl) | 213 | 7 | 2015-05-20 | 1 year ago | Tool for code clone detection. |
| [goplantuml](https://github.com/jfeliu007/goplantuml) | 213 | 8 | 2019-05-26 | 1 week ago | Library and CLI that generates text plantump class diagram containing information about structures and interfaces with the relationship among them. |
| [tickgit](https://github.com/augmentable-dev/tickgit) | 213 | 7 | 2019-10-12 | 2 months ago | CLI and go package for surfacing code comment TODOs (in any language) and applying a `git blame`to identify the author. |
| [apicompat](https://github.com/bradleyfalzon/apicompat) | 172 | 8 | 2016-07-10 | 3 years ago | Checks recent changes to a Go project for backwards incompatible changes. |
| [checkstyle](https://github.com/qiniu/checkstyle) | 107 | 11 | 2014-01-01 | 8 months ago | checkstyle is a style check tool like java checkstyle. This tool inspired by java checkstyle, golint. The style referred to some points in Go Code Review Comments. |
| [lint](https://github.com/surullabs/lint) | 65 | 5 | 2016-07-09 | 1 year ago | Run linters as part of go test. |
| [golines](https://github.com/segmentio/golines) | 64 | 14 | 2019-10-01 | 1 week ago | Formatter that automatically shortens long lines in Go code. |
| [validate](https://github.com/mccoyst/validate) | 60 | 6 | 2013-11-22 | 4 years ago | Automatically validates struct fields with tags. |
| [go-outdated](https://github.com/firstrow/go-outdated) | 44 | 1 | 2015-06-29 | 1 year ago | Console application that displays outdated packages. |
| [blanket](https://github.com/verygoodsoftwarenotvirus/blanket) | 14 | 2 | 2017-09-04 | 2 years ago | tarp finds functions and methods without direct unit tests in Go source code. |

## Editor Plugins
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [vim-go](https://github.com/fatih/vim-go) | 12531 | 295 | 2014-03-24 | 14 hours ago | Go development plugin for Vim. |
| [vscode-go](https://github.com/microsoft/vscode-go) | 5980 | 226 | 2015-10-14 | 2 months ago | Extension for Visual Studio Code (VS Code) which provides support for the Go language. |
| [gocode](https://github.com/nsf/gocode) | 4872 | 194 | 2010-07-05 | 15 hours ago | Autocompletion daemon for the Go programming language. |
| [GoSublime](https://github.com/DisposaBoy/GoSublime) | 3368 | 124 | 2011-08-27 | 1 month ago | Golang plugin collection for the text editor SublimeText 3 providing code completion and other IDE-like features. |
| [go-plus](https://github.com/joefitzgerald/go-plus) | 1508 | 46 | 2014-03-13 | 5 days ago | Go (Golang) Package For Atom That Adds Autocomplete, Formatting, Syntax Checking, Linting and Vetting. |
| [go-mode.el](https://github.com/dominikh/go-mode.el) | 1095 | 52 | 2013-01-30 | 1 week ago | Go mode for GNU/Emacs. |
| [Watch](https://github.com/eaburns/Watch) | 175 | 12 | 2013-08-08 | 2 years ago | Runs a command in an acme win on file changes. |
| [vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go) | 85 | 5 | 2012-11-25 | 4 years ago | Vim plugin to highlight syntax errors on save. |
| [go-language-server](https://github.com/theia-ide/go-language-server) | 32 | 5 | 2017-11-21 | 1 year ago | A wrapper to turn the VSCode go extension into a language server supporting the language-server-protocol. |
| [gounit-vim](https://github.com/hexdigest/gounit-vim) | 19 | 2 | 2018-02-21 | 1 year ago | Vim plugin for generating Go tests based on the function's or method's signature. |
| [theia-go-extension](https://github.com/theia-ide/theia-go-extension) | 13 | 4 | 2017-11-30 | 1 year ago | Go language support for the Theia IDE. |
| [goimports-reviser](https://github.com/incu6us/goimports-reviser) | 10 | 2 | 2020-04-08 | 3 weeks ago | Formatting tool for imports. |

## Go Generate Tools
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gotests](https://github.com/cweill/gotests) | 2820 | 74 | 2016-01-19 | 4 months ago | Generate Go tests from your source code. |
| [genny](https://github.com/cheekybits/genny) | 1265 | 24 | 2014-10-27 | 1 month ago | Elegant generics for Go. |
| [re2dfa](https://github.com/opennota/re2dfa) | 182 | 9 | 2015-06-20 | 2 years ago | Transform regular expressions into finite state machines and output Go source code. |
| [gocontracts](https://github.com/Parquery/gocontracts) | 62 | 6 | 2018-08-13 | 1 year ago | brings design-by-contract to Go by synchronizing the code with the documentation. |
| [hasgo](https://github.com/DylanMeeus/hasgo) | 48 | 4 | 2019-05-16 | 2 months ago | Generate Haskell inspired functions for your slices. |
| [gounit](https://github.com/hexdigest/gounit) | 43 | 4 | 2018-02-05 | 2 years ago | Generate Go tests using your own templates. |
| [xgen](https://github.com/xuri/xgen) | 39 | 5 | 2019-06-22 | 2 months ago | XSD (XML Schema Definition) parser and Go/C/Java/Rust/TypeScript code generator. |
| [generic](https://github.com/usk81/generic) | 34 | 2 | 2016-06-15 | 1 week ago | flexible data type for Go. |

## Go Tools
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-swagger](https://github.com/go-swagger/go-swagger) | 5559 | 125 | 2014-11-16 | 2 days ago | Swagger 2.0 implementation for go. Swagger is a simple yet powerful representation of your RESTful API. |
| [OctoLinker](https://github.com/OctoLinker/OctoLinker) | 4463 | 90 | 2013-12-27 | 1 day ago | Navigate through go files efficiently with the OctoLinker browser extension for GitHub. |
| [go-callvis](https://github.com/ofabry/go-callvis) | 2722 | 79 | 2016-09-03 | 10 hours ago | Visualize call graph of your Go program using dot format. |
| [go-callvis](https://github.com/TrueFurby/go-callvis) | 2408 | 70 | 2016-09-03 | 6 months ago | Visualize call graph of your Go program using dot format. |
| [depth](https://github.com/KyleBanks/depth) | 526 | 11 | 2017-03-04 | 6 months ago | Visualize dependency trees of any package by analyzing imports. |
| [richgo](https://github.com/kyoh86/richgo) | 492 | 5 | 2017-01-04 | 2 months ago | Enrich `go test` outputs with text decorations. |
| [rts](https://github.com/galeone/rts) | 206 | 3 | 2016-04-04 | 2 months ago | RTS: response to struct. Generates Go structs from server responses. |
| [godbg](https://github.com/tylerwince/godbg) | 169 | 4 | 2019-01-23 | 1 year ago | Implementation of Rusts `dbg!` macro for quick and easy debugging during development. |
| [typex](https://github.com/dtgorski/typex) | 125 | 2 | 2020-03-24 | 1 month ago | Examine Go types and their transitive dependencies, alternatively export results as TypeScript value objects (or types) declaration. |
| [colorgo](https://github.com/songgao/colorgo) | 105 | 6 | 2013-02-14 | 1 month ago | Wrapper around `go` command for colorized `go build` output. |
| [gothanks](https://github.com/psampaz/gothanks) | 93 | 3 | 2019-11-10 | 4 months ago | GoThanks automatically stars your go.mod github dependencies, sending this way some love to their maintainers. |
| [go-pkg-complete](https://github.com/skelterjohn/go-pkg-complete) | 37 | 2 | 2015-05-22 | 2 years ago | Bash completion for go and wgo. |
| [igo](https://github.com/rocketlaunchr/igo) | 32 | 2 | 2018-11-17 | 4 months ago | Improved Go Syntax (transpiler) |
| [go-james](https://github.com/pieterclaerhout/go-james) | 28 | 2 | 2019-10-14 | 1 month ago | Go project skeleton creator, builds and tests your projects without the manual setup. |
| [generator-go-lang](https://github.com/axelspringer/generator-go-lang) | 22 | 13 | 2017-09-13 | 4 months ago | A [Yeoman](http://yeoman.io) generator to get new Go projects started. |

## Software Packages
        
*Software written in Go.*

### DevOps Tools
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [kubernetes](https://github.com/kubernetes/kubernetes) | 69613 | 3262 | 2014-06-06 | 15 minutes ago | Container Cluster Manager from Google. |
| [moby](https://github.com/moby/moby) | 57955 | 3147 | 2013-01-18 | 6 hours ago | Collaborative project for the container ecosystem to assemble container-based systems. |
| [traefik](https://github.com/containous/traefik) | 30510 | 721 | 2015-09-13 | 43 minutes ago | Reverse proxy and load balancer with support for multiple backends. |
| [gitea](https://github.com/go-gitea/gitea) | 21045 | 464 | 2016-11-01 | 37 minutes ago | Fork of Gogs, entirely community driven. |
| [vegeta](https://github.com/tsenart/vegeta) | 15316 | 303 | 2013-08-13 | 3 days ago | HTTP load testing tool and library. It's over 9000! |
| [packer](https://github.com/hashicorp/packer) | 11192 | 436 | 2013-03-23 | 2 hours ago | Packer is a tool for creating identical machine images for multiple platforms from a single source configuration. |
| [hey](https://github.com/rakyll/hey) | 9059 | 161 | 2016-09-02 | 4 days ago | Hey is a tiny program that sends some load to a web application. |
| [webhook](https://github.com/adnanh/webhook) | 5626 | 137 | 2015-01-12 | 3 weeks ago | Tool which allows user to create HTTP endpoints (hooks) that execute commands on the server. |
| [gvm](https://github.com/moovweb/gvm) | 5593 | 155 | 2011-12-03 | 5 days ago | GVM provides an interface to manage Go versions. |
| [gaia](https://github.com/gaia-pipeline/gaia) | 4183 | 106 | 2017-12-28 | 2 weeks ago | Build powerful pipelines in any programming language. |
| [gox](https://github.com/mitchellh/gox) | 3848 | 75 | 2013-11-17 | 6 months ago | Dead simple, no frills Go cross compile tool. |
| [bosun](https://github.com/bosun-monitor/bosun) | 3048 | 157 | 2013-11-15 | 1 week ago | Time Series Alerting Framework. |
| [bombardier](https://github.com/codesenberg/bombardier) | 2208 | 56 | 2016-05-29 | 1 month ago | Fast cross-platform HTTP benchmarking tool. |
| [pomerium](https://github.com/pomerium/pomerium) | 1841 | 25 | 2019-01-01 | 1 hour ago | Pomerium is an identity-aware access proxy. |
| [fac](https://github.com/mkchoi212/fac) | 1666 | 29 | 2017-12-29 | 10 months ago | Command-line user interface to fix git merge conflicts. |
| [goxc](https://github.com/laher/goxc) | 1655 | 49 | 2013-02-11 | 11 months ago | build tool for Go, with a focus on cross-compiling and packaging. |
| [script](https://github.com/bitfield/script) | 1540 | 29 | 2019-04-20 | 2 months ago | Making it easy to write shell-like scripts in Go for DevOps and system administration tasks. |
| [kala](https://github.com/ajvb/kala) | 1516 | 66 | 2015-03-19 | 1 month ago | Simplistic, modern, and performant job scheduler. |
| [statusok](https://github.com/sanathp/statusok) | 1378 | 49 | 2015-08-26 | 1 month ago | Monitor your Website and REST APIs.Get Notified through Slack, E-mail when your server is down or response time is more than expected. |
| [s3gof3r](https://github.com/rlmcpherson/s3gof3r) | 1063 | 34 | 2013-08-02 | 6 months ago | Small utility/library optimized for high speed transfer of large objects into and out of Amazon S3. |
| [go-selfupdate](https://github.com/sanbornm/go-selfupdate) | 752 | 28 | 2013-11-13 | 5 months ago | Enable your Go applications to self update. |
| [skm](https://github.com/TimothyYe/skm) | 645 | 20 | 2017-10-11 | 1 month ago | SKM is a simple and powerful SSH Keys Manager, it helps you to manage your multiple SSH keys easily! |
| [scaleway-cli](https://github.com/scaleway/scaleway-cli) | 615 | 31 | 2015-03-20 | 25 minutes ago | Manage BareMetal Servers from Command Line (as easily as with Docker). |
| [aurora](https://github.com/xuri/aurora) | 468 | 30 | 2016-10-09 | 3 months ago | Cross-platform web-based Beanstalkd queue server console. |
| [govvv](https://github.com/ahmetb/govvv) | 456 | 10 | 2016-08-02 | 7 months ago | “go build” wrapper to easily add version information into Go binaries. |
| [cassowary](https://github.com/rogerwelin/cassowary) | 440 | 5 | 2019-08-25 | 2 months ago | Modern cross-platform HTTP load-testing tool written in Go. |
| [s5cmd](https://github.com/peak/s5cmd) | 358 | 18 | 2016-11-16 | 1 day ago | Blazing fast S3 and local filesystem execution tool. |
| [gonative](https://github.com/inconshreveable/gonative) | 323 | 8 | 2014-05-01 | 4 years ago | Tool which creates a build of Go that can cross compile to all platforms while still using the Cgo-enabled versions of the stdlib packages. |
| [mora](https://github.com/emicklei/mora) | 276 | 24 | 2013-07-12 | 3 years ago | REST server for accessing MongoDB documents and meta data. |
| [trubka](https://github.com/xitonix/trubka) | 272 | 14 | 2019-07-05 | 1 month ago | A CLI tool to manage and troubleshoot Apache Kafka clusters with the ability of generically publishing/consuming protocol buffer and plain text events to/from Kafka. |
| [lstags](https://github.com/ivanilves/lstags) | 264 | 14 | 2017-08-15 | 2 months ago | Tool and API to sync Docker images across different registries. |
| [pewpew](https://github.com/bengadbois/pewpew) | 242 | 9 | 2016-10-12 | 2 months ago | Flexible HTTP command line stress tester. |
| [utask](https://github.com/ovh/utask) | 233 | 23 | 2019-11-05 | 1 week ago | Automation engine that models and executes business processes declared in yaml. |
| [dogo](https://github.com/liudng/dogo) | 229 | 18 | 2014-11-19 | 1 year ago | Monitoring changes in the source file and automatically compile and run (restart). |
| [godbg](https://github.com/sirnewton01/godbg) | 222 | 18 | 2013-08-09 | 2 years ago | Web-based gdb front-end application. |
| [manssh](https://github.com/xwjdsh/manssh) | 221 | 4 | 2017-10-08 | 2 years ago | manssh is a command line tool for managing your ssh alias config easily. |
| [jenkins-cli](https://github.com/jenkins-zh/jenkins-cli) | 192 | 11 | 2019-06-21 | 1 week ago | Jenkins CLI allows you manage your Jenkins as an easy way. |
| [blast](https://github.com/dave/blast) | 186 | 4 | 2017-10-21 | 2 years ago | A simple tool for API load testing and batch jobs. |
| [gobrew](https://github.com/cryptojuice/gobrew) | 177 | 5 | 2013-11-13 | 3 months ago | gobrew lets you easily switch between multiple versions of go. |
| [ostent](https://github.com/ostrost/ostent) | 166 | 6 | 2014-03-31 | 2 years ago | collects and displays system metrics and optionally relays to Graphite and/or InfluxDB. |
| [easyssh-proxy](https://github.com/appleboy/easyssh-proxy) | 153 | 6 | 2017-03-03 | 3 months ago | Golang package for easy remote execution through SSH and SCP downloading via `ProxyCommand`. |
| [grapes](https://github.com/yaronsumel/grapes) | 152 | 6 | 2016-09-01 | 11 months ago | Lightweight tool designed to distribute commands over ssh with ease. |
| [kcli](https://github.com/cswank/kcli) | 126 | 6 | 2017-03-25 | 8 months ago | Command line tool for inspecting kafka topics/partitions/messages. |
| [terraform-provider-openapi](https://github.com/dikhan/terraform-provider-openapi) | 121 | 10 | 2017-10-17 | 4 days ago | Terraform provider plugin that dynamically configures itself at runtime based on an OpenAPI document (formerly known as swagger file) containing the definitions of the APIs exposed. |
| [winrm-cli](https://github.com/masterzen/winrm-cli) | 96 | 5 | 2016-05-23 | 3 months ago | Cli tool to remotely execute commands on Windows machines. |
| [dockerfile-generator](https://github.com/ozankasikci/dockerfile-generator) | 83 | 5 | 2019-08-14 | 7 months ago | A go library and an executable that produces valid Dockerfiles using various input channels. |
| [go-furnace](https://github.com/go-furnace/go-furnace) | 78 | 1 | 2016-10-09 | 11 months ago | Hosting solution written in Go. Deploy your Application with ease on AWS, GCP or DigitalOcean. |
| [drone-scp](https://github.com/appleboy/drone-scp) | 77 | 3 | 2016-10-16 | 2 months ago | Copy files and artifacts via SSH using a binary, docker or Drone CI. |
| [dropship](https://github.com/ChrisMcKenzie/dropship) | 53 | 3 | 2015-09-03 | 2 years ago | Tool for deploying code via cdn. |
| [rodent](https://github.com/alouche/rodent) | 31 | 2 | 2014-06-01 | 3 years ago | Rodent helps you manage Go versions, projects and track dependencies. |
| [drone-jenkins](https://github.com/appleboy/drone-jenkins) | 30 | 2 | 2016-10-15 | 1 month ago | Trigger downstream Jenkins jobs using a binary, docker or Drone CI. |
| [awsenv](https://github.com/soniah/awsenv) | 25 | 2 | 2015-08-05 | 2 years ago | Small binary that loads Amazon (AWS) environment variables for a profile. |
| [lwc](https://github.com/timdp/lwc) | 22 | 3 | 2018-04-22 | 4 months ago | A live-updating version of the UNIX wc command. |
| [s3-proxy](https://github.com/oxyno-zeta/s3-proxy) | 19 | 2 | 2019-09-22 | 1 day ago | S3 Proxy with GET, PUT and DELETE methods and authentication (OpenID Connect and Basic Auth). |
| [depcharge](https://github.com/centerorbit/depcharge) | 14 | 3 | 2018-07-25 | 6 months ago | Helps orchestrating the execution of commands across the many dependencies in larger projects. |
| [sg](https://github.com/ChristopherRabotin/sg) | 6 | 1 | 2015-08-19 | 3 years ago | Benchmarks a set of HTTP endpoints (like ab), with possibility to use the response code and data between each call for specific server stress based on its previous response. |
| [aptly-fork](https://github.com/smira/aptly-fork) | 3 | 0 | 2019-07-04 | 11 months ago | aptly is a Debian repository management tool. |

### Other Software
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [goreplay](https://github.com/buger/goreplay) | 13252 | 468 | 2013-05-30 | 2 days ago | Http traffic replication tool, for replaying traffic from production to stage/dev environments in real-time. |
| [restic](https://github.com/restic/restic) | 10761 | 233 | 2014-04-27 | 2 hours ago | De-duplicating backup program. |
| [seaweedfs](https://github.com/chrislusf/seaweedfs) | 10187 | 528 | 2014-07-14 | 8 hours ago | Fast, Simple and Scalable Distributed File System with O(1) disk seek. |
| [confd](https://github.com/kelseyhightower/confd) | 7143 | 260 | 2013-10-01 | 1 month ago | Manage local application configuration files using templates and data from etcd or consul. |
| [comcast](https://github.com/tylertreat/comcast) | 6714 | 152 | 2014-11-12 | 3 months ago | Simulate bad network connections. |
| [liteide](https://github.com/visualfc/liteide) | 6146 | 377 | 2012-11-19 | 2 weeks ago | LiteIDE is a simple, open source, cross-platform Go IDE. |
| [drive](https://github.com/odeke-em/drive) | 5575 | 202 | 2014-11-03 | 1 week ago | Google Drive client for the commandline. |
| [toxiproxy](https://github.com/Shopify/toxiproxy) | 4822 | 292 | 2014-09-04 | 4 months ago | Proxy to simulate network and system conditions for automated tests. |
| [nes](https://github.com/fogleman/nes) | 4549 | 152 | 2015-03-02 | 1 week ago | Nintendo Entertainment System (NES) emulator written in Go. |
| [croc](https://github.com/schollz/croc) | 3458 | 60 | 2017-10-17 | 37 minutes ago | Easily and securely send files or folders from one computer to another. |
| [duplicacy](https://github.com/gilbertchen/duplicacy) | 3391 | 96 | 2016-02-23 | 1 day ago | A cross-platform network and cloud backup tool based on the idea of lock-free deduplication. |
| [mylg](https://github.com/mehrdadrad/mylg) | 2358 | 109 | 2016-06-21 | 6 months ago | Command Line Network Diagnostic tool written in Go. |
| [goboy](https://github.com/Humpheh/goboy) | 2235 | 41 | 2017-08-20 | 3 weeks ago | Nintendo Game Boy Color emulator written in Go. |
| [sup](https://github.com/pressly/sup) | 2193 | 72 | 2015-02-23 | 6 months ago | Stack Up, a super simple deployment tool - just Unix - think of it like 'make' for a network of servers. |
| [lgo](https://github.com/yunabe/lgo) | 2058 | 49 | 2017-10-05 | 1 year ago | Interactive Go programming with Jupyter. It supports code completion, code inspection and 100% Go compatibility. |
| [circuit](https://github.com/gocircuit/circuit) | 1844 | 141 | 2014-04-10 | 4 months ago | Circuit is a programmable platform-as-a-service (PaaS) and/or Infrastructure-as-a-Service (IaaS), for management, discovery, synchronization and orchestration of services and hosts comprising cloud applications. |
| [snap](https://github.com/intelsdi-x/snap) | 1794 | 146 | 2014-08-13 | 1 year ago | Powerful telemetry framework. |
| [scc](https://github.com/boyter/scc) | 1689 | 18 | 2018-03-01 | 5 days ago | Sloc Cloc and Code, a very fast accurate code counter with complexity calculations and COCOMO estimates. |
| [borg](https://github.com/ok-borg/borg) | 1482 | 42 | 2016-09-10 | 2 years ago | Terminal based search engine for bash snippets. |
| [community](https://github.com/documize/community) | 1154 | 48 | 2016-04-29 | 1 week ago | Modern wiki software that integrates data from SaaS tools. |
| [Go-Package-Store](https://github.com/shurcooL/Go-Package-Store) | 889 | 19 | 2014-01-24 | 5 months ago | App that displays updates for the Go packages in your GOPATH. |
| [peg](https://github.com/pointlander/peg) | 717 | 31 | 2010-04-25 | 6 days ago | Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator. |
| [vflow](https://github.com/VerizonDigital/vflow) | 695 | 83 | 2017-02-24 | 1 week ago | High-performance, scalable and reliable IPFIX, sFlow and Netflow collector. |
| [leaps](https://github.com/Jeffail/leaps) | 687 | 27 | 2014-06-19 | 1 year ago | Pair programming service using Operational Transforms. |
| [shell2http](https://github.com/msoap/shell2http) | 623 | 26 | 2015-03-11 | 1 week ago | Executing shell commands via http server (for prototyping or remote control). |
| [gfile](https://github.com/Antonito/gfile) | 569 | 12 | 2019-03-08 | 1 year ago | Securely transfer files between two computers, without any third party, over WebRTC. |
| [mockingjay-server](https://github.com/quii/mockingjay-server) | 461 | 9 | 2015-04-04 | 6 months ago | Fake HTTP servers and consumer driven contracts from one configuration file. You can also make the server randomly misbehave to help do more realistic performance tests. |
| [gocc](https://github.com/goccmack/gocc) | 417 | 22 | 2015-06-05 | 2 months ago | Gocc is a compiler kit for Go written in Go. |
| [go-peerflix](https://github.com/Sioro-Neoku/go-peerflix) | 408 | 18 | 2015-10-08 | 5 months ago | Video streaming torrent client. |
| [gebug](https://github.com/moshebe/gebug) | 348 | 4 | 2020-07-20 | 4 weeks ago | A tool that makes debugging of Dockerized Go applications super easy by enabling Debugger and Hot-Reload features, seamlessly. |
| [ipe](https://github.com/dimiro1/ipe) | 305 | 18 | 2015-01-13 | 5 months ago | Open source Pusher server implementation compatible with Pusher client libraries written in GO. |
| [wellington](https://github.com/wellington/wellington) | 296 | 13 | 2014-12-08 | 5 months ago | Sass project management tool, extends the language with sprite functions (like Compass). |
| [IDE](https://github.com/thestrukture/IDE) | 258 | 14 | 2017-09-09 | 1 year ago | Browser accessible IDE. Designed for Go with Go. |
| [cherry](https://github.com/rafael-santiago/cherry) | 225 | 12 | 2015-10-24 | 3 years ago | Tiny webchat server in Go. |
| [orange-cat](https://github.com/utatti/orange-cat) | 184 | 5 | 2014-11-01 | 1 year ago | Markdown previewer written in Go. |
| [joincap](https://github.com/assafmo/joincap) | 144 | 7 | 2018-05-31 | 4 months ago | Command-line utility for merging multiple pcap files together. |
| [orbit](https://github.com/gulien/orbit) | 139 | 8 | 2017-05-13 | 9 months ago | A simple tool for running commands and generating files from templates. |
| [boxed](https://github.com/tejo/boxed) | 71 | 2 | 2015-04-18 | 2 years ago | Dropbox based blog engine. |
| [dp](https://github.com/scryinfo/dp) | 60 | 9 | 2018-12-12 | 1 month ago | Through SDK for data exchange with blockchain, developers can get easy access to DAPP development. |
| [naclpipe](https://github.com/unix4fun/naclpipe) | 21 | 5 | 2015-05-05 | 1 year ago | Simple NaCL EC25519 based crypto pipe tool written in Go. |
| [term-quiz](https://github.com/crazcalm/term-quiz) | 17 | 1 | 2017-12-26 | 1 year ago | Quizzes for your terminal. |
| [snitch](https://github.com/lucasgomide/snitch) | 15 | 1 | 2017-04-06 | 2 years ago | Simple way to notify your team and many tools when someone has deployed any application via Tsuru. |
| [GoDocTooltip](https://github.com/diankong/GoDocTooltip) | 12 | 3 | 2016-01-21 | 4 months ago | Chrome extension for Go Doc sites, which shows function description as tooltip at function list. |

# Resources
        
*Where to discover new Go libraries.*

## Benchmarks
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark) | 1419 | 59 | 2013-12-16 | 1 month ago | Go HTTP request router benchmark and comparison. |
| [go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) | 1279 | 84 | 2016-04-06 | 6 days ago | Go web framework benchmark. |
| [go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) | 1027 | 38 | 2013-01-18 | 8 months ago | Benchmarks of Go serialization methods. |
| [skynet](https://github.com/atemerev/skynet) | 965 | 48 | 2016-02-14 | 1 year ago | Skynet 1M threads microbenchmark. |
| [speedtest-resize](https://github.com/fawick/speedtest-resize) | 196 | 7 | 2013-09-16 | 10 months ago | Compare various Image resize algorithms for the Go language. |
| [go-benchmarks](https://github.com/tylertreat/go-benchmarks) | 134 | 10 | 2016-02-25 | 4 years ago | Few miscellaneous Go microbenchmarks. Compare some language features to alternative approaches. |
| [gospeed](https://github.com/feyeleanor/gospeed) | 102 | 7 | 2011-05-23 | 1 year ago | Go micro-benchmarks for calculating the speed of language constructs. |
| [autobench](https://github.com/davecheney/autobench) | 90 | 8 | 2013-03-28 | 6 years ago | Framework to compare the performance between different Go versions. |
| [gocostmodel](https://github.com/mna/gocostmodel) | 55 | 5 | 2014-12-19 | 5 years ago | Benchmarks of common basic operations for the Go language. |
| [golang-sql-benchmark](https://github.com/tyler-smith/golang-sql-benchmark) | 52 | 5 | 2014-09-24 | 2 years ago | Collection of benchmarks for popular Go database/SQL utilities. |
| [go-benchmark-app](https://github.com/mrLSD/go-benchmark-app) | 21 | 1 | 2017-01-24 | 3 years ago | Powerful HTTP-benchmark tool mixed with Аb, Wrk, Siege tools. Gathering statistics and various parameters for benchmarks and comparison results. |
| [kvbench](https://github.com/jimrobinson/kvbench) | 17 | 1 | 2014-04-15 | 11 months ago | Key/Value database benchmark. |

## Conferences
        

## E-Books
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [GoBooks](https://github.com/dariubs/GoBooks) | 8256 | 554 | 2015-05-05 | 3 weeks ago | A curated list of Go books. |
| [The-Golang-Standard-Library-by-Example](https://github.com/polaris1119/The-Golang-Standard-Library-by-Example) | 7044 | 568 | 2013-04-14 | 1 month ago | Golang标准库。对于程序员而言，标准库与语言本身同样重要，它好比一个百宝箱，能为各种常见的任务提供完美的解决方案。以示例驱动的方式讲解Golang的标准库。 |
| [gosuccinctly](https://github.com/thedevsir/gosuccinctly) | 15 | 3 | 2018-09-02 | 1 year ago | in Persian. |

## Gophers
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gophers](https://github.com/ashleymcnamara/gophers) | 2244 | 95 | 2017-02-15 | 1 year ago | Gopher artworks by Ashley McNamara. |
| [gophers](https://github.com/egonelbre/gophers) | 2089 | 47 | 2015-06-03 | 2 months ago | Free gophers. |
| [free-gophers-pack](https://github.com/MariaLetta/free-gophers-pack) | 1988 | 53 | 2019-04-02 | 2 months ago | Gopher graphics pack by Maria Letta with illustrations and emotional characters in vector and raster. |
| [gophericons](https://github.com/shalakhin/gophericons) | 568 | 20 | 2015-08-22 | 2 years ago | 34 gopher images for Go developers community |
| [gopher-stickers](https://github.com/tenntenn/gopher-stickers) | 483 | 15 | 2014-11-09 | 9 months ago | gopher stickers |
| [gopherize.me](https://github.com/matryer/gopherize.me) | 446 | 9 | 2017-01-25 | 6 days ago | Gopherize yourself. |
| [gopher-vector](https://github.com/golang-samples/gopher-vector) | 366 | 14 | 2013-03-31 | 4 years ago | Vector data of gopher |
| [gopher-logos](https://github.com/GolangUA/gopher-logos) | 76 | 7 | 2017-07-27 | 2 years ago | adorable gopher logos. |
| [go-gopher](https://github.com/sillecelik/go-gopher) | 58 | 0 | 2018-03-28 | 4 months ago | Gopher amigurumi toy pattern. |
| [gophers](https://github.com/rogeralsing/gophers) | 54 | 2 | 2017-01-28 | 3 weeks ago | random gopher graphics. |
| [Go-gopher-Vector](https://github.com/keygx/Go-gopher-Vector) | 35 | 1 | 2014-09-03 | 2 years ago | Go gopher Vector Data [.ai, .svg]. |

## Meetups
        
*Add the group of your city/country here (send **PR**)*

## Twitter
        

## Websites
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) | 26537 | 1750 | 2014-07-08 | 1 week ago | List of other amazingly awesome lists. |
| [awesome-remote-job](https://github.com/lukasz-madon/awesome-remote-job) | 19124 | 1015 | 2015-01-02 | 1 hour ago | Curated list of awesome remote jobs. A lot of them are looking for Go hackers. |
| [golang-graphics](https://github.com/mholt/golang-graphics) | 143 | 9 | 2014-03-24 | 5 years ago | Collection of Go images, graphics, and art. |
| [gocryforhelp](https://github.com/ninedraft/gocryforhelp) | 38 | 12 | 2016-05-09 | 2 years ago | Collection of Go projects that needs help. Good place to start your open-source way in Go. |

### Tutorials
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [build-web-application-with-golang](https://github.com/astaxie/build-web-application-with-golang) | 35511 | 2479 | 2012-08-02 | 3 weeks ago | Golang ebook intro how to build a web app with golang. |
| [go-patterns](https://github.com/tmrts/go-patterns) | 13491 | 593 | 2015-12-14 | 1 month ago | Curated list of Go design patterns, recipes and idioms. |
| [learn-go-with-tests](https://github.com/quii/learn-go-with-tests) | 11726 | 278 | 2018-03-02 | 8 hours ago | Learn Go with test-driven development. |
| [golang-cheat-sheet](https://github.com/a8m/golang-cheat-sheet) | 4729 | 182 | 2014-02-13 | 2 months ago | Go's reference card. |
| [golang-for-nodejs-developers](https://github.com/miguelmota/golang-for-nodejs-developers) | 1317 | 34 | 2019-01-03 | 2 days ago | Examples of Golang compared to Node.js for learning. |
| [working-with-go](https://github.com/mkaz/working-with-go) | 1160 | 50 | 2014-05-04 | 7 months ago | Intro to go for experienced programmers. |
| [ethereum-development-with-go-book](https://github.com/miguelmota/ethereum-development-with-go-book) | 657 | 41 | 2018-05-16 | 4 weeks ago | A little e-book on Ethereum Development with Go. |
| [goapp](https://github.com/bnkamalesh/goapp) | 168 | 9 | 2020-07-04 | 1 month ago | An opinionated guideline to structure & develop a Go web application/service. |

## Style Guides
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-styleguide](https://github.com/bahlo/go-styleguide) | 944 | 28 | 2017-07-29 | 5 months ago | Opinionated Styleguide for the Go language |

> 该项目源码[Awesome Go Analysis](https://github.com/plholx/awesome-go-analysis)
> 更专业的go开源项目分析请移步 [Awesome Go](https://go.libhunt.com/)
