# MediaStreamSource 暂停 Bug
位于 Windows.Media.Core

## 描述
当非MP3的音频流被呈现时，在某次暂停后音频流不会继续播放，直到再执行一次播放和暂停操作才恢复正常。

## 临时解决方案
尝试再次播放暂停。

## 平台
在 Windows 8.0, 8.1, Windows Phone 8.1以及更高版本中被确认

状态：未修复
