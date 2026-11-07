# FlexiSLM × UniVLA 本地展示页

直接打开 `index.html`，或在本目录执行：

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

访问 http://127.0.0.1:8765 。纯静态页面，无 npm 依赖，无外部字体、分析脚本或后端服务。

## 素材与证据

两个 GIF 和初末帧复制自 `../成功案例/`，原素材未改动。案例来自 2026-11-03 expanded300 早期闭环测试，task0 和 task3，init0 / seed42，不是 v2 新录制的轨迹。GIF 是每动作块一帧的稀疏回放，非实时视频。没有对应原始音频，因此不放置虚假的音频播放控件。

下载 JSON 保留原 report 的结果和设置，将 checkpoint 服务器绝对路径改为便于展示的相对名称。未复制日志、认证信息或 trace。v2 背景数字来自本对话 2026-11-07 核查的 scores_first_attempt/summary.json，均为首次尝试 / 计划次数口径。

交互：任务切换（含方向键）、停止并显示初帧、重新播放、查看末帧、下载记录。减少动态效果偏好下默认显示静态初帧。

参考 https://amphionteam.github.io/DuplexAgent-RSI-Demo/ 的米白底、深紫色衬线标题、编号章节风格，未复制其品牌、文案或素材。本页为本地研究展示，不代表官方 FlexiSLM 项目网站。
