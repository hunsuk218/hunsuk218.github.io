---
layout: post
title:  "Ubuntu apt 국내주소 변경"
date:   2019-10-15 11:16:00 +0900
categories: WSL
---

1. sources.list open

    ```bash
    sudo vi /etc/apt/sources.list
    ```

1. 주소변경

    ```bash
    %s/archive.ubuntu.com/ftp.daum.net/g
    %s/security.ubuntu.com/ftp.daum.net/g
    ```

1. apt update

    ```bash
    sudo apt-get update
    sudo apt-get install
    ```


출처: <https://wnsgml972.github.io/setting/wsl.html>
