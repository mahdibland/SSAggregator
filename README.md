# TopFreeProxies
[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/alanbobs999/topfreeproxies/sub_merge?label=sub_merge)](https://github.com/alanbobs999/TopFreeProxies/actions/workflows/sub_merge.yml) 

![Watchers](https://img.shields.io/github/watchers/alanbobs999/topfreeproxies) ![Stars](https://img.shields.io/github/stars/alanbobs999/topfreeproxies) ![Forks](https://img.shields.io/github/forks/alanbobs999/topfreeproxies) ![Vistors](https://visitor-badge.laobi.icu/badge?page_id=alanbobs999.topfreeproxies) ![LICENSE](https://img.shields.io/badge/license-CC%20BY--SA%204.0-green.svg)

[仓库介绍](https://github.com/alanbobs999/TopFreeProxies#仓库介绍) | [使用方法](https://github.com/alanbobs999/TopFreeProxies#使用方法) | [节点信息](https://github.com/alanbobs999/TopFreeProxies#节点信息) | [软件推荐](https://github.com/alanbobs999/TopFreeProxies#客户端选择) | [机场推荐](https://github.com/alanbobs999/TopFreeProxies#机场推荐) | [仓库声明](https://github.com/alanbobs999/TopFreeProxies#仓库声明)

## 仓库介绍
本仓库自动化功能全部基于 `GitHub Actions` 实现，如果有需要可以自行 Fork 实现个性化需求。

对网络上各免费节点池及博主分享的节点进行测速筛选出较为稳定高速的节点，再导入到仓库中进行分享记录。所筛选的节点链接在仓库 `./sub/sub_list.json` 文件中，其中大部分为其他 `GitHub` 仓库链接，如果大家有好的订阅链接欢迎提交 PR ，这些链接包含的所有节点会合并在仓库 `./sub/sub_merge.txt` 中。

测速筛选后的节点订阅文件在仓库根目录 `Eterniy`(Base64) 和 `Eternity.yml`(Clash)。同时在仓库的 `./update` 中保留了原始节点链接的的记录。

测速功能使用 [LiteSpeedTest](https://github.com/xxf098/LiteSpeedTest) 在 `GitHub Actions` 环境下实现，所以美国节点较多，不能很好代表国内网络环境下节点可用性，目前正在解决这一问题。

虽然是测速筛选过后的节点，但仍然会出现部分节点不可用的情况，遇到这种情况建议选择`Clash`, `Shadowrocket`之类能自动切换低延迟节点的客户端。

## 使用方法
将以下订阅链接导入相应客户端即可。链接中大部分为 SS 协议节点，少量 Vmess, Trojan ,SSR 协议节点，建议选择协议支持完整的客户端。

- [多协议Base64编码](https://raw.githubusercontent.com/alanbobs999/TopFreeProxies/master/Eternity)
- [Clash](https://raw.githubusercontent.com/alanbobs999/TopFreeProxies/master/Eternity.yml)

另有国内加速链接：

- [多协议Base64编码](https://fastly.jsdelivr.net/gh/alanbobs999/TopFreeProxies@master/Eternity)
- [Clash](https://fastly.jsdelivr.net/gh/alanbobs999/TopFreeProxies@master/Eternity.yml)

>`Clash`链接所使用的配置在仓库`./update/provider/`中，有相应配置文件和以国家分类的`proxy-provider`。
>
>需要其它配置可使用订阅转换工具自行转换。
>自用在线订阅转换网址：[sub-web-modify](https://sub.v1.mk/)

## 节点信息
### 高速节点
高速节点数量: `99`
<details>
  <summary>展开复制节点</summary>

    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA2NiIsImFkZCI6InVzYS13YXNoaW5ndG9uLmx2dWZ0LmNvbSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYWJhNTBkZDQtNTQ4NC0zYjA1LWIxNGEtNDY2MWNhZjg2MmQ1IiwiYWlkIjoiNCIsIm5ldCI6IndzIiwicGF0aCI6Ii93cyIsImhvc3QiOiJ1c2Etd2FzaGluZ3Rvbi5sdnVmdC5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA3MiIsImFkZCI6IjQ1LjM1Ljg0LjE2MiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYWJhNTBkZDQtNTQ4NC0zYjA1LWIxNGEtNDY2MWNhZjg2MmQ1IiwiYWlkIjoiNCIsIm5ldCI6IndzIiwicGF0aCI6Ii93cyIsImhvc3QiOiJ1c2EtZGFsbGFzLmx2dWZ0LmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA3NiIsImFkZCI6IjIwOC45OC40OC4yIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJhYmE1MGRkNC01NDg0LTNiMDUtYjE0YS00NjYxY2FmODYyZDUiLCJhaWQiOiI0IiwibmV0Ijoid3MiLCJwYXRoIjoiL3dzIiwiaG9zdCI6Imllc2VpMWVpLmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA2MyIsImFkZCI6InVzYS1kYWxsYXMubHZ1ZnQuY29tIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJhYmE1MGRkNC01NDg0LTNiMDUtYjE0YS00NjYxY2FmODYyZDUiLCJhaWQiOiI0IiwibmV0Ijoid3MiLCJwYXRoIjoiL3dzIiwiaG9zdCI6InVzYS1kYWxsYXMubHZ1ZnQuY29tIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiVVMwMS1WMi3nm7Tov54iLCJhZGQiOiJ1czAxLmhlbmV0LmN5b3UiLCJwb3J0IjoiMjAwMDAiLCJ0eXBlIjoibm9uZSIsImlkIjoiODNmNWQ0ZjEtNDliMi00YWNlLWE1YWQtNDhkZjU4ZjRkYTUzIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9saXZlIiwiaG9zdCI6ImNjdHYuY29tIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA3NyIsImFkZCI6Imllc2VpMWVpLmNvbSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYWJhNTBkZDQtNTQ4NC0zYjA1LWIxNGEtNDY2MWNhZjg2MmQ1IiwiYWlkIjoiNCIsIm5ldCI6IndzIiwicGF0aCI6Ii93cyIsImhvc3QiOiJpZXNlaTFlaS5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA2MyIsImFkZCI6IjIwOC45OC40OC4yIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJhYmE1MGRkNC01NDg0LTNiMDUtYjE0YS00NjYxY2FmODYyZDUiLCJhaWQiOiI0IiwibmV0Ijoid3MiLCJwYXRoIjoiL3dzIiwiaG9zdCI6Imllc2VpMWVpLmNvbSIsInRscyI6InRscyJ9
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTozZjQxMWU4Ny0zZTkzLTRmMjMtYmMyMi0yNjNhNzQ4YmM4YzU@164.92.107.59:1645#%F0%9F%87%BA%F0%9F%87%B8%20%3A%E7%BE%8E%E5%9B%BD-ss-164.92.107.59%3A1645-%E5%8F%AF%E7%94%A8-%E7%9B%B4%E8%BF%9E-%E4%BB%85%E6%94%AF%E6%8C%81%E7%BE%8E%E5%9B%BD%E5%9C%B0%E5%8C%BANF%E8%87%AA%E5%88%B6%E5%89%A7
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTozZjQxMWU4Ny0zZTkzLTRmMjMtYmMyMi0yNjNhNzQ4YmM4YzU@164.92.115.89:3125#%F0%9F%87%BA%F0%9F%87%B8%20%3A%E7%BE%8E%E5%9B%BD-ss-164.92.115.89%3A3125-%E5%8F%AF%E7%94%A8-%E7%9B%B4%E8%BF%9E-%E4%BB%85%E6%94%AF%E6%8C%81%E7%BE%8E%E5%9B%BD%E5%9C%B0%E5%8C%BANF%E8%87%AA%E5%88%B6%E5%89%A7
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTozZjQxMWU4Ny0zZTkzLTRmMjMtYmMyMi0yNjNhNzQ4YmM4YzU@164.92.115.89:3125#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD12
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTozZjQxMWU4Ny0zZTkzLTRmMjMtYmMyMi0yNjNhNzQ4YmM4YzU@164.92.107.59:1645#US_27
    ss://YWVzLTI1Ni1nY206M2Y0MTFlODctM2U5My00ZjIzLWJjMjItMjYzYTc0OGJjOGM1@164.92.99.255:4649#%F0%9F%87%BA%F0%9F%87%B8%20%3A%E7%BE%8E%E5%9B%BD-ss-164.92.99.255%3A4649-%E5%8F%AF%E7%94%A8-%E7%9B%B4%E8%BF%9E-%E4%BB%85%E6%94%AF%E6%8C%81%E7%BE%8E%E5%9B%BD%E5%9C%B0%E5%8C%BANF%E8%87%AA%E5%88%B6%E5%89%A7
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTozZjQxMWU4Ny0zZTkzLTRmMjMtYmMyMi0yNjNhNzQ4YmM4YzU@164.92.115.89:3125#US_25
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDEzOSIsImFkZCI6ImJhaS1waWFvLXdhbmctemhlLWlwbGM2Ljk4ODQ4Lnh5eiIsInBvcnQiOiIxMjgyNCIsInR5cGUiOiJub25lIiwiaWQiOiJjZTQ5YjAzYS1lYzM2LTRhZmQtZDZmMS1mNjc4YWQzN2NiYjciLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii9nbyIsImhvc3QiOiJiYWktcGlhby13YW5nLXpoZS1pcGxjNi45ODg0OC54eXoiLCJ0bHMiOiIifQ==
    ss://YWVzLTI1Ni1nY206M2Y0MTFlODctM2U5My00ZjIzLWJjMjItMjYzYTc0OGJjOGM1@164.92.99.255:4649#%F0%9F%87%BA%F0%9F%87%B8%20%3A%E7%BE%8E%E5%9B%BD-ss-164.92.99.255%3A4649-%E5%8F%AF%E7%94%A8-%E7%9B%B4%E8%BF%9E-%E4%BB%85%E6%94%AF%E6%8C%81%E7%BE%8E%E5%9B%BD%E5%9C%B0%E5%8C%BANF%E8%87%AA%E5%88%B6%E5%89%A7
    ss://YWVzLTI1Ni1nY206M2Y0MTFlODctM2U5My00ZjIzLWJjMjItMjYzYTc0OGJjOGM1@164.92.99.255:4649#%F0%9F%87%BA%F0%9F%87%B8%20github.com%2Ffreefq%20-%20%E7%BE%8E%E5%9B%BD%20%206
    ss://YWVzLTI1Ni1nY206M2Y0MTFlODctM2U5My00ZjIzLWJjMjItMjYzYTc0OGJjOGM1@164.92.99.255:4649#%F0%9F%87%BA%F0%9F%87%B8%20%3A%E7%BE%8E%E5%9B%BD-ss-164.92.99.255%3A4649-%E5%8F%AF%E7%94%A8-%E7%9B%B4%E8%BF%9E-%E8%A7%A3%E9%94%81%E7%BE%8E%E5%9B%BD%E5%9C%B0%E5%8C%BANF%E9%9D%9E%E8%87%AA%E5%88%B6%E5%89%A7
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTozZjQxMWU4Ny0zZTkzLTRmMjMtYmMyMi0yNjNhNzQ4YmM4YzU@164.92.107.59:1645#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD11
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTozZjQxMWU4Ny0zZTkzLTRmMjMtYmMyMi0yNjNhNzQ4YmM4YzU@164.92.107.59:1645#%F0%9F%87%BA%F0%9F%87%B8%20github.com%2Ffreefq%20-%20%E7%BE%8E%E5%9B%BD%20%205
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTozZjQxMWU4Ny0zZTkzLTRmMjMtYmMyMi0yNjNhNzQ4YmM4YzU@164.92.115.89:3125#%F0%9F%87%BA%F0%9F%87%B8%20US%201
    ss://YWVzLTI1Ni1nY206M2Y0MTFlODctM2U5My00ZjIzLWJjMjItMjYzYTc0OGJjOGM1@164.92.99.255:4649#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD13
    ss://YWVzLTI1Ni1nY206M2Y0MTFlODctM2U5My00ZjIzLWJjMjItMjYzYTc0OGJjOGM1@164.92.99.255:4649#%F0%9F%87%BA%F0%9F%87%B8%20github.com%2Ffreefq%20-%20%E7%BE%8E%E5%9B%BD%20%206
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTozZjQxMWU4Ny0zZTkzLTRmMjMtYmMyMi0yNjNhNzQ4YmM4YzU@164.92.107.59:1645#%F0%9F%87%BA%F0%9F%87%B8%20US%203
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDAzMCIsImFkZCI6IjE0My4xOTguMTMwLjIxIiwicG9ydCI6IjQyMzgyIiwidHlwZSI6Im5vbmUiLCJpZCI6IjAzYjQ1MmE3LTkwN2ItNGY3Ny04Y2E0LTYwMjUwY2M4MzViYyIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    trojan://dfbf0d67-f03d-4184-a224-c2d64a571f99@s3.hazz.win:12340?allowInsecure=1&sni=edge.apple.com#_%E6%B2%B9%E7%AE%A1%EF%BC%9A%E5%85%A8%E7%BD%91%E6%9C%80%E5%BC%BA%E7%99%BD%E5%AB%96
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTozZjQxMWU4Ny0zZTkzLTRmMjMtYmMyMi0yNjNhNzQ4YmM4YzU@164.92.107.59:1645#%F0%9F%87%BA%F0%9F%87%B8%20%3A%E7%BE%8E%E5%9B%BD-ss-164.92.107.59%3A1645-%E5%8F%AF%E7%94%A8-%E7%9B%B4%E8%BF%9E-%E4%BB%85%E6%94%AF%E6%8C%81%E7%BE%8E%E5%9B%BD%E5%9C%B0%E5%8C%BANF%E8%87%AA%E5%88%B6%E5%89%A7
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA5MCIsImFkZCI6ImJhaS1waWFvLXdhbmctemhlLWlwbGM2Ljk4ODQ4Lnh5eiIsInBvcnQiOiIxMjgyNCIsInR5cGUiOiJub25lIiwiaWQiOiJjZTQ5YjAzYS1lYzM2LTRhZmQtZDZmMS1mNjc4YWQzN2NiYjciLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii95b3V0dWJ0QOeZveWrlueOi+iAhSIsImhvc3QiOiJiYWktcGlhby13YW5nLXpoZS1pcGxjNi45ODg0OC54eXoiLCJ0bHMiOiIifQ==
    ss://YWVzLTI1Ni1nY206M2Y0MTFlODctM2U5My00ZjIzLWJjMjItMjYzYTc0OGJjOGM1@164.92.99.255:4649#%F0%9F%87%BA%F0%9F%87%B8%20US%204
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTozZjQxMWU4Ny0zZTkzLTRmMjMtYmMyMi0yNjNhNzQ4YmM4YzU@164.92.115.89:3125#%F0%9F%87%BA%F0%9F%87%B8%20github.com%2Ffreefq%20-%20%E7%BE%8E%E5%9B%BD%20%207
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTozZjQxMWU4Ny0zZTkzLTRmMjMtYmMyMi0yNjNhNzQ4YmM4YzU@164.92.115.89:3125#%F0%9F%87%BA%F0%9F%87%B8%20%3A%E7%BE%8E%E5%9B%BD-ss-164.92.115.89%3A3125-%E5%8F%AF%E7%94%A8-%E7%9B%B4%E8%BF%9E-%E4%BB%85%E6%94%AF%E6%8C%81%E7%BE%8E%E5%9B%BD%E5%9C%B0%E5%8C%BANF%E8%87%AA%E5%88%B6%E5%89%A7
    ss://YWVzLTI1Ni1nY206M2Y0MTFlODctM2U5My00ZjIzLWJjMjItMjYzYTc0OGJjOGM1@164.92.99.255:4649#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%20014
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTozZjQxMWU4Ny0zZTkzLTRmMjMtYmMyMi0yNjNhNzQ4YmM4YzU@164.92.115.89:3125#%F0%9F%87%BA%F0%9F%87%B8%20github.com%2Ffreefq%20-%20%E7%BE%8E%E5%9B%BD%20%207
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTozZjQxMWU4Ny0zZTkzLTRmMjMtYmMyMi0yNjNhNzQ4YmM4YzU@164.92.115.89:3125#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%20009
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA3NCIsImFkZCI6ImJhaS1waWFvLXdhbmctemhlLWlwbGM2Ljk4ODQ4Lnh5eiIsInBvcnQiOiIxMjgyNCIsInR5cGUiOiJub25lIiwiaWQiOiJjZTQ5YjAzYS1lYzM2LTRhZmQtZDZmMS1mNjc4YWQzN2NiYjciLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii94eFgxIiwiaG9zdCI6ImJhaS1waWFvLXdhbmctemhlLWlwbGM2Ljk4ODQ4Lnh5eiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggVVMgNiIsImFkZCI6IjE0My4xMTAuMTQ1LjMzIiwicG9ydCI6IjEyMzE1IiwidHlwZSI6Im5vbmUiLCJpZCI6IjYzMjk3YzM5LTNlNjktNGZkMC04NjMyLWRhNGM3MDhmMTM5ZiIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiJmaGNhcm0yLmdhb3gubWwiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA2NCIsImFkZCI6Imllc2VpMWVpLmNvbSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYWJhNTBkZDQtNTQ4NC0zYjA1LWIxNGEtNDY2MWNhZjg2MmQ1IiwiYWlkIjoiNCIsIm5ldCI6IndzIiwicGF0aCI6Ii93cyIsImhvc3QiOiJpZXNlaTFlaS5jb20iLCJ0bHMiOiJ0bHMifQ==
    trojan://dfbf0d67-f03d-4184-a224-c2d64a571f99@s3.hazz.win:12340?allowInsecure=1&sni=edge.apple.com#%F0%9F%87%BA%F0%9F%87%B8%20US%207
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggX1VTX+e+juWbvV81IiwiYWRkIjoiMTQzLjE5OC4xMzAuMjEiLCJwb3J0IjoiNDIzODIiLCJ0eXBlIjoibm9uZSIsImlkIjoiMDNiNDUyYTctOTA3Yi00Zjc3LThjYTQtNjAyNTBjYzgzNWJjIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggdjJyYXlmcmVlLmV1Lm9yZyAtIOe+juWbveWco+aWr+iAg+aLieaWr+iSguWNoeWkp+WtpiAyMyIsImFkZCI6IjE0My4xMTAuMTQ1LjMzIiwicG9ydCI6IjEyMzE1IiwidHlwZSI6Im5vbmUiLCJpZCI6IjYzMjk3YzM5LTNlNjktNGZkMC04NjMyLWRhNGM3MDhmMTM5ZiIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiL2NoYXQiLCJob3N0IjoiIiwidGxzIjoiIn0=
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTozZjQxMWU4Ny0zZTkzLTRmMjMtYmMyMi0yNjNhNzQ4YmM4YzU@164.92.115.89:3125#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD12
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDExNSIsImFkZCI6ImJhaS1waWFvLXdhbmctemhlLWlwbGM2Ljk4ODQ4Lnh5eiIsInBvcnQiOiIxMjgyNCIsInR5cGUiOiJub25lIiwiaWQiOiJjZTQ5YjAzYS1lYzM2LTRhZmQtZDZmMS1mNjc4YWQzN2NiYjciLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii9jY3R2MTMvaGQubTN1OCIsImhvc3QiOiJiYWktcGlhby13YW5nLXpoZS1pcGxjNi45ODg0OC54eXoiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA2MDg2NDMiLCJhZGQiOiJpZXNlaTFlaS5jb20iLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImFiYTUwZGQ0LTU0ODQtM2IwNS1iMTRhLTQ2NjFjYWY4NjJkNSIsImFpZCI6IjQiLCJuZXQiOiJ3cyIsInBhdGgiOiIvd3MiLCJob3N0IjoiaWVzZWkxZWkuY29tIiwidGxzIjoidGxzIn0=
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTozZjQxMWU4Ny0zZTkzLTRmMjMtYmMyMi0yNjNhNzQ4YmM4YzU@164.92.107.59:1645#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%20013
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTozZjQxMWU4Ny0zZTkzLTRmMjMtYmMyMi0yNjNhNzQ4YmM4YzU@164.92.107.59:1645#%F0%9F%87%BA%F0%9F%87%B8%20github.com%2Ffreefq%20-%20%E7%BE%8E%E5%9B%BD%20%205
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDExMyIsImFkZCI6ImJhaS1waWFvLXdhbmctemhlLWlwbGM2Ljk4ODQ4Lnh5eiIsInBvcnQiOiIzMTk2MSIsInR5cGUiOiJub25lIiwiaWQiOiI5NDMxMWU3MS05MTI1LTRiZDEtZmFhMi01MTVhODY2N2M0ODYiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3lvdXR1YnRA55m95auW546L6ICFIiwiaG9zdCI6ImJhaS1waWFvLXdhbmctemhlLWlwbGM2Ljk4ODQ4Lnh5eiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDExNiIsImFkZCI6ImJhaS1waWFvLXdhbmctemhlLWlwbGM2Ljk4ODQ4Lnh5eiIsInBvcnQiOiI1OTk1OSIsInR5cGUiOiJub25lIiwiaWQiOiJmN2QyNmI1ZS04ZDc4LTQxNTQtODViNi1kNjllYThkZWEwZWEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3lvdXR1YnRA55m95auW546L6ICFIiwiaG9zdCI6ImJhaS1waWFvLXdhbmctemhlLWlwbGM2Ljk4ODQ4Lnh5eiIsInRscyI6IiJ9
    trojan://c8bae3de-16ed-4247-8a99-f38ef79a4b51@bai-piao-wang-zhe10.98848.xyz:48240?allowInsecure=1&sni=bai-piao-wang-zhe10.98848.xyz#_%E6%B2%B9%E7%AE%A1%EF%BC%9A%E5%85%A8%E7%BD%91%E6%9C%80%E5%BC%BA%E7%99%BD%E5%AB%96
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm73lnKPmlq/ogIPmi4nmlq/okoLljaHlpKflraYgMjMiLCJhZGQiOiIxNDMuMTEwLjE0NS4zMyIsInBvcnQiOiIxMjMxNSIsInR5cGUiOiJub25lIiwiaWQiOiI2MzI5N2MzOS0zZTY5LTRmZDAtODYzMi1kYTRjNzA4ZjEzOWYiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii9jaGF0IiwiaG9zdCI6IiIsInRscyI6IiJ9
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTozZjQxMWU4Ny0zZTkzLTRmMjMtYmMyMi0yNjNhNzQ4YmM4YzU@164.92.107.59:1645#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD11
    trojan://dfbf0d67-f03d-4184-a224-c2d64a571f99@s3.hazz.win:12340?allowInsecure=1&sni=edge.apple.com#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%20016
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA5MSIsImFkZCI6ImJhaS1waWFvLXdhbmctemhlLWlwbGM2Ljk4ODQ4Lnh5eiIsInBvcnQiOiI1OTk1OSIsInR5cGUiOiJub25lIiwiaWQiOiJmN2QyNmI1ZS04ZDc4LTQxNTQtODViNi1kNjllYThkZWEwZWEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3lvdXR1YnRA55m95auW546L6ICFIiwiaG9zdCI6ImJhaS1waWFvLXdhbmctemhlLWlwbGM2Ljk4ODQ4Lnh5eiIsInRscyI6IiJ9
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTozZjQxMWU4Ny0zZTkzLTRmMjMtYmMyMi0yNjNhNzQ4YmM4YzU@164.92.107.59:1645#%F0%9F%87%BA%F0%9F%87%B8%20github.com%2Ffreefq%20-%20%E7%BE%8E%E5%9B%BD%20%205
    trojan://dfbf0d67-f03d-4184-a224-c2d64a571f99@s3.hazz.win:12340?allowInsecure=1&sni=edge.apple.com#_%E6%B2%B9%E7%AE%A1%EF%BC%9A%E5%85%A8%E7%BD%91%E6%9C%80%E5%BC%BA%E7%99%BD%E5%AB%96
    ss://YWVzLTI1Ni1nY206M2Y0MTFlODctM2U5My00ZjIzLWJjMjItMjYzYTc0OGJjOGM1@164.92.99.255:4649#US_26
    trojan://d4e9e6bb-daa4-44ed-aa29-d1b8d00ba7d6@107.167.24.6:17001?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%20020
    trojan://d4e9e6bb-daa4-44ed-aa29-d1b8d00ba7d6@107.167.24.6:17001?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20US%208
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTozZjQxMWU4Ny0zZTkzLTRmMjMtYmMyMi0yNjNhNzQ4YmM4YzU@164.92.115.89:3125#%F0%9F%87%BA%F0%9F%87%B8%20github.com%2Ffreefq%20-%20%E7%BE%8E%E5%9B%BD%20%207
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA2MDgxNzE2IiwiYWRkIjoiMTQzLjExMC4xNDUuMzMiLCJwb3J0IjoiMTIzMTUiLCJ0eXBlIjoibm9uZSIsImlkIjoiNjMyOTdjMzktM2U2OS00ZmQwLTg2MzItZGE0YzcwOGYxMzlmIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6ImJhaS1waWFvLXdhbmctemhlMTAuOTg4NDgueHl6IiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA1MCIsImFkZCI6InVzYS1kYWxsYXMubHZ1ZnQuY29tIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJhYmE1MGRkNC01NDg0LTNiMDUtYjE0YS00NjYxY2FmODYyZDUiLCJhaWQiOiI0IiwibmV0Ijoid3MiLCJwYXRoIjoiL3dzIiwiaG9zdCI6InVzYS1kYWxsYXMubHZ1ZnQuY29tIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm73liqDliKnnpo/lsLzkuprlt57otLnliKnokplMaW5vZGXmlbDmja7kuK3lv4MgMTIiLCJhZGQiOiJ1czAxLmhlbmV0LmN5b3UiLCJwb3J0IjoiMjAwMDAiLCJ0eXBlIjoibm9uZSIsImlkIjoiODNmNWQ0ZjEtNDliMi00YWNlLWE1YWQtNDhkZjU4ZjRkYTUzIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9saXZlIiwiaG9zdCI6ImNjdHYuY29tIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDExMiIsImFkZCI6InVzMDEuaGVuZXQuY3lvdSIsInBvcnQiOiIyMDAwMCIsInR5cGUiOiJub25lIiwiaWQiOiI4M2Y1ZDRmMS00OWIyLTRhY2UtYTVhZC00OGRmNThmNGRhNTMiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2xpdmUiLCJob3N0IjoidXMwMS5oZW5ldC5jeW91IiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm73liqDliKnnpo/lsLzkuprlt57otLnliKnokplMaW5vZGXmlbDmja7kuK3lv4MgMTIiLCJhZGQiOiJ1czAxLmhlbmV0LmN5b3UiLCJwb3J0IjoiMjAwMDAiLCJ0eXBlIjoibm9uZSIsImlkIjoiODNmNWQ0ZjEtNDliMi00YWNlLWE1YWQtNDhkZjU4ZjRkYTUzIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9saXZlIiwiaG9zdCI6ImNjdHYuY29tIiwidGxzIjoiIn0=
    trojan://f0de3134-aef4-45b5-a135-3a82321bbac6@bai-piao-wang-zhe10.98848.xyz:50858?allowInsecure=1#_%E6%B2%B9%E7%AE%A1%EF%BC%9A%E5%85%A8%E7%BD%91%E6%9C%80%E5%BC%BA%E7%99%BD%E5%AB%96
    vmess://eyJ2IjoiMiIsInBzIjoiVVMwMS1WMi3nm7Tov54iLCJhZGQiOiJ1czAxLmhlbmV0LmN5b3UiLCJwb3J0IjoiMjAwMDAiLCJ0eXBlIjoibm9uZSIsImlkIjoiODNmNWQ0ZjEtNDliMi00YWNlLWE1YWQtNDhkZjU4ZjRkYTUzIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9saXZlIiwiaG9zdCI6ImNjdHYuY29tIiwidGxzIjoiIn0=
    ss://YWVzLTI1Ni1nY206M2Y0MTFlODctM2U5My00ZjIzLWJjMjItMjYzYTc0OGJjOGM1@164.92.99.255:4649#%F0%9F%87%BA%F0%9F%87%B8%20github.com%2Ffreefq%20-%20%E7%BE%8E%E5%9B%BD%20%206
    ss://YWVzLTI1Ni1nY206M2Y0MTFlODctM2U5My00ZjIzLWJjMjItMjYzYTc0OGJjOGM1@164.92.99.255:4649#%F0%9F%87%BA%F0%9F%87%B8%20%3A%E7%BE%8E%E5%9B%BD-ss-164.92.99.255%3A4649-%E5%8F%AF%E7%94%A8-%E7%9B%B4%E8%BF%9E-%E8%A7%A3%E9%94%81%E7%BE%8E%E5%9B%BD%E5%9C%B0%E5%8C%BANF%E9%9D%9E%E8%87%AA%E5%88%B6%E5%89%A7
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA4OSIsImFkZCI6ImJhaS1waWFvLXdhbmctemhlLWlwbGM2Ljk4ODQ4Lnh5eiIsInBvcnQiOiIzMTk2MSIsInR5cGUiOiJub25lIiwiaWQiOiI5NDMxMWU3MS05MTI1LTRiZDEtZmFhMi01MTVhODY2N2M0ODYiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3lvdXR1YnRA55m95auW546L6ICFIiwiaG9zdCI6ImJhaS1waWFvLXdhbmctemhlLWlwbGM2Ljk4ODQ4Lnh5eiIsInRscyI6IiJ9
    ss://YWVzLTI1Ni1nY206M2Y0MTFlODctM2U5My00ZjIzLWJjMjItMjYzYTc0OGJjOGM1@164.92.99.255:4649#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD13
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA2MDgxNzIwIiwiYWRkIjoiMTUwLjIzMC40My4xMDYiLCJwb3J0IjoiNTQ4MjkiLCJ0eXBlIjoibm9uZSIsImlkIjoiZjJiNWMzZmYtODZjNy00ZWZhLTgzMWYtZmYwZmNkNzY1NmE1IiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIveW91dHVidEDnmb3lq5bnjovogIUiLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA2MDg2NDAiLCJhZGQiOiJiYWktcGlhby13YW5nLXpoZS1pcGxjNi45ODg0OC54eXoiLCJwb3J0IjoiMzE5NjEiLCJ0eXBlIjoibm9uZSIsImlkIjoiOTQzMTFlNzEtOTEyNS00YmQxLWZhYTItNTE1YTg2NjdjNDg2IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii95b3V0dWJ0QOeZveWrlueOi+iAhSIsImhvc3QiOiJiYWktcGlhby13YW5nLXpoZS1pcGxjNi45ODg0OC54eXoiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA1OCIsImFkZCI6IjE1MC4yMzAuNDEuOSIsInBvcnQiOiIyMzI5MiIsInR5cGUiOiJub25lIiwiaWQiOiI5NTZjNmMyZi1iZjU0LTRiODctZmFmZC00Yjc2N2NhMTI3NTAiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii93cyIsImhvc3QiOiJ1c2Etd2FzaGluZ3Rvbi5sdnVmdC5jb20iLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA2MDg2NDAiLCJhZGQiOiJiYWktcGlhby13YW5nLXpoZS1pcGxjNi45ODg0OC54eXoiLCJwb3J0IjoiMzE5NjEiLCJ0eXBlIjoibm9uZSIsImlkIjoiOTQzMTFlNzEtOTEyNS00YmQxLWZhYTItNTE1YTg2NjdjNDg2IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii95b3V0dWJ0QOeZveWrlueOi+iAhSIsImhvc3QiOiJiYWktcGlhby13YW5nLXpoZS1pcGxjNi45ODg0OC54eXoiLCJ0bHMiOiIifQ==
    trojan://d4e9e6bb-daa4-44ed-aa29-d1b8d00ba7d6@107.167.24.6:17001?allowInsecure=1&sni=107.167.24.6#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD2
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggWzA2LTA5XXxvc2xvb2t8576O5Zu9KFVTKVVTQS9TYW5Kb3NlXzEzIiwiYWRkIjoiMTU1LjI0OC4yMDIuMjAzIiwicG9ydCI6IjE0NTY0IiwidHlwZSI6Im5vbmUiLCJpZCI6IjRhMGRhMzc5LWE3Y2MtNDM4OS04OGQ3LTQ1NTE0Yjg5Njg4MyIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA2MDg5OTYiLCJhZGQiOiIxNTAuMjMwLjQxLjkiLCJwb3J0IjoiMjMyOTIiLCJ0eXBlIjoibm9uZSIsImlkIjoiOTU2YzZjMmYtYmY1NC00Yjg3LWZhZmQtNGI3NjdjYTEyNzUwIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA2MDYxMTA0IiwiYWRkIjoiYmFpLXBpYW8td2FuZy16aGUtaXBsYzYuOTg4NDgueHl6IiwicG9ydCI6IjMxOTYxIiwidHlwZSI6Im5vbmUiLCJpZCI6Ijk0MzExZTcxLTkxMjUtNGJkMS1mYWEyLTUxNWE4NjY3YzQ4NiIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIveW91dHVidEDnmb3lq5bnjovogIUiLCJob3N0IjoiYmFpLXBpYW8td2FuZy16aGUtaXBsYzYuOTg4NDgueHl6IiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA3MSIsImFkZCI6IjE1MC4yMzAuNDEuOSIsInBvcnQiOiIyMzI5MiIsInR5cGUiOiJub25lIiwiaWQiOiI5NTZjNmMyZi1iZjU0LTRiODctZmFmZC00Yjc2N2NhMTI3NTAiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii93cyIsImhvc3QiOiJ1c2Etd2FzaGluZ3Rvbi5sdnVmdC5jb20iLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA2MDg2NDAiLCJhZGQiOiJiYWktcGlhby13YW5nLXpoZS1pcGxjNi45ODg0OC54eXoiLCJwb3J0IjoiMzE5NjEiLCJ0eXBlIjoibm9uZSIsImlkIjoiOTQzMTFlNzEtOTEyNS00YmQxLWZhYTItNTE1YTg2NjdjNDg2IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii95b3V0dWJ0QOeZveWrlueOi+iAhSIsImhvc3QiOiJiYWktcGlhby13YW5nLXpoZS1pcGxjNi45ODg0OC54eXoiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA1NSIsImFkZCI6InU0LmFubXUub25lIiwicG9ydCI6IjE2MTY2IiwidHlwZSI6Im5vbmUiLCJpZCI6IjgyMjg1NTBlLTdmNTMtNDgwOS04Y2IxLTVmOTQyMDM4MGQxMyIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiL3dzIiwiaG9zdCI6InVzYS13YXNoaW5ndG9uLmx2dWZ0LmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA1MyIsImFkZCI6InVzYS13YXNoaW5ndG9uLmx2dWZ0LmNvbSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYWJhNTBkZDQtNTQ4NC0zYjA1LWIxNGEtNDY2MWNhZjg2MmQ1IiwiYWlkIjoiNCIsIm5ldCI6IndzIiwicGF0aCI6Ii93cyIsImhvc3QiOiJ1c2Etd2FzaGluZ3Rvbi5sdnVmdC5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA4NyIsImFkZCI6InVzYS1kYWxsYXMubHZ1ZnQuY29tIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJhYmE1MGRkNC01NDg0LTNiMDUtYjE0YS00NjYxY2FmODYyZDUiLCJhaWQiOiI0IiwibmV0Ijoid3MiLCJwYXRoIjoiL3dzIiwiaG9zdCI6InVzYS1kYWxsYXMubHZ1ZnQuY29tIiwidGxzIjoidGxzIn0=
    trojan://d4e9e6bb-daa4-44ed-aa29-d1b8d00ba7d6@107.167.24.6:17001?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%20002
    trojan://d4e9e6bb-daa4-44ed-aa29-d1b8d00ba7d6@107.167.24.6:17001?allowInsecure=1&sni=107.167.24.6#%F0%9F%87%BA%F0%9F%87%B8%20US
    trojan://f39bd244-f5fe-415c-8b98-a1e5250bf178@fhcarm2.gaox.ml:443?allowInsecure=0#%F0%9F%87%BA%F0%9F%87%B8%20Relay_%F0%9F%87%BA%F0%9F%87%B8US-%F0%9F%87%BA%F0%9F%87%B8US_40
    trojan://05742120-ce23-4cc8-88f5-6d221ce45bf4@fhcarm1.gaox.ml:443?allowInsecure=0#%F0%9F%87%BA%F0%9F%87%B8%20US-%E9%AB%98%E9%80%9F%E8%8A%82%E7%82%B9%E6%8E%A8%E8%8D%90%EF%BC%9Av1.mk%2Fvip
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA2MCIsImFkZCI6InVzMi5hc2FzYXMudG9wIiwicG9ydCI6IjE4MTE3IiwidHlwZSI6Im5vbmUiLCJpZCI6IjgwZWZhNzFiLWExNjQtMzA1Ny1iZGZkLWVkMjg1MjEyNTZmZSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvdjJyYXkiLCJob3N0IjoidXMyLmFzYXNhcy50b3AiLCJ0bHMiOiJ0bHMifQ==
    trojan://d4e9e6bb-daa4-44ed-aa29-d1b8d00ba7d6@107.167.24.6:17001?allowInsecure=1#US009
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA2MDg2NDQiLCJhZGQiOiIyMDguOTguNDguMiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYWJhNTBkZDQtNTQ4NC0zYjA1LWIxNGEtNDY2MWNhZjg2MmQ1IiwiYWlkIjoiNCIsIm5ldCI6IndzIiwicGF0aCI6Ii93cyIsImhvc3QiOiJpZXNlaTFlaS5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA3MyIsImFkZCI6InU0LmFubXUub25lIiwicG9ydCI6IjE2MTk5IiwidHlwZSI6Im5vbmUiLCJpZCI6IjA3ZWM1OWRhLTE4YWQtNDIyNC04YWQ5LWM1YTY2YjE0NDdhOSIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiL3dzIiwiaG9zdCI6InVzYS1kYWxsYXMubHZ1ZnQuY29tIiwidGxzIjoidGxzIn0=
    trojan://dbf9bf9c-2c3f-474a-8031-d4c00666a989@fhcamd2.gaox.ml:443?allowInsecure=1&sni=fhcamd2.gaox.ml#%F0%9F%87%BA%F0%9F%87%B8%20%28Youtube%E6%8A%80%E6%9C%AF%E5%88%86%E4%BA%AB%E5%AE%A4%29%F0%9F%87%BA%F0%9F%87%B8%E7%BE%8E%E5%9B%BD%2039
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA1OSIsImFkZCI6IjQ1LjM1Ljg0LjE2MiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYWJhNTBkZDQtNTQ4NC0zYjA1LWIxNGEtNDY2MWNhZjg2MmQ1IiwiYWlkIjoiNCIsIm5ldCI6IndzIiwicGF0aCI6Ii93cyIsImhvc3QiOiJ1c2EtZGFsbGFzLmx2dWZ0LmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA2MDg2NTgiLCJhZGQiOiIxNTAuMjMwLjQzLjEwNiIsInBvcnQiOiI1NDgyOSIsInR5cGUiOiJub25lIiwiaWQiOiJmMmI1YzNmZi04NmM3LTRlZmEtODMxZi1mZjBmY2Q3NjU2YTUiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii9IOFZzd3RVSi8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    trojan://d4e9e6bb-daa4-44ed-aa29-d1b8d00ba7d6@107.167.24.6:17001?allowInsecure=1#US_182%20TG%40peekfun%20%7C%203.06Mb
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA2MDg2NDYiLCJhZGQiOiJ1czIuYXNhc2FzLnRvcCIsInBvcnQiOiIxODExNyIsInR5cGUiOiJub25lIiwiaWQiOiI4MGVmYTcxYi1hMTY0LTMwNTctYmRmZC1lZDI4NTIxMjU2ZmUiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3YycmF5IiwiaG9zdCI6InVzMi5hc2FzYXMudG9wIiwidGxzIjoidGxzIn0=
    trojan://dbf9bf9c-2c3f-474a-8031-d4c00666a989@fhcamd2.gaox.ml:443?allowInsecure=1&sni=fhcamd2.gaox.ml#%F0%9F%87%BA%F0%9F%87%B8%20%28Youtube%E6%8A%80%E6%9C%AF%E5%88%86%E4%BA%AB%E5%AE%A4%29%F0%9F%87%BA%F0%9F%87%B8%E7%BE%8E%E5%9B%BD%2039
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA2MDg2NTYiLCJhZGQiOiI2Ny4yMS43Mi40MSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMjU2NmQwMGYtMjE4Yy00OGY3LTlhMzYtMTNkM2Q2ZjFhNzI0IiwiYWlkIjoiNjQiLCJuZXQiOiJ3cyIsInBhdGgiOiIvcGF0aC8xNzM0MTgxNDExMjMiLCJob3N0Ijoid3d3LjE3MDgwMTAwLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA2OCIsImFkZCI6InU0LmFubXUub25lIiwicG9ydCI6IjE2MTY2IiwidHlwZSI6Im5vbmUiLCJpZCI6IjgyMjg1NTBlLTdmNTMtNDgwOS04Y2IxLTVmOTQyMDM4MGQxMyIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiL3dzIiwiaG9zdCI6InVzYS13YXNoaW5ndG9uLmx2dWZ0LmNvbSIsInRscyI6InRscyJ9
    trojan://05742120-ce23-4cc8-88f5-6d221ce45bf4@fhcarm1.gaox.ml:443?allowInsecure=0#%F0%9F%87%BA%F0%9F%87%B8%20US-%E9%AB%98%E9%80%9F%E8%8A%82%E7%82%B9%E6%8E%A8%E8%8D%90%EF%BC%9Av1.mk%2Fvip
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA0OCIsImFkZCI6IjY3LjIxLjcyLjQxIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIyNTY2ZDAwZi0yMThjLTQ4ZjctOWEzNi0xM2QzZDZmMWE3MjQiLCJhaWQiOiI2NCIsIm5ldCI6IndzIiwicGF0aCI6Ii9wYXRoLzE3MzQxODE0MTEyMyIsImhvc3QiOiJ3d3cuMTcwODAxMDAueHl6IiwidGxzIjoidGxzIn0=

</details>

### 所有节点
合并节点总数: `5762`
[节点链接](https://raw.githubusercontent.com/alanbobs999/TopFreeProxies/master/sub/sub_merge.txt)

### 节点来源
- [pojiezhiyuanjun/freev2](https://github.com/pojiezhiyuanjun/freev2), 节点数量: `72`
- [chfchf0306/clash](https://github.com/chfchf0306/clash), 节点数量: `174`
- [xiyaowong/freeFQ](https://github.com/xiyaowong/freeFQ), 节点数量: `110`
- [freefq/free](https://github.com/freefq/free), 节点数量: `39`
- [learnhard-cn/free_proxy_ss](https://github.com/learnhard-cn/free_proxy_ss), 节点数量: `182`
- [vpei/Free-Node-Merge](https://github.com/vpei/Free-Node-Merge), 节点数量: `100`
- [colatiger/v2ray-nodes](https://github.com/colatiger/v2ray-nodes), 节点数量: `40`
- [oslook/clash-freenode](https://github.com/oslook/clash-freenode), 节点数量: `42`
- [ssrsub/ssr](https://github.com/ssrsub/ssr), 节点数量: `57`
- [Leon406/SubCrawler](https://github.com/Leon406/SubCrawler), 节点数量: `2757`
- [yu-steven/openit](https://github.com/yu-steven/openit), 节点数量: `104`
- [iwxf/free-v2ray](https://github.com/iwxf/free-v2ray), 节点数量: `8`
- [gooooooooooooogle/Clash-Config](https://github.com/gooooooooooooogle/Clash-Config), 节点数量: `42`
- [Jsnzkpg/Jsnzkpg](https://github.com/Jsnzkpg/Jsnzkpg), 节点数量: `50`
- [ermaozi/get_subscribe](https://github.com/ermaozi/get_subscribe), 节点数量: `145`
- [wrfree/free](https://github.com/wrfree/free), 节点数量: `39`
- [GreenFishStudio/GreenFish](https://github.com/GreenFishStudio/GreenFish), 节点数量: `56`
- [tomdegnan/clashrule](https://github.com/tomdegnan/clashrule), 节点数量: `214`
- [changfengoss](https://github.com/ronghuaxueleng/get_v2), 节点数量: `86`
- [anaer/Sub](https://github.com/anaer/Sub), 节点数量: `236`
- [xrayfree/free-ssr-ss-v2ray-vpn-clash](https://github.com/xrayfree/free-ssr-ss-v2ray-vpn-clash), 节点数量: `68`
- [mhmhone/shadowrocket-free-subscribe](https://github.com/mhmhone/shadowrocket-free-subscribe), 节点数量: `30`
- [aiboboxx/v2rayfree](https://github.com/aiboboxx/v2rayfree), 节点数量: `31`
- [moneyfly1/sublist](https://github.com/moneyfly1/sublist), 节点数量: `172`
- [poduv/poduv](https://github.com/poduv/poduv), 节点数量: `75`
- [ok1991/v2ray](https://github.com/ok1991/v2ray), 节点数量: `39`
- [parkerpa/jsfxs](https://github.com/parkerpa/jsfxs), 节点数量: `582`
- [Pawdroid/Free-servers](https://github.com/Pawdroid/Free-servers), 节点数量: `12`
- [Nodefree.org](https://github.com/Fukki-Z/nodefree), 节点数量: `101`

## 客户端选择
### 主流桌面客户端
|                            MacOS                             |                            Linux                             |                           Windows                            | 简易描述                                           |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :------------------------------------------------- |
| [CFW](https://github.com/Fndroid/clash_for_windows_pkg/releases) | [CFW](https://github.com/Fndroid/clash_for_windows_pkg/releases) | [CFW(Clash For Windows)](https://github.com/Fndroid/clash_for_windows_pkg/releases) | SS, SSR, Trojan, Vmess, VLESS协议支持，策略分流能力强。            |
|     [Qv2ray](https://github.com/Qv2ray/Qv2ray/releases)      |     [Qv2ray](https://github.com/Qv2ray/Qv2ray/releases)      |     [Qv2ray](https://github.com/Qv2ray/Qv2ray/releases)      | SS, SSR, Trojan, Vmess, VLESS, Trojan-Go协议支持（需安装相关插件）。 |
|                              ×                               |                              ×                               |      [V2rayN](https://github.com/2dust/v2rayN/releases)      | SS, Trojan, Vmess, VLESS协议支持，有测速，测延迟功能，支持订阅，二维码，剪贴板导入及手动配置。                 |
|                              ×                               |                              ×                               |    [WinXray](https://github.com/TheMRLL/winxray/releases)    | SS, SSR, Trojan, Vmess, VLESS协议支持，支持自动连接最快节点。            |
|                              ×                               |                              ×                               | [Shadowsocks-windows](https://github.com/shadowsocks/shadowsocks-windows/releases) | SS协议支持， SS 专用客户端。                                       |
|                              ×                               |                              ×                               | [ShadowsocksR-windows](https://github.com/HMBSbige/ShadowsocksR-Windows/releases) | SSR协议支持，SSR 专用客户端。                                      |
|                [Surge](https://nssurge.com/)                 |                              ×                               |                              ×                               | SS, Trojan, Vmess协议支持，著名网络调试工具，策略分流能力强大，需付费。                        |
|   [ClashX](https://github.com/yichengchen/clashX/releases)   |                              ×                               |                              ×                               | SS, SSR, Trojan, Vmess协议支持，占用资源较少。                   |
|      [V2rayU](https://github.com/yanue/V2rayU/releases)      |                              ×                               |                              ×                               | SS, Trojan, Vmess协议支持，支持订阅，二维码，剪贴板导入，手动配置，二维码分享，与 V2RayN 类似。                        |

### 主流移动客户端
|                          iOS/iPadOS                          |                           Android                            | 简易描述                                                     |
| :----------------------------------------------------------: | :----------------------------------------------------------: | ------------------------------------------------------------ |
| [Shadowrocket](https://apps.apple.com/us/app/shadowrocket/id932747118) | [Shadowrocket](https://play.google.com/store/apps/details?id=com.v2cross.proxy) | SS, SSR, Trojan, Vmess, VLESS协议支持，iOS端需在非国区 App Store 购买，美区售价 $2.99；安卓端非与 iOS 端同一作者，不支持 SSR 协议，免费且内置免费节点。 |
|                [Surge](https://nssurge.com/)                 |                              ×                               | SS, Trojan, Vmess协议支持，iOS 端著名网络调试工具，需付费。                                  |
| [Quantumult X](https://apps.apple.com/us/app/quantumult-x/id1443988620) |                              ×                               | SS, SSR, Trojan, Vmess协议支持，需在非国区AppStore购买，美区售价$4.99。 |
| [Potatso Lite](https://apps.apple.com/us/app/potatso-lite/id1239860606) |                              ×                               | SS, SSR协议支持，需在非国区AppStore购买，免费。              |
|                              ×                               | [Surfboard](https://play.google.com/store/apps/details?id=com.getsurfboard) | SS, SSR, Vmess协议支持，安卓端网络调试软件，兼容 Surge 2 配置。 |
|                              ×                               | [CFA(Clash For Android)](https://github.com/Kr328/ClashForAndroid/releases) | SS, SSR, Trojan, Vmess协议支持。                             |
|                              ×                               |  [SagerNet](https://github.com/SagerNet/SagerNet/releases)   | SS, SSR, Trojan, Vmess, VLESS协议支持。                      |
|                              ×                               | [Shadowsocks-android](https://github.com/shadowsocks/shadowsocks-android/releases) | SS协议支持，安卓专用 SS 客户端。                                                 |
|                              ×                               | [ShadowsocksR-android](https://github.com/HMBSbige/ShadowsocksR-Android/releases) | SSR协议支持，安卓专用 SSR 客户端。                                                |
|                              ×                               |     [V2rayNG](https://github.com/2dust/v2rayNG/releases)     | SS, Trojan, Vmess, VLESS协议支持，v2ray 内核。                           |

## 机场推荐
免费节点失效太快，推荐一些性价比高的机场应急使用。
- [魔戒.net](https://www.mojie.cyou/#/register?code=sAbl0qtT)
  - 按量计费机场, 1¥10G, 10¥130G
  - 所有套餐均是一样的节点与一样的服务，所有套餐流量永不过期，用完为止，不限制客户端数量，最高可提供 2Gbps 峰值
- [大迅云](https://daxun.club/#/register?code=JPmAFPav)
  - 最低月付 5¥50G, 12¥200G, 购买 12¥ 及以上套餐免费领取奈飞 + 迪士尼 Plus 共享号
  - 原生IP负载均衡，流媒体解锁晚高峰油管秒开，主打性价比，有试用
- [阿伟云](https://awslcn.xyz/#/register?code=8C18uZwl)
  - 最低月付 1¥ 起, 9.99¥100G
  - 无带宽速率限制，有流媒体解锁，香港 BGP 中继线路

## 仓库声明
订阅节点仅作学习交流使用，只是对网络上节点的优选排序，用于查找资料，学习知识，不做任何违法行为。所有资源均来自互联网，仅供大家交流学习使用，出现违法问题概不负责。

## 星标统计
[![Star History Chart](https://api.star-history.com/svg?repos=alanbobs999/TopFreeProxies&type=Date)](https://star-history.com/#alanbobs999/TopFreeProxies&Date)