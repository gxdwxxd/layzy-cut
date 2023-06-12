# LAZY-CUT

基于 Cursor（GPT-3.5）辅助生成的简单抖音视频生成工具。

## 命令参数
`./cut.sh -i "in.mp4" -o "out.mp4" -t "字幕" -c 10:20 -a "公路之歌.mp3"`

-i: 输入视频路径，必填
-o：输出视频路径，必填
-t：置顶字幕，可选
-c：截取时间段，10:20表示截取 10 秒到 20 秒的视频内容；直接输入 10 表示截取前十秒的内容。可选
-a：音频路径，可选

[](./2023-06-11%2023.03.31.gif)

## 生成效果
[](./demo.jpg)