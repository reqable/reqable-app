# Reqable

[中文版本](./README_CN.md)

⚠️ **Note: Reqable is a non-open source project, and this repository is only used to manage requirements and user feedback.**

[Reqable](https://reqable.com/) is a modern cross-platform project, designed for API development, testing, and debugging. Reqable fully supports HTTP1 and HTTP2 and partially supports HTTP3(QUIC). Now available on `Windows`, `Mac`, `Linux`, `Android` and `iOS`.

![](https://reqable.com/en-US/img/reqable-social-card.jpg)

Official website: https://reqable.com

The features of Reqable are simple, beautiful, free, no login is required, and it can be used immediately after installation.

- The volume of the installation package is about 20M.
- Cross-platform, based on Flutter and C++ development.
- Both light and dark theme modes are supported.
- 11 different accent colors are supported.
- Support `Atom One` code highlighting.

## Desktop App

The Reqable desktop supports Windows/Mac/Linux and integrates API debugging and API testing. You can think of it as Fiddler/Charles + Postman.

Reqable breaks down the barrier between API debugging and testing. For example, APIs can be created from a recording list, and recording can also be performed during API testing.

### 1. API Debugging

Reqable uses the classic MITM proxy method for debugging and supports such as rewriting, scripting (Python), breakpoints, and replay.

- [x] Support HTTP/1.x and HTTP2 protocol, HTTP3 (QUIC) is not supported yet.
- [x] Support HTTP/HTTPS/Socks4/Socks4a/Socks5 proxy mode.
- [x] Support HTTPS, TLSv1.1, TLSv1.2 and TLSv1.3 protocols.
- [x] Support WebSocket upgraded based on HTTP1.
- [x] Support HTTP/HTTPS secondary proxy.
- [x] Search and filter: Different filtering methods, such as bookmarks, domains, quick filter, and searchs with multiple conditions.
- [x] Gateway: Perform operations such as shielding and suspending for requests or responses.
- [x] Rewriting: Perform redirection, map local, map remote, modification for requests or responses.
- [x] Breakpoint: Perform real-time breakpoint operations on requests or responses.
- [x] Scripting: Support for writing Python scripts to process requests or responses.
- [x] Mirroring: Configure mirror mapping for the specified domain name and port.
- [x] API testing: Compose APIs from the recording list.
- [x] History: Automatically save the recording list for easy retrospective viewing.
- [x] Diff tool: Compare request and response messages, quickly locate data deviations.
- [x] Replay: Support single or multiple requests for playback testing.
- [x] Reverse proxy: Use local reverse proxy server to debug HTTPS traffics without trusting CA certificate.
- [x] Traffic source: Detect which application the traffic is coming from.
- [x] HAR: Automatically associate HAR files, and support HAR export and open.

Real machine screenshot:

![](/arts/screenshot_en_01.png)

### 2. API Testing

Reqable can compose API for testing and also supports features such as API collection and history.

- [x] Supports HTTP/1.1, HTTP2 and HTTP3 (QUIC) protocols.
- [x] API collection: Save API to collections, or import collections from Postman and Hoppscotch.
- [x] Multiple sessions: Support creating multiple Tabs for API testing.
- [x] Batch editing: Support batch editing of query parameters, request headers, forms, etc.
- [x] Authorization settings: Support authorization methods such as API KEY, Basic Auth, and Bearer Token.
- [x] Proxy settings: Support custom proxy, system proxy and debugging proxy, etc.
- [x] Performance: You can view the time-consuming data of requests at different stages.
- [x] Cookie management: Automatically save cookies or add cookies.
- [x] History: Automatically save the request and response for easy retrospective viewing.
- [x] cURL support: cURL can be imported and exported.

Real machine screenshot:

![](/arts/screenshot_en_02.png)

## Installation

Reqable official website provides the download of the latest version: [Download Now](https://reqable.com/en-US/download). If you want to download the historical version: [Click here](https://github.com/reqable/reqable-app/releases). In addition, on Mac, Reqable provides the `Homebrew` installation.

### Windows Setup

On Windows, you download `Setup.exe` and just follow the setup installation program instructions. There is currently no installation-free version available, mainly because Reqable installation requires writing the registry (associated with `har` and other file formats).

### Mac Setup

On Mac, Reqable provides installation packages for both Apple chip and Intel chip. If you download the DMG file, open it and drag app into the `Applications` folder; if you are using `Homebrew`, please try this command:
```shell
brew install reqable
```

### Linux Setup

The Linux version requires the GTK library. Please confirm whether the system has GTK installed before installation. The Linux installation program is a deb file. We currently only provide the x64 architecture version. You can install it using `apt`:
```shell
sudo apt install reqable-app-linux-x86_64.deb
```

## Mobile App

The Reqable mobile can be used standalone or work with the desktop app. Standalone means that traffic recording and API testing can be performed independently without relying on the desktop. While in collaborative mode, the mobile app could automatically forward traffic to the desktop by scanning the desktop QR code without manually configuring the Wifi proxy.

Mobile app implements most of the features on the desktop, except for some with legal risks, such as rewriting.

Get app for free from play store and app store.

<a href="https://play.google.com/store/apps/details?id=com.reqable.android"><img src="arts/play_store.svg" height="48"></a>
<a href="https://apps.apple.com/app/id6473166828"><img src="arts/app_store.svg" height="48"></a>

Real machine screenshots:

![](/arts/screenshot_en_03.png)

## Documentation
https://reqable.com/en-US/docs/introduction
