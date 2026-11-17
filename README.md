# Sleep · 结单小票生成器（橘子海club / 安眠药）

基于原版小票机的独立定制版本：俱乐部名称 **橘子海club**（ORANGE SEA CLUB），直属盖章署名 **安眠药**（SLEEPING PILL）。单文件 HTML，无需安装。

## 本地打开

直接双击 `index.html` 即可（也可用 `python3 -m http.server` 起个本地服务）。

## 说明

- 店名固定为橘子海club，盖章固定为安眠药，不可修改、不可关闭。
- 每个陪陪单项可填写结单备注，显示在小票对应单项下方，留空不显示。
- 所有输入自动存 `localStorage`（独立存储键 `sleep-v1`），刷新不丢，与其他版本互不干扰。
