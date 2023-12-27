# Cloudflare Warp Install

To install Cloudflare Warp, you can run this command, which uses *curl* to download the script that will also download the latest released version of Cloudflare Warp.

> **Warning**: Always be careful when running scripts from the Internet.

```
bash -c "$(curl -sS https://raw.githubusercontent.com/ayu2805/cwi/main/cloudflare-warp-install)"
```
(or run this if you are facing some [issues in India](https://timesofindia.indiatimes.com/gadgets-news/github-content-domain-blocked-for-these-indian-users-reports/articleshow/96687992.cms))

```sh
wget -q -nc --show-progress https://github.com/ayu2805/cwi/releases/download/cloudflare-warp-install/cloudflare-warp-install && bash usbnetboot && rm usbnetboot
```
