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

    trojan://dfbf0d67-f03d-4184-a224-c2d64a571f99@s3.hazz.win:12340?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20US%2019%20%E2%86%92%20TG%40SCINV
    ss://YWVzLTI1Ni1nY206ODhneTU2aDk@104.237.154.158:864#%E8%BF%99%E4%BA%9B%E8%8A%82%E7%82%B9%E5%8F%AA%E8%83%BD%E5%A4%87%E7%94%A8%E6%88%96%E8%80%85%E9%98%B2%E6%AD%A2%E5%A4%B1%E8%81%94%EF%BC%8C%E8%99%BD%E7%84%B6%E8%B4%A8%E9%87%8F%E5%B9%B6%E4%B8%8D%E6%98%AF%E5%BE%88%E5%A5%BD%EF%BC%8C%E4%B9%9F%E8%AF%B7%E4%BD%8E%E8%B0%83%E4%BD%BF%E7%94%A8%3A%29
    trojan://dfbf0d67-f03d-4184-a224-c2d64a571f99@s3.hazz.win:12340?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%20019
    trojan://e4abe563-0f1b-4262-9535-bef102f25f8c@80.251.216.13:50500?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20US%2023%20%E2%86%92%20TG%40SCINV
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggX1VTX+e+juWbvV8xIiwiYWRkIjoibHo3NC5haWppYXN1Lnh5eiIsInBvcnQiOiIzNTU3NSIsInR5cGUiOiJub25lIiwiaWQiOiJkNWNlMzc4OC0wMzExLTQ5NGEtZWIxZC01OWU2YzFhOTBjY2IiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoibHo3NC5haWppYXN1Lnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggdjJyYXlmcmVlLmV1Lm9yZyAtIOe+juWbveWuvuWkleazleWwvOS6muW3nuaLieWFi+S4h+e6s+WOv+WFi+aLieWFi+aWr+iQqOWvhueJueiHquayu+WMulZvbHVtZURyaXZl6IKh5Lu95pyJ6ZmQ5YWs5Y+4IDI0IiwiYWRkIjoibHo3NC5haWppYXN1Lnh5eiIsInBvcnQiOiIzNTU3NSIsInR5cGUiOiJub25lIiwiaWQiOiJkNWNlMzc4OC0wMzExLTQ5NGEtZWIxZC01OWU2YzFhOTBjY2IiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoibHo3NC5haWppYXN1Lnh5eiIsInRscyI6InRscyJ9
    ss://YWVzLTI1Ni1nY206ODhneTU2aDk@104.237.154.158:864#%E8%BF%99%E4%BA%9B%E8%8A%82%E7%82%B9%E5%8F%AA%E8%83%BD%E5%A4%87%E7%94%A8%E6%88%96%E8%80%85%E9%98%B2%E6%AD%A2%E5%A4%B1%E8%81%94%EF%BC%8C%E8%99%BD%E7%84%B6%E8%B4%A8%E9%87%8F%E5%B9%B6%E4%B8%8D%E6%98%AF%E5%BE%88%E5%A5%BD%EF%BC%8C%E4%B9%9F%E8%AF%B7%E4%BD%8E%E8%B0%83%E4%BD%BF%E7%94%A8%3A%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm73lrr7lpJXms5XlsLzkuprlt57mi4nlhYvkuIfnurPljr/lhYvmi4nlhYvmlq/okKjlr4bnibnoh6rmsrvljLpWb2x1bWVEcml2ZeiCoeS7veaciemZkOWFrOWPuCAyNCIsImFkZCI6Imx6NzQuYWlqaWFzdS54eXoiLCJwb3J0IjoiMzU1NzUiLCJ0eXBlIjoibm9uZSIsImlkIjoiZDVjZTM3ODgtMDMxMS00OTRhLWViMWQtNTllNmMxYTkwY2NiIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6Imx6NzQuYWlqaWFzdS54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm73lrr7lpJXms5XlsLzkuprlt57mi4nlhYvkuIfnurPljr/lhYvmi4nlhYvmlq/okKjlr4bnibnoh6rmsrvljLpWb2x1bWVEcml2ZeiCoeS7veaciemZkOWFrOWPuCAyNCIsImFkZCI6Imx6NzQuYWlqaWFzdS54eXoiLCJwb3J0IjoiMzU1NzUiLCJ0eXBlIjoibm9uZSIsImlkIjoiZDVjZTM3ODgtMDMxMS00OTRhLWViMWQtNTllNmMxYTkwY2NiIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6Imx6NzQuYWlqaWFzdS54eXoiLCJ0bHMiOiJ0bHMifQ==
    trojan://3df66137-a428-429c-a858-8b150721b354@us23.567568.ml:27956?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%20011
    trojan://2ad895a4-90e1-460d-9291-bbfb3463190e@45.33.61.143:443?allowInsecure=0&sni=www.download.windowsupdate1.com#1111
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm71EWEMgVGVjaG5vbG9neSAyOCIsImFkZCI6IjIwLjEwNi43NC4xNyIsInBvcnQiOiIyMzY5MCIsInR5cGUiOiJub25lIiwiaWQiOiI0OTI4MDg1ZC02MzdlLTRiOWUtZTI2ZC1lMTQ2MjdhNDVjNDYiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLzc4OWsiLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDE0NCIsImFkZCI6IjIwLjEwNi43NC4xNyIsInBvcnQiOiIyMzY5MCIsInR5cGUiOiJub25lIiwiaWQiOiI0OTI4MDg1ZC02MzdlLTRiOWUtZTI2ZC1lMTQ2MjdhNDVjNDYiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLzc4OWsiLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA3NyIsImFkZCI6InZmbHk5LndpbiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiODM4YmU5ZWQtZDdhOC00ZGExLWIwNjctYjk1ZDJhODc4MmY1IiwiYWlkIjoiMTAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvbXlibG9nIiwiaG9zdCI6InZmbHk5LndpbiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggdjJyYXlmcmVlLmV1Lm9yZyAtIOe+juWbvURYQyBUZWNobm9sb2d5IDI4IiwiYWRkIjoiMjAuMTA2Ljc0LjE3IiwicG9ydCI6IjIzNjkwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjQ5MjgwODVkLTYzN2UtNGI5ZS1lMjZkLWUxNDYyN2E0NWM0NiIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvNzg5ayIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDExMCIsImFkZCI6InZmbHk5LndpbiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiODM4YmU5ZWQtZDdhOC00ZGExLWIwNjctYjk1ZDJhODc4MmY1IiwiYWlkIjoiMTAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvbXlibG9nIiwiaG9zdCI6InZmbHk5LndpbiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA3OSIsImFkZCI6InZmbHk5LndpbiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiODM4YmU5ZWQtZDdhOC00ZGExLWIwNjctYjk1ZDJhODc4MmY1IiwiYWlkIjoiMTAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvbXlibG9nIiwiaG9zdCI6InZmbHk5LndpbiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggdjJyYXlmcmVlLmV1Lm9yZyAtIOe+juWbveWKoOWIqeemj+WwvOS6muW3nuWco+S9leWhnkNob29wYeaVsOaNruS4reW/gyA1IiwiYWRkIjoiMTA0LjE1Ni4yMjkuMTQ4IiwicG9ydCI6IjM2Nzg4IiwidHlwZSI6Im5vbmUiLCJpZCI6IjlmZWU3MjQ5LTY5ZmItNDkwZC1lNjE3LWNmYjU0YTI0OTkzMiIsImFpZCI6IjYwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm71DbG91ZEZsYXJl6IqC54K5IDM4IiwiYWRkIjoidmZseTkud2luIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI4MzhiZTllZC1kN2E4LTRkYTEtYjA2Ny1iOTVkMmE4NzgyZjUiLCJhaWQiOiIxMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9teWJsb2ciLCJob3N0IjoidmZseTkud2luIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi6L+Z5Lqb6IqC54K55Y+q6IO95aSH55So5oiW6ICF6Ziy5q2i5aSx6IGU77yM6Jm954S26LSo6YeP5bm25LiN5piv5b6I5aW977yM5Lmf6K+35L2O6LCD5L2/55SoOikiLCJhZGQiOiIyMy4yMzAuMTQ2LjI1NCIsInBvcnQiOiIxMjU4IiwidHlwZSI6Im5vbmUiLCJpZCI6ImVkZWI0MWNjLWE3NmEtNDdmMi1mYTk2LWI5MTQxZTY2YTJiMCIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIyMy4yMzAuMTQ2LjI1NCIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9KOe7v+WktOWklue9kembhuWboikoUHVibGljKSIsImFkZCI6InVzMDIuZ29nb2dvby5jeW91IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJkYjVkMWFhMy05MDhiLTQ0ZDEtYmUwYS00ZTZhOGQ0ZTRjZGEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2dvIiwiaG9zdCI6InVzMDIuZ29nb2dvby5jeW91IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm71DbG91ZEZsYXJl6IqC54K5IDM0IiwiYWRkIjoidmZseTkud2luIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI4MzhiZTllZC1kN2E4LTRkYTEtYjA2Ny1iOTVkMmE4NzgyZjUiLCJhaWQiOiIxMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9teWJsb2ciLCJob3N0IjoidmZseTkud2luIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDljJfnvo7lnLDljLogIDYxIiwiYWRkIjoiMjMuMjMwLjE0Ni4yNTQiLCJwb3J0IjoiMTI1OCIsInR5cGUiOiJub25lIiwiaWQiOiJlZGViNDFjYy1hNzZhLTQ3ZjItZmE5Ni1iOTE0MWU2NmEyYjAiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii9wYXRoLzI3MzIxMzA3MDkzMyIsImhvc3QiOiI1MS4xOTUuMzUuMTM0IiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggdjJyYXlmcmVlLmV1Lm9yZyAtIOe+juWbvUNsb3VkRmxhcmXoioLngrkgMzQiLCJhZGQiOiJ2Zmx5OS53aW4iLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjgzOGJlOWVkLWQ3YTgtNGRhMS1iMDY3LWI5NWQyYTg3ODJmNSIsImFpZCI6IjEwIiwibmV0Ijoid3MiLCJwYXRoIjoiL215YmxvZyIsImhvc3QiOiJ2Zmx5OS53aW4iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDEwOSIsImFkZCI6IjEwNC4xNTYuMjI5LjE0OCIsInBvcnQiOiIzNjc4OCIsInR5cGUiOiJub25lIiwiaWQiOiI5ZmVlNzI0OS02OWZiLTQ5MGQtZTYxNy1jZmI1NGEyNDk5MzIiLCJhaWQiOiI2MCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoiMTA0LjE1Ni4yMjkuMTQ4IiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm71DbG91ZEZsYXJl5YWs5Y+4Q0RO6IqC54K5IDE3IiwiYWRkIjoid3d3LmRpZ2l0YWxvY2Vhbi5jb20iLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjNkZjY2MTM3LWE0MjgtNDI5Yy1hODU4LThiMTUwNzIxYjM1NCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIveW91dGJ1ZUBiYWktcGlhby13YW5nLXpoZV92d3MiLCJob3N0IjoidXMyMy41Njc1NjgubWwiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDE3MiIsImFkZCI6IjIwLjEwNi43NC4xNyIsInBvcnQiOiIyMzY5MCIsInR5cGUiOiJub25lIiwiaWQiOiI0OTI4MDg1ZC02MzdlLTRiOWUtZTI2ZC1lMTQ2MjdhNDVjNDYiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLzc4OWsiLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA3MzAwMjIiLCJhZGQiOiJ2Zmx5OS53aW4iLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjgzOGJlOWVkLWQ3YTgtNGRhMS1iMDY3LWI5NWQyYTg3ODJmNSIsImFpZCI6IjEwIiwibmV0Ijoid3MiLCJwYXRoIjoiL215YmxvZyIsImhvc3QiOiJ2Zmx5OS53aW4iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA3MzAwMzIiLCJhZGQiOiJ1czAyLmdvZ29nb28uY3lvdSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiZGI1ZDFhYTMtOTA4Yi00NGQxLWJlMGEtNGU2YThkNGU0Y2RhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9nbyIsImhvc3QiOiJ1czAyLmdvZ29nb28uY3lvdSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm73liqDliKnnpo/lsLzkuprlt57lnKPkvZXloZ5DaG9vcGHmlbDmja7kuK3lv4MgNSIsImFkZCI6IjEwNC4xNTYuMjI5LjE0OCIsInBvcnQiOiIzNjc4OCIsInR5cGUiOiJub25lIiwiaWQiOiI5ZmVlNzI0OS02OWZiLTQ5MGQtZTYxNy1jZmI1NGEyNDk5MzIiLCJhaWQiOiI2MCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm71EWEMgVGVjaG5vbG9neSAyOCIsImFkZCI6IjIwLjEwNi43NC4xNyIsInBvcnQiOiIyMzY5MCIsInR5cGUiOiJub25lIiwiaWQiOiI0OTI4MDg1ZC02MzdlLTRiOWUtZTI2ZC1lMTQ2MjdhNDVjNDYiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLzc4OWsiLCJob3N0IjoiIiwidGxzIjoiIn0=
    trojan://f39bd244-f5fe-415c-8b98-a1e5250bf178@fhcarm2.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20US%2015%20%E2%86%92%20TG%40SCINV
    trojan://05742120-ce23-4cc8-88f5-6d221ce45bf4@fhcarm1.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%20016
    trojan://sharecentre@ussc.scsevers.cf:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20US%2024%20%E2%86%92%20TG%40SCINV
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA3NCIsImFkZCI6Ijk2LjQzLjg2LjI4IiwicG9ydCI6IjI2OTM3IiwidHlwZSI6Im5vbmUiLCJpZCI6ImIxODlkOGJlLTI3M2ItNDQ4Ny1hM2MxLTdkZGQ4OGZiNzU1OCIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiL2hlbGxvIiwiaG9zdCI6IjEwNy4xNzMuMTY2LjE2MCIsInRscyI6IiJ9
    trojan://05742120-ce23-4cc8-88f5-6d221ce45bf4@fhcarm1.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%20013
    vmess://eyJ2IjoiMiIsInBzIjoi6L+Z5Lqb6IqC54K55Y+q6IO95aSH55So5oiW6ICF6Ziy5q2i5aSx6IGU77yM6Jm954S26LSo6YeP5bm25LiN5piv5b6I5aW977yM5Lmf6K+35L2O6LCD5L2/55SoOikiLCJhZGQiOiIyMC4xMDYuNzQuMTciLCJwb3J0IjoiMjM2OTAiLCJ0eXBlIjoibm9uZSIsImlkIjoiNDkyODA4NWQtNjM3ZS00YjllLWUyNmQtZTE0NjI3YTQ1YzQ2IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii83ODlrIiwiaG9zdCI6IjIwLjEwNi43NC4xNyIsInRscyI6IiJ9
    trojan://f39bd244-f5fe-415c-8b98-a1e5250bf178@fhcarm2.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%28%E7%BB%BF%E5%A4%B4%E5%A4%96%E7%BD%91%E9%9B%86%E5%9B%A2%29%28Public%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggUmVsYXlf8J+HuvCfh7hVUy3wn4e68J+HuFVTXzY1IiwiYWRkIjoidXNhLWRhbGxhcy5sdnVmdC5jb20iLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImFiYTUwZGQ0LTU0ODQtM2IwNS1iMTRhLTQ2NjFjYWY4NjJkNSIsImFpZCI6IjQiLCJuZXQiOiJ3cyIsInBhdGgiOiIvd3MiLCJob3N0IjoidXNhLWRhbGxhcy5sdnVmdC5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA3MjYyODgiLCJhZGQiOiIxNTguMTAxLjE5LjE3MiIsInBvcnQiOiIxMDkxMCIsInR5cGUiOiJodHRwIiwiaWQiOiIyNDE2NDVmNS0zMTkwLTQyOWItYjUxMy01MjY1YTI0MmRmZTEiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiQFNTUlNVQi1WNzIt5LuY6LS55o6o6I2QOnN1by55dC9zc3JzdWIiLCJhZGQiOiIxNTguMTAxLjE5LjE3MiIsInBvcnQiOiIxMDkxMCIsInR5cGUiOiJodHRwIiwiaWQiOiIyNDE2NDVmNS0zMTkwLTQyOWItYjUxMy01MjY1YTI0MmRmZTEiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA3MzAwMjkiLCJhZGQiOiIxNTguMTAxLjE5LjE3MiIsInBvcnQiOiIxMDkxMCIsInR5cGUiOiJodHRwIiwiaWQiOiIyNDE2NDVmNS0zMTkwLTQyOWItYjUxMy01MjY1YTI0MmRmZTEiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    trojan://f39bd244-f5fe-415c-8b98-a1e5250bf178@fhcarm2.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%28%E7%BB%BF%E5%A4%B4%E5%A4%96%E7%BD%91%E9%9B%86%E5%9B%A2%29%28Public%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA3MzAwMjkiLCJhZGQiOiIxNTguMTAxLjE5LjE3MiIsInBvcnQiOiIxMDkxMCIsInR5cGUiOiJodHRwIiwiaWQiOiIyNDE2NDVmNS0zMTkwLTQyOWItYjUxMy01MjY1YTI0MmRmZTEiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    trojan://f39bd244-f5fe-415c-8b98-a1e5250bf178@fhcarm2.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%20012
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA3MzAwMjkiLCJhZGQiOiIxNTguMTAxLjE5LjE3MiIsInBvcnQiOiIxMDkxMCIsInR5cGUiOiJodHRwIiwiaWQiOiIyNDE2NDVmNS0zMTkwLTQyOWItYjUxMy01MjY1YTI0MmRmZTEiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    trojan://f39bd244-f5fe-415c-8b98-a1e5250bf178@fhcarm2.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%20010
    trojan://f39bd244-f5fe-415c-8b98-a1e5250bf178@fhcarm2.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%28%E7%BB%BF%E5%A4%B4%E5%A4%96%E7%BD%91%E9%9B%86%E5%9B%A2%29%28Public%29
    trojan://2ad895a4-90e1-460d-9291-bbfb3463190e@45.33.61.143:443?allowInsecure=0&sni=www.download.windowsupdate1.com#1111
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA4OSIsImFkZCI6Ijk2LjQzLjg2LjI4IiwicG9ydCI6IjI2OTM3IiwidHlwZSI6Im5vbmUiLCJpZCI6ImIxODlkOGJlLTI3M2ItNDQ4Ny1hM2MxLTdkZGQ4OGZiNzU1OCIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiL3dzIiwiaG9zdCI6InVzYS13YXNoaW5ndG9uLmx2dWZ0LmNvbSIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA3MzAwMjkiLCJhZGQiOiIxNTguMTAxLjE5LjE3MiIsInBvcnQiOiIxMDkxMCIsInR5cGUiOiJodHRwIiwiaWQiOiIyNDE2NDVmNS0zMTkwLTQyOWItYjUxMy01MjY1YTI0MmRmZTEiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggdjJjcm9zcy5jb20gLSDnvo7lm73liqDliKnnpo/lsLzkuprlt57mtJvmnYnnn7ZNVUxUQUNPTeaVsOaNruS4reW/gyAxMiIsImFkZCI6IjIxNi4yNC4yNDguMTIyIiwicG9ydCI6IjEzNjQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjI4YjMwNDhiLWZiNGUtNGJlZS1jOGY2LTZjMzMxMDEyNmMyZSIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA4MiIsImFkZCI6IjE1MC4yMzAuNDEuOSIsInBvcnQiOiIyMzI5MiIsInR5cGUiOiJub25lIiwiaWQiOiI5NTZjNmMyZi1iZjU0LTRiODctZmFmZC00Yjc2N2NhMTI3NTAiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii9pbmRleCIsImhvc3QiOiI4NzMxODcwNi13cy52YS5odXlhLmNvbSIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDEwMSIsImFkZCI6Imllc2VpMWVpLmNvbSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYWJhNTBkZDQtNTQ4NC0zYjA1LWIxNGEtNDY2MWNhZjg2MmQ1IiwiYWlkIjoiNCIsIm5ldCI6IndzIiwicGF0aCI6Ii93cyIsImhvc3QiOiJpZXNlaTFlaS5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm71EWEMgVGVjaG5vbG9neSA1MSIsImFkZCI6IjIwLjEwNi43NC4xNyIsInBvcnQiOiIyMzY5MCIsInR5cGUiOiJub25lIiwiaWQiOiI0OTI4MDg1ZC02MzdlLTRiOWUtZTI2ZC1lMTQ2MjdhNDVjNDYiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLzc4OWsiLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA3MzAwMjkiLCJhZGQiOiIxNTguMTAxLjE5LjE3MiIsInBvcnQiOiIxMDkxMCIsInR5cGUiOiJodHRwIiwiaWQiOiIyNDE2NDVmNS0zMTkwLTQyOWItYjUxMy01MjY1YTI0MmRmZTEiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Ht/Cfh7QgdjJyYXlmcmVlLmV1Lm9yZyAtIOe9l+mprOWwvOS6miAgMyIsImFkZCI6IjEwOS4xNjYuMzkuMjA1IiwicG9ydCI6IjM5MjA1IiwidHlwZSI6Im5vbmUiLCJpZCI6IjU0OGNmZDI3LWUxOGYtNDA2Yi04NGY2LTc0ZGU4NDllMjdiOCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvdGlrdG9rIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA3MzAwMjkiLCJhZGQiOiIxNTguMTAxLjE5LjE3MiIsInBvcnQiOiIxMDkxMCIsInR5cGUiOiJodHRwIiwiaWQiOiIyNDE2NDVmNS0zMTkwLTQyOWItYjUxMy01MjY1YTI0MmRmZTEiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA3MzAwMzIiLCJhZGQiOiJ1czAyLmdvZ29nb28uY3lvdSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiZGI1ZDFhYTMtOTA4Yi00NGQxLWJlMGEtNGU2YThkNGU0Y2RhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9nbyIsImhvc3QiOiJ1czAyLmdvZ29nb28uY3lvdSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm70gIDU1IiwiYWRkIjoiZW1ieS5tZXRhbGluay5jZiIsInBvcnQiOiI4MDk2IiwidHlwZSI6ImF1dG8iLCJpZCI6ImI4ZjliNTE0LTQ4MzUtNDkzYi1lOWEwLWMxMzViYmViNzY0YiIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiJlbWJ5Lm1ldGFsaW5rLmNmIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggX1VTX+e+juWbvV82IiwiYWRkIjoiZW1ieS5tZXRhbGluay5jZiIsInBvcnQiOiI4MDk2IiwidHlwZSI6Im5vbmUiLCJpZCI6ImI4ZjliNTE0LTQ4MzUtNDkzYi1lOWEwLWMxMzViYmViNzY0YiIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiL3lvdXRidWVAYmFpLXBpYW8td2FuZy16aGVfdndzIiwiaG9zdCI6ImVtYnkubWV0YWxpbmsuY2YiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA3MzAwMjkiLCJhZGQiOiIxNTguMTAxLjE5LjE3MiIsInBvcnQiOiIxMDkxMCIsInR5cGUiOiJodHRwIiwiaWQiOiIyNDE2NDVmNS0zMTkwLTQyOWItYjUxMy01MjY1YTI0MmRmZTEiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA4MyIsImFkZCI6Ijk2LjQzLjg2LjI4IiwicG9ydCI6IjI2OTM3IiwidHlwZSI6Im5vbmUiLCJpZCI6ImIxODlkOGJlLTI3M2ItNDQ4Ny1hM2MxLTdkZGQ4OGZiNzU1OCIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiL2hlbGxvIiwiaG9zdCI6IllvdVR1YmUtYXdlaWtlamkiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDExNiIsImFkZCI6ImVtYnkubWV0YWxpbmsuY2YiLCJwb3J0IjoiODA5NiIsInR5cGUiOiJub25lIiwiaWQiOiJiOGY5YjUxNC00ODM1LTQ5M2ItZTlhMC1jMTM1YmJlYjc2NGIiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii95b3V0YnVlQGJhaS1waWFvLXdhbmctemhlX3Z3cyIsImhvc3QiOiJlbWJ5Lm1ldGFsaW5rLmNmIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA3NiIsImFkZCI6Ijk2LjQzLjg2LjI4IiwicG9ydCI6IjI2OTM3IiwidHlwZSI6Im5vbmUiLCJpZCI6ImIxODlkOGJlLTI3M2ItNDQ4Ny1hM2MxLTdkZGQ4OGZiNzU1OCIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiL2hlbGxvIiwiaG9zdCI6IjEwNy4xNzMuMTY2LjE2MCIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA3MzAwMjkiLCJhZGQiOiIxNTguMTAxLjE5LjE3MiIsInBvcnQiOiIxMDkxMCIsInR5cGUiOiJodHRwIiwiaWQiOiIyNDE2NDVmNS0zMTkwLTQyOWItYjUxMy01MjY1YTI0MmRmZTEiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Ht/Cfh7Qg572X6ams5bC85LqaIDAwMSIsImFkZCI6IjEwOS4xNjYuMzkuMjA1IiwicG9ydCI6IjM5MjA1IiwidHlwZSI6Im5vbmUiLCJpZCI6IjU0OGNmZDI3LWUxOGYtNDA2Yi04NGY2LTc0ZGU4NDllMjdiOCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvdGlrdG9rIiwiaG9zdCI6IjEwOS4xNjYuMzkuMjA1IiwidGxzIjoiIn0=
    trojan://05742120-ce23-4cc8-88f5-6d221ce45bf4@fhcarm1.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%20028
    trojan://ce433528-39fa-4711-bc0d-25a5b1579574@us-05.licom.ml:12501?allowInsecure=1&sni=us-05.licom.ml#%F0%9F%87%AC%F0%9F%87%A7%20TG%40moneyflychat%20%20%E4%B8%AD%E8%BD%AC%E8%8A%82%E7%82%B9%F0%9F%87%AC%F0%9F%87%A7GB-%F0%9F%87%AC%F0%9F%87%A7GB_433%20%7C%204.35Mb
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA2OSIsImFkZCI6IjIwOC45OC40OC4yIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJhYmE1MGRkNC01NDg0LTNiMDUtYjE0YS00NjYxY2FmODYyZDUiLCJhaWQiOiI0IiwibmV0Ijoid3MiLCJwYXRoIjoiL3dzIiwiaG9zdCI6Imllc2VpMWVpLmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDEwMiIsImFkZCI6IjIwOC45OC40OC4yIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJhYmE1MGRkNC01NDg0LTNiMDUtYjE0YS00NjYxY2FmODYyZDUiLCJhaWQiOiI0IiwibmV0Ijoid3MiLCJwYXRoIjoiL3dzIiwiaG9zdCI6Imllc2VpMWVpLmNvbSIsInRscyI6InRscyJ9
    trojan://05742120-ce23-4cc8-88f5-6d221ce45bf4@fhcarm1.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%20011
    trojan://05742120-ce23-4cc8-88f5-6d221ce45bf4@fhcarm1.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20US%2016%20%E2%86%92%20TG%40SCINV
    vmess://eyJ2IjoiMiIsInBzIjoi6L+Z5Lqb6IqC54K55Y+q6IO95aSH55So5oiW6ICF6Ziy5q2i5aSx6IGU77yM6Jm954S26LSo6YeP5bm25LiN5piv5b6I5aW977yM5Lmf6K+35L2O6LCD5L2/55SoOikiLCJhZGQiOiJlbWJ5Lm1ldGFsaW5rLmNmIiwicG9ydCI6IjgwOTYiLCJ0eXBlIjoiYXV0byIsImlkIjoiYjhmOWI1MTQtNDgzNS00OTNiLWU5YTAtYzEzNWJiZWI3NjRiIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6ImVtYnkubWV0YWxpbmsuY2YiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggdjJyYXlmcmVlLmV1Lm9yZyAtIOe+juWbvUNsb3VkRmxhcmXlhazlj7hDRE7oioLngrkgNjQiLCJhZGQiOiJlcnFpLmxpdmUiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjdjYWEyNDRmLTM3ZjEtNGIwYy1jYzEyLTBjMmQzOTJkNGY2YSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6ImVycWkubGl2ZSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9KOe7v+WktOWklue9kembhuWboikoUHVibGljKSIsImFkZCI6InVzMDIuZ29nb2dvby5jeW91IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJkYjVkMWFhMy05MDhiLTQ0ZDEtYmUwYS00ZTZhOGQ0ZTRjZGEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2dvIiwiaG9zdCI6InVzMDIuZ29nb2dvby5jeW91IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm71DbG91ZEZsYXJl5YWs5Y+4Q0RO6IqC54K5IDY0IiwiYWRkIjoiZXJxaS5saXZlIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI3Y2FhMjQ0Zi0zN2YxLTRiMGMtY2MxMi0wYzJkMzkyZDRmNmEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiJlcnFpLmxpdmUiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Ht/Cfh7QgZ2l0aHViLmNvbS9mcmVlZnEgLSDnvZfpqazlsLzkupogIDMiLCJhZGQiOiIxMDkuMTY2LjM5LjIwNSIsInBvcnQiOiIzOTIwNSIsInR5cGUiOiJub25lIiwiaWQiOiI1NDhjZmQyNy1lMThmLTQwNmItODRmNi03NGRlODQ5ZTI3YjgiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3Rpa3RvayIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA3MSIsImFkZCI6IjIwOC45OC40OC4yIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJhYmE1MGRkNC01NDg0LTNiMDUtYjE0YS00NjYxY2FmODYyZDUiLCJhaWQiOiI0IiwibmV0Ijoid3MiLCJwYXRoIjoiL3dzIiwiaG9zdCI6Imllc2VpMWVpLmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm71DbG91ZEZsYXJl5YWs5Y+4Q0RO6IqC54K5IDY0IiwiYWRkIjoiZXJxaS5saXZlIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI3Y2FhMjQ0Zi0zN2YxLTRiMGMtY2MxMi0wYzJkMzkyZDRmNmEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiJlcnFpLmxpdmUiLCJ0bHMiOiJ0bHMifQ==
    trojan://2ad895a4-90e1-460d-9291-bbfb3463190e@170.187.182.64:443?allowInsecure=0&sni=www.download.windowsupdate1.com#333
    vmess://eyJ2IjoiMiIsInBzIjoiQFNTUlNVQi1WNTMt5LuY6LS55o6o6I2QOnN1by55dC9zc3JzdWIiLCJhZGQiOiIxMjkuMTU5LjQxLjIzMyIsInBvcnQiOiIzMjU4NiIsInR5cGUiOiJub25lIiwiaWQiOiIzNDFhOTE4Mi1jNDIzLTQ5OWMtYzQ2ZS1kMTc4MzhiMjkwMzciLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    trojan://ce433528-39fa-4711-bc0d-25a5b1579574@us-05.licom.ml:12501?allowInsecure=0#%F0%9F%87%AC%F0%9F%87%A7%20Relay_%F0%9F%87%AC%F0%9F%87%A7GB-%F0%9F%87%BA%F0%9F%87%B8US_38
    trojan://05742120-ce23-4cc8-88f5-6d221ce45bf4@fhcarm1.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20US%2012%20%E2%86%92%20TG%40SCINV
    vmess://eyJ2IjoiMiIsInBzIjoiUG9vbF/wn4e68J+HuFVTXzY5IiwiYWRkIjoiNDUuMzUuODQuMTYyIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJhYmE1MGRkNC01NDg0LTNiMDUtYjE0YS00NjYxY2FmODYyZDUiLCJhaWQiOiI0IiwibmV0Ijoid3MiLCJwYXRoIjoiL3dzIiwiaG9zdCI6InVzYS1kYWxsYXMubHZ1ZnQuY29tIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA5NCIsImFkZCI6IjE1MC4yMzAuNDEuOSIsInBvcnQiOiIyMzI5MiIsInR5cGUiOiJub25lIiwiaWQiOiI5NTZjNmMyZi1iZjU0LTRiODctZmFmZC00Yjc2N2NhMTI3NTAiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii93cyIsImhvc3QiOiJ1c2Etd2FzaGluZ3Rvbi5sdnVmdC5jb20iLCJ0bHMiOiIifQ==
    trojan://dbf9bf9c-2c3f-474a-8031-d4c00666a989@fhcamd2.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20US%2010%20%E2%86%92%20TG%40SCINV
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA3MjYyODgiLCJhZGQiOiIxNTguMTAxLjE5LjE3MiIsInBvcnQiOiIxMDkxMCIsInR5cGUiOiJodHRwIiwiaWQiOiIyNDE2NDVmNS0zMTkwLTQyOWItYjUxMy01MjY1YTI0MmRmZTEiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA2MiIsImFkZCI6IjEyOS4xNTkuNDEuMjMzIiwicG9ydCI6IjMyNTg2IiwidHlwZSI6Im5vbmUiLCJpZCI6IjM0MWE5MTgyLWM0MjMtNDk5Yy1jNDZlLWQxNzgzOGIyOTAzNyIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiL3NzaGtpdC81MjA2MTk0ODYzLzYyYzc3MDJhMGVhOGIvIiwiaG9zdCI6InNnMS12MnJheS5zc2hraXQub3JnIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA5MSIsImFkZCI6IjIxNi4yNC4yNDMuMjMzIiwicG9ydCI6IjI5MzUwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjQ3MWNlMTU2LTM5ODAtNGE0ZS1iOTAxLWEyN2RmMjBlOWQwNyIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiL3dzIiwiaG9zdCI6InVzYS13YXNoaW5ndG9uLmx2dWZ0LmNvbSIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDEwNyIsImFkZCI6InhpZXhpLnRrIiwicG9ydCI6IjIwOTYiLCJ0eXBlIjoibm9uZSIsImlkIjoiMzc1NTFjYTAtOGNjMy00MzJmLWNhMWYtODJhYmExZGIzZWY5IiwiYWlkIjoiNjQiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6InhpZXhpLnRrIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDEwNiIsImFkZCI6IjE1MC4yMzAuNDEuOSIsInBvcnQiOiIyMzI5MiIsInR5cGUiOiJub25lIiwiaWQiOiI5NTZjNmMyZi1iZjU0LTRiODctZmFmZC00Yjc2N2NhMTI3NTAiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii93cyIsImhvc3QiOiJ1c2Etd2FzaGluZ3Rvbi5sdnVmdC5jb20iLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm73okpnlpKfmi7/lt55TaGFya3RlY2jlhazlj7ggODQiLCJhZGQiOiIyMDguOTguNDguMiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYWJhNTBkZDQtNTQ4NC0zYjA1LWIxNGEtNDY2MWNhZjg2MmQ1IiwiYWlkIjoiNCIsIm5ldCI6IndzIiwicGF0aCI6Ii93cyIsImhvc3QiOiJpZXNlaTFlaS5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm71DbG91ZEZsYXJl5YWs5Y+4Q0RO6IqC54K5IDY0IiwiYWRkIjoiZXJxaS5saXZlIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI3Y2FhMjQ0Zi0zN2YxLTRiMGMtY2MxMi0wYzJkMzkyZDRmNmEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiJlcnFpLmxpdmUiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm73np5HnvZfmi4nlpJrlt57luIPpmoboj7LlsJTlvrfluIJMZXZlbCAz6YCa5L+h6IKh5Lu95pyJ6ZmQ5YWs5Y+4IDEwIiwiYWRkIjoiNjMuMjA5LjMzLjUyIiwicG9ydCI6IjQ5MTg1IiwidHlwZSI6ImF1dG8iLCJpZCI6IjgyMWUxNjQ0LWI0ZDQtNGM4Mi1kNWRmLTdiNWVmMDZmNDBlOCIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9KOayueeuoTrnoLTop6PotYTmupDlkJsyLjApIiwiYWRkIjoiNjMuMjA5LjMzLjUyIiwicG9ydCI6IjQ5MTg1IiwidHlwZSI6Im5vbmUiLCJpZCI6IjgyMWUxNjQ0LWI0ZDQtNGM4Mi1kNWRmLTdiNWVmMDZmNDBlOCIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9KOayueeuoTrnoLTop6PotYTmupDlkJsyLjApIiwiYWRkIjoid3d3LmRpZ2l0YWxvY2Vhbi5jb20iLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjNkZjY2MTM3LWE0MjgtNDI5Yy1hODU4LThiMTUwNzIxYjM1NCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIveW91dGJ1ZUBiYWktcGlhby13YW5nLXpoZV92d3MiLCJob3N0IjoidXMyMy41Njc1NjgubWwiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA3NSIsImFkZCI6Ijk2LjQzLjg2LjI4IiwicG9ydCI6IjI2OTM3IiwidHlwZSI6Im5vbmUiLCJpZCI6ImIxODlkOGJlLTI3M2ItNDQ4Ny1hM2MxLTdkZGQ4OGZiNzU1OCIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiL2hlbGxvIiwiaG9zdCI6IllvdVR1YmUtYXdlaWtlamkiLCJ0bHMiOiIifQ==
    trojan://ce433528-39fa-4711-bc0d-25a5b1579574@us-05.licom.ml:12501?allowInsecure=0#%E8%BF%99%E4%BA%9B%E8%8A%82%E7%82%B9%E5%8F%AA%E8%83%BD%E5%A4%87%E7%94%A8%E6%88%96%E8%80%85%E9%98%B2%E6%AD%A2%E5%A4%B1%E8%81%94%EF%BC%8C%E8%99%BD%E7%84%B6%E8%B4%A8%E9%87%8F%E5%B9%B6%E4%B8%8D%E6%98%AF%E5%BE%88%E5%A5%BD%EF%BC%8C%E4%B9%9F%E8%AF%B7%E4%BD%8E%E8%B0%83%E4%BD%BF%E7%94%A8%3A%29

