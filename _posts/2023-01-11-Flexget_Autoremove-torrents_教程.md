---
layout: post
title: Flexget autoremove-torrents 教程
categories: [PT, Flexget, autoremove-torrents, Qbittorrent]
description: 纯小白 PT 自动刷 free 种删种教程
keywords: PT，Flexget，autoremove-torrents，Qbittorrent，群晖，Debain，Ubuntu，Linux，qb，刷种，自动，免费
topmost: false
---

全自动下载免费种子，自动删种，小白进阶教程3。

<h1 align = "center">Flexget autoremove-torrents 教程</h1>

## 1、安装 Python 和 pip

如已经安装好 python 和 pip 后，并且能正常运行，请跳转至【步骤 2】
<!-- <h1 align = "center">Flexget + Autoremove-torrents + Qbittorrent 教程</h1> -->

### 1.1 [群晖](https://github.com/RipplePiam/MobaXterm-Chinese-Simplified "群晖")

### 1.2 [Linux](https://github.com/RipplePiam/MobaXterm-Chinese-Simplified "群晖") 



## 2、安装 BT 软件

如已经安装好 BT 软件，请跳至【步骤 3】

### 1.1 [Qbittorrent](https://github.com/RipplePiam/MobaXterm-Chinese-Simplified "群晖")

### 1.2 [Trasmission](https://github.com/RipplePiam/MobaXterm-Chinese-Simplified "群晖") 

### 1.3 更多
<details><summary style="color: #00FFFF">toremove-torrents 支持客户端</summary>

