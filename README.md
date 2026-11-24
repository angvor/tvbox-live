# TVBox 直播源

TVBox / OK影视 直播配置文件，频道数据来自 iptv-org 公开源。

## 使用方法

### 方法一：直播配置（推荐，OK影视 / TVBox 都可用）

在 OK影视 或 TVBox 里找到**直播配置**（有的版本叫“直播源”），填入 M3U 地址：

```
https://raw.githubusercontent.com/angvor/tvbox-live/main/tv.m3u
```

### 方法二：完整配置（TVBox）

在 TVBox 的配置地址里填入 JSON 地址：

```
https://raw.githubusercontent.com/angvor/tvbox-live/main/tv.json
```

## 内容

- `tv.m3u`：直播频道 M3U 播放列表（155+ 个频道）
- `tv.json`：直播频道配置（JSON 格式，TVBox 可直接加载）
- 频道分组：综合、新闻、体育、电影、娱乐、少儿、音乐、纪录片、教育、财经、文化、生活、宗教、经典、其他

## 说明

- 频道源为公开 IPTV 流，部分源可能失效或受地域限制，个别台打不开是正常的。
- OK影视 本身是看电影电视剧的点播应用，直播要走上面的直播配置入口；只填点播配置是看不到直播的。
- 配置文件会不定期更新。
