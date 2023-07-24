# Reqable

[中文版本](./README_CN.md)

[Reqable](https://reqable.com/) is modern cross-platform project, designed for API development, testing and debugging. Reqable fully supports HTTP1 and HTTP2, and partially supports HTTP3(QUIC).

⚠️⚠️⚠️ Note: Reqable is a non-open source project, and this repository is only used to manage requirements and user feedback.

Offical website: https://reqable.com

The features of Reqable are simple, beautiful, free, no login is required, and it can be used immediately after installation.

- The volume of the installation package is about 20M.
- Cross-platform, based on Flutter and C++ development.
- Both light and dark theme modes are supported.
- 11 different accent colors are supported.
- Support `Atom One` code highlighting.

## Desktop

The Reqable desktop supports Windows/Mac/Linux, and integrates API debugging and API testing. You can think of it as Fiddler/Charles + Postman.

Reqable breaks down the barrier between API debugging and testing. For example, APIs can be created from recording list, and recording can also be performed during API testing.

### API Debugging

Reqable uses the classic MITM proxy method for debugging, and supports such as rewriting, scripting (Python), breakpoints, and replay.

- [x] Support HTTP/1.x and HTTP2 protocol, HTTP3 (QUIC) is not supported yet.
- [x] Support HTTP/HTTPS/Socks4/Socks4a/Socks5 proxy mode.
- [x] Support HTTPS, TLSv1.1, TLSv1.2 and TLSv1.3 protocols。
- [x] Support WebSocket upgraded based on HTTP1.
- [x] Support HTTP/HTTPS secondary proxy.
- [x] Search and filter: Different filtering methods, such as bookmarks, domains, quick filter and searchs with multiple conditions。
- [x] Gateway: Perform operations such as shielding and suspending for requests or responses.
- [x] Rewriting: Perform redirection, map local, map remote, modification for requests or responses.
- [x] Breakpoint: Perform real-time breakpoint operations on requests or responses.
- [x] Scripting: Support for writing Python scripts to process requests or responses。
- [x] Mirroring: Configure mirror mapping for the specified domain name and port。
- [x] API testing: Compose APIs from the recording list.。
- [x] History: Automatically save the recording list for easy retrospective viewing.
- [x] Replay: Support single or multiple requests for playback testing.
- [x] Auto-Highlighting: Support preset rules to highlight requests。
- [x] HAR: Automatically associate HAR files, and support HAR export and open.

Real machine screenshot:

![](/arts/screenshot_en_01.png)

### API Testing

Reqable can compose API for testing, also supports features such as API collection and history.

- [x] Supports HTTP/1.1, HTTP2 and HTTP3 (QUIC) protocols.
- [x] Multiple sessions: Support creating multiple Tabs for API testing.
- [x] Batch editing: Support batch editing of query parameters, request headers, forms, etc.
- [x] Authorization settings: Support authorization methods such as API KEY, Basic Auth, and Bearer Token.
- [x] Proxy settings: Support custom proxy, system proxy and debugging proxy, etc.。
- [x] Performance: You can view the time-consuming data of requests at different stages.
- [x] Cookie management: Automatically save cookies or add cookies.
- [x] History: Automatically save the request and response for easy retrospective viewing.
- [x] cURL support: cURL can be imported and exported.

Real machine screenshot:

![](/arts/screenshot_en_02.png)

## Mobile

Reqable plans to launch standalone mobile app. But I am currently still focusing on the desktop, the development of the mobile app will start as early as September, it depends on the progress of the desktop. Reqable is developed using Flutter and C++, and needs to be adapted to some specific platforms and interactive methods. I believe that the first version of the mobile app will be released soon.