[官网（中文）](https://autoremove-torrents.readthedocs.io/zh_CN/latest/) 

版本 Version 1.5.4 日期 2022.07.19
<div class="section" id="supported-clients"> <h2>支持的客户端<a class="headerlink" href="#supported-clients" title="永久链接至标题"></a></h2> <p>截至目前，程序支持 qBittorrent/Transmission/μTorrent/Deluge。rTorrent 正在计划之中。</p> <div class="wy-table-responsive"><table border="1" class="docutils"> <colgroup> <col width="50%"> <col width="50%"> </colgroup> <thead valign="bottom"> <tr class="row-odd"><th class="head">客户端</th> <th class="head">支持情况</th> </tr> </thead> <tbody valign="top"> <tr class="row-even"><td>qBittorrent</td> <td>是</td> </tr> <tr class="row-odd"><td>Transmission</td> <td>是</td> </tr> <tr class="row-even"><td>μTorrent</td> <td>是</td> </tr> <tr class="row-odd"><td>Deluge</td> <td>是</td> </tr> <tr class="row-even"><td>rTorrent</td> <td>计划中</td> </tr> </tbody> </table></div> </div>

<div class="section" id="supported-properties"> <h2>支持的属性<a class="headerlink" href="#supported-properties" title="永久链接至标题"></a></h2> <p>✓ = 支持 ✗ = 不支持</p> <div class="wy-table-responsive"><table border="1" class="docutils"> <colgroup> <col width="20%"> <col width="20%"> <col width="20%"> <col width="20%"> <col width="20%"> </colgroup> <thead valign="bottom"> <tr class="row-odd"><th class="head">属性/客户端</th> <th class="head">Deluge</th> <th class="head">qBittorrent</th> <th class="head">Transmission</th> <th class="head">μTorrent</th> </tr> </thead> <tbody valign="top"> <tr class="row-even"><td>平均下载速度</td> <td>✓ <sup>2.0 或更高版本</sup></td> <td>✓</td> <td>✓</td> <td>✗</td> </tr> <tr class="row-odd"><td>平均上传速度</td> <td>✓</td> <td>✓</td> <td>✓</td> <td>✗</td> </tr> <tr class="row-even"><td>类别</td> <td>✓ <sup>需要 Label 插件</sup></td> <td>✓</td> <td>✓ <sup>3.00+ 或更高版本</sup></td> <td>✓</td> </tr> <tr class="row-odd"><td>已连接的下载者</td> <td>✓</td> <td>✓</td> <td>✓</td> <td>✓</td> </tr> <tr class="row-even"><td>已连接的做种者</td> <td>✓</td> <td>✓</td> <td>✓</td> <td>✓</td> </tr> <tr class="row-odd"><td>创建时间</td> <td>✓</td> <td>✓</td> <td>✓</td> <td>✗</td> </tr> <tr class="row-even"><td>下载速度</td> <td>✓</td> <td>✓</td> <td>✓</td> <td>✓</td> </tr> <tr class="row-odd"><td>下载量</td> <td>✓</td> <td>✓</td> <td>✓</td> <td>✓</td> </tr> <tr class="row-even"><td>空闲空间</td> <td>✓</td> <td>✓</td> <td>✓</td> <td>✗</td> </tr> <tr class="row-odd"><td>最近活动</td> <td>✓ <sup>2.0 或更高版本</sup></td> <td>✓ <sup>v3.0 或更高版本</sup></td> <td>✓</td> <td>✗</td> </tr> <tr class="row-even"><td>下载者</td> <td>✓</td> <td>✓</td> <td>✓</td> <td>✓</td> </tr> <tr class="row-odd"><td>进度（百分比）</td> <td>✓</td> <td>✓</td> <td>✓</td> <td>✓</td> </tr> <tr class="row-even"><td>分享率</td> <td>✓</td> <td>✓</td> <td>✓</td> <td>✓</td> </tr> <tr class="row-odd"><td>做种者</td> <td>✓</td> <td>✓</td> <td>✓</td> <td>✓</td> </tr> <tr class="row-even"><td>做种时间</td> <td>✓</td> <td>✓</td> <td>✓</td> <td>✓</td> </tr> <tr class="row-odd"><td>种子大小</td> <td>✓</td> <td>✓</td> <td>✓</td> <td>✓</td> </tr> <tr class="row-even"><td>空闲状态（Stall）</td> <td>✗</td> <td>✓</td> <td>✓</td> <td>✗</td> </tr> <tr class="row-odd"><td>状态</td> <td>✓</td> <td>✓</td> <td>✓</td> <td>✓</td> </tr> <tr class="row-even"><td>Tracker</td> <td>✓</td> <td>✓</td> <td>✓</td> <td>✓</td> </tr> <tr class="row-odd"><td>上传比率</td> <td>✓</td> <td>✓</td> <td>✓</td> <td>✓</td> </tr> <tr class="row-even"><td>上传速度</td> <td>✓</td> <td>✓</td> <td>✓</td> <td>✓</td> </tr> <tr class="row-odd"><td>上传量</td> <td>✓</td> <td>✓</td> <td>✓</td> <td>✓</td> </tr> </tbody> </table></div> </div>
</details>

<p></p>

<details><summary style="color: #00FFFF">Flexget 支持客户端</summary>

版本 Version 1.5.4
日期 2022.07.19
<table><thead><tr><th><strong>Keyword</strong></th> <th><strong>Description</strong></th></tr></thead> <tbody><tr><td><a href="/Plugins/aria2" class="is-internal-link is-valid-page">aria2</a></td> <td>Pass URIs to be downloaded to the aria2 downloader.</td></tr> <tr><td><a href="/Plugins/deluge" class="is-internal-link is-valid-page">deluge</a></td> <td>Pass torrents directly to deluge bittorrent client, supporting magnet links.</td></tr> <tr><td><a href="/Plugins/nzbget" class="is-internal-link is-valid-page">nzbget</a></td> <td>Download nzbs with nzbget.</td></tr> <tr><td><a href="/Plugins/periscope" class="is-internal-link is-valid-page">periscope</a></td> <td>Download subtitles with Periscope.</td></tr> <tr><td><a href="/Plugins/pyload" class="is-internal-link is-valid-page">pyload</a></td> <td><a href="http://pyload.net/" class="is-external-link">http://pyload.net/</a>.</td></tr> <tr><td><a href="/Plugins/qbittorrent" class="is-internal-link is-valid-page">qbittorrent</a></td> <td>Pass torrents directly to the qBittorrent client, supporting magnet links.</td></tr> <tr><td><a href="/Plugins/rtorrent" class="is-internal-link is-valid-page">rtorrent</a></td> <td>Pass torrents directly to rtorrent</td></tr> <tr><td><a href="/Plugins/rtorrent_magnet" class="is-internal-link is-valid-page">rtorrent_magnet</a></td> <td>Handles magnet URI's and produces rTorrent compatible torrent files (0.8.9+)</td></tr> <tr><td><a href="/Plugins/sabnzbd" class="is-internal-link is-valid-page">sabnzbd</a></td> <td>Download nzbs with SABnzbd.</td></tr> <tr><td><a href="/Plugins/subliminal" class="is-internal-link is-valid-page">subliminal</a></td> <td>Download subtitles with Subliminal.</td></tr> <tr><td><a href="/Plugins/transmission" class="is-internal-link is-valid-page">transmission</a></td> <td>Pass torrents directly to transmission, supporting magnet links.</td></tr> <tr><td><a href="/Plugins/utorrent" class="is-internal-link is-valid-page">utorrent</a></td> <td>Pass torrents directly to uTorrent.</td></tr></tbody></table>

[官网(英文)](https://flexget.com/en/Plugins)
</details>


## 3、安装 Flexget

[SSH工具](https://github.com/RipplePiam/MobaXterm-Chinese-Simplified "中文版")
安装
```
pip install flexget
```
### 3.1 config.yml 配置<font color=Red>（重要）</font>

<details><summary style="color: #980000">简易模板</summary>

简易模板
```
templates:    
  standard:
    free_space:
      path: /volume2/Nas1x_16T/        # 目录 等价于 /volume2
      space: 10240                    # 单位(MB) 当空间  小于 10gb 不下载
  qb:
    qbittorrent:
      path: /volume2/Nas1x_16T/PT/PT-torrents-ed/      # qb文件下载路径
      # 也可用 127.0.0.1    192.168.1.197
      host: localhost         # qb-web网址
      port: 55555             # qb-web端口（默认 8080 ）
      username: admin         # 用户名
      password: adminadmin    # 密码
tasks:
  u2: # 任务名
    rss: 
      url:  https://hdhome.org/torrentrss.php?xxx  # 订阅链接
      other_fields:
        - link
    template: qb # 调用上边的 qb 模板
    qbittorrent: # 对这个任务加载到 qb 的种子，自动添加 u2 的标签
      label: u2
      maxupspeed: 10000     #  单种最大上传速度 500MB/s
    download: /volume2/torrents/HDhome/  #  种子文件保存路径 （非下载数据）
    content_size: # （可选）针对每个种子体积过滤 ()单位：MiB 
      # 文件在 20~40g 方可下载
      min: 20480
      max: 40960
      strict: no  # 严格执行 yes 默认no就好了
```
</details>

（简易配置 成功 <font color=Red>测试 (3.2) | 运行 (3.3) </font> 后，再尝试使用 订阅「免费」种子模板！）
<details><summary style="color: #00FFFF">订阅免费种子模板</summary>

需下载 nexusphp （flxget 插件）
```
templates:    
  standard:
    free_space:
      path: /volume2/Nas1x_16T/     # 目录 等价于 /volume2
      space: 10240                  # 单位(MB) 当空间  小于 10gb 不下载
  qb:
    qbittorrent:
      path: /volume2/Nas1x_16T/PT/PT-torrents-ed/      # qb文件下载路径
      # 也可用 127.0.0.1    192.168.1.197
      host: localhost         # qb-web网址
      port: 55555             # qb-web端口（默认 8080 ）
      username: admin         # 用户名
      password: adminadmin    # 密码
tasks:
  u2: # 任务名
    rss: 
      url:  https://hdhome.org/torrentrss.php?xxx
      other_fields:
        - link
    template: qb 
    qbittorrent:
      label: u2
      maxupspeed: 10240
    nexusphp:
      cookie: 'c_secure_uid=xxx; xxx'   # 浏览器获取
      discount:   # 优惠信息（选填）
        - free
        - 2xfree
      seeders:    # 做种情况（选填） 做种人数，大于4个则不下载
        min: 0
        max: 4
      leechers:   # 下载情况（选填） 下载人数，超过5个则不下载
        min: 5
        max: 99999
        max_complete: 0.8
      left-time: 10 hours  # 优惠剩余时间（选填）
      hr: no    # 是否下载HR （选填）
      remember: yes  # 记住优惠信息 （选填） yes：后续种子开启 free 也不会下载
    download: /volume2/torrents/HDhome/ 
    content_size:
      min: 20480
      max: 40960
      strict: no  
#web_server:                  # 删除 # 开启WEBUI
  #port: 6566                 # flexget-web端口，默认值6566，请勿随意修改
  #web_ui: yes                
```
</details>

<details><summary style="color: #00FFFF">Linux (群晖) 查看剩余空间大小</summary> 

df -h
```
root@:~# df -h
文件系统                           大小  已用  可用 使用率%  挂载路径
Filesystem                        Size  Used Avail Use% Mounted on
/dev/nvme0n1                      469G  128G  318G  29% /volume3
/dev/sdb                          14.5T 9.8T  4.7T  67% /volume2
```
</details>


### 3.2 测试
### 3.3 运行
### 3.4 定时运行
### 3.5 查看日志 排查错误
### 3.6 进阶教程
[Flexget 进阶配置](https://www.v2ex.com/t/901223 "Flexget")

## 4、安装 autoremove-torrents
### 4.1 安装
```
pip install autoremove-torrents
```
如错误 ，请在 Python 和 pip 的安装教程 寻找原因

获取 autoremove-torrents 的路径
```
which autoremove-torrents
或
find -name / -name autoremove-torrents
```
上面命令是在 根目录 / 下查找名外 autoremove-torrents 的路径

<details><summary style="color: #00FFFF">关于 find 命令</summary> 

例如我安装在 /volume1/ 就可以指定在这搜索，加快速度
-name 是文件名字
```
find  /volume1/ -name autoremove-torrents
```
</details>

建立软连接 /bin/autoremove-torrents

请自行替换 『绝对路径』
```
ln -s 绝对路径 /bin/autoremove-torrents
# ln -s 原始路径 新路径
```
例子：
```
ln -s /volume3/python/3.8.16/bin/autoremove-torrents /bin/autoremove-torrents
```
<details><summary style="color: #00FFFF">删除软连接</summary>

```
rm -f /bin/autoremove-torrents
```
说明
```
rm 删除文件
-f                    # 是参数 表示强制
-r                    # 删除文件夹
rm -rf /volume1       # 强制删除目录 /volume1 
rm -rf /*             # 程序员要跑路了
```
</details>

成功
```
root@:~# autoremove-torrents -v
Fri, XX Jan 202X XX:00:00 autoremovetorrents.main INFO: Auto Remove Torrents 1.5.4
```
<details><summary style="color: #00FFFF">不成功</summary>

```
root@:~#  autoremove-torrents -v
autoremove-torrents: command not found
```
说明 软连接 建立失败

排查错误：
找到绝对路径 
```
/volume3/python/3.8.16/bin/autoremove-torrents -v
Sun, XX Jan 2023 XX:00:00 autoremovetorrents.main INFO: Auto Remove Torrents 1.5.4
Sun, XX Jan 2023 XX:00:00 autoremovetorrents.main INFO: Loading configurations...

```

</details>


### 4.1 配置 config.yaml （重要）

<details><summary style="color: #00FFFF">YML语法注意事项</summary>

空两格, 不使用 Tab 键（YML/YAML 语法格式报错，大多是使用 Tab 键造成，复制）

注释符号“#”    # 号后面当行的内容，不影响配置文件
```
u2:
  client: qbittorrent
```

</details>

简易配置
```
u2:   # 第一部分：任务名称 自行修改 u2
  client: qbittorrent                   # 指定客户端 qbittorrent
  host: http://127.0.0.1:8080           # 8080 端口 实际看qbittorrent配置
  # host: http://192.168.1.10:55555     # 也可以这样填写 55555端口
  username: <qb用户名>                  # 用户名、密码 不用加 <>
  password: <qb密码>
  strategies:                           # 第二部分 策略块（删除条件）
    u2-mteam: # Part2：                 # 策略名称 u2-mteam
      categories:                       # 1：过滤器   在这些标签 中选择种子。
        - u2                            # 移除种子种类 u2 meteam
        - meteam
      free_space:
        min: 200                       # 当 /volume1/PT/ 空间小于 200GiB 时执行。
        path: /volume1/PT/   # 目录
        action: remove-old-seeds           #	尝试删除添加时间最久种子
        #action: remove-inactive-seeds     # 尝试删除不活跃的种子
  delete_data: true              # 第四部分： 删除下载数据（可选项） 默认值为 false
```
### 4.2 测试
<details><summary style="color: #00FFFF">提示</summary>

--view    测试，实际上不会执行

--log     日志文件夹路径（选填）

--conf    配置文件 config.yml 路径（选填）
</details>

```
autoremove-torrents --view --conf=/volume3/Nvme1/flexget/autoremove-torrents/config.yml --log=/volume1/autoremove-torrents/logs/
```

[进阶配置](https://www.v2ex.com/t/901223 "进阶配置") <font color=Red>（简易配置成功运行后再点击查看！）</font>

### 4.3 运行

### 4.4 定时启用

<details><summary style="color: #00FFFF">crontab 用法</summary>

</details>

nano /etc/crontab

```
# # 号为注释符，注释该行后的语句
# * * * * * 每分钟执行一次命令
# 成功后再设置成 */30 * * * *  三十分钟一次

* * * * * /bin/autoremove-torrents --conf=/volume3/Nvme1/flexget/ --log=/volume1/autoremove-torrents/logs/ autoremove-torrents/config.yml

```
### 4.5 查看日志 logs

### 4.6 进阶配置 
[进阶配置](https://www.v2ex.com/t/901223 "进阶配置") <font color=Red>（简易配置成功运行后再点击查看！）</font>


# 一级导航
### 二级导航
#### 三级导航
##### 四级导航

隐藏
<details><summary style="color: #00FFFF">谷歌、360、114 DNS 被劫持</summary>
</details>

 - 这是列表
Markdown是一种可以使用普通文本编辑器编写的标记语言，<br>通过简单的标记语法，它可以使普通文本内容具有一定的格式。

  * 这也是列表
    * 这个缩进可以使用tab键
      - 再缩进一下

  + 这还是一种列表

  1 .这是有序列表

  2 .有序列表

字体

斜体 *这是斜体内容*

加粗 **这是加粗内容**

加粗又斜体 ***这是内容***

> 一级引用

>> 二级引用

>>> 三级引用

等等n级引用

删除线
~~删除线内容~~

分割线
*** 

图片
<img src="https://i.imgur.com/CcsgKZM.png" alt="多拨图"/>
or
![图片下方文字]('https://i.imgur.com/CcsgKZM.png' '图片title')

解释：图片title 是图片的标题，当鼠标移到图片上时显示的内容。title可加可不加


[链接名](https://www.v2ex.com/t/901223 "悬停title")
解释：title可加可不加

- 列表内容
+ 列表内容
* 列表内容

注意：- + * 跟内容之间都要有一个空格

表格
表头|表头|表头
---|:--:|---:
内容|内容|内容
内容|内容|内容

代码

单行代码：
`python flexget`

多行 

```
python flexget
sudo
```