</details>

### 所有节点
合并节点总数: `5322`
[节点链接](https://raw.githubusercontent.com/alanbobs999/TopFreeProxies/master/sub/sub_merge.txt)

### 节点来源
- [pojiezhiyuanjun/freev2](https://github.com/pojiezhiyuanjun/freev2), 节点数量: `89`
- [chfchf0306/clash](https://github.com/chfchf0306/clash), 节点数量: `448`
- [xiyaowong/freeFQ](https://github.com/xiyaowong/freeFQ), 节点数量: `178`
- [freefq/free](https://github.com/freefq/free), 节点数量: `81`
- [learnhard-cn/free_proxy_ss](https://github.com/learnhard-cn/free_proxy_ss), 节点数量: `43`
- [vpei/Free-Node-Merge](https://github.com/vpei/Free-Node-Merge), 节点数量: `100`
- [colatiger/v2ray-nodes](https://github.com/colatiger/v2ray-nodes), 节点数量: `87`
- [oslook/clash-freenode](https://github.com/oslook/clash-freenode), 节点数量: `42`
- [ssrsub/ssr](https://github.com/ssrsub/ssr), 节点数量: `80`
- [Leon406/SubCrawler](https://github.com/Leon406/SubCrawler), 节点数量: `2731`
- [yu-steven/openit](https://github.com/yu-steven/openit), 节点数量: `94`
- [iwxf/free-v2ray](https://github.com/iwxf/free-v2ray), 节点数量: `39`
- [gooooooooooooogle/Clash-Config](https://github.com/gooooooooooooogle/Clash-Config), 节点数量: `1`
- [Jsnzkpg/Jsnzkpg](https://github.com/Jsnzkpg/Jsnzkpg), 节点数量: `75`
- [ermaozi/get_subscribe](https://github.com/ermaozi/get_subscribe), 节点数量: `49`
- [wrfree/free](https://github.com/wrfree/free), 节点数量: `81`
- [GreenFishStudio/GreenFish](https://github.com/GreenFishStudio/GreenFish), 节点数量: `56`
- [changfengoss](https://github.com/ronghuaxueleng/get_v2), 节点数量: `15`
- [anaer/Sub](https://github.com/anaer/Sub), 节点数量: `284`
- [xrayfree/free-ssr-ss-v2ray-vpn-clash](https://github.com/xrayfree/free-ssr-ss-v2ray-vpn-clash), 节点数量: `4`
- [mhmhone/shadowrocket-free-subscribe](https://github.com/mhmhone/shadowrocket-free-subscribe), 节点数量: `75`
- [aiboboxx/v2rayfree](https://github.com/aiboboxx/v2rayfree), 节点数量: `69`
- [moneyfly1/sublist](https://github.com/moneyfly1/sublist), 节点数量: `435`
- [Pawdroid/Free-servers](https://github.com/Pawdroid/Free-servers), 节点数量: `17`
- [kxswa/k](https://github.com/kxswa/k), 节点数量: `0`
- [Nodefree.org](https://github.com/Fukki-Z/nodefree), 节点数量: `50`

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