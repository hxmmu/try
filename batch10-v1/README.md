# 十套 BNF 转换交付 v1

## 已完成：宝宝巴士点读馆（五个原始分册）

这套原包含五个 BNF，均无游戏。本次保留普通点读和全部原始录音，不新增游戏。原始 MPEG 音频帧全部保持不变。

| 分册 | BNL 下载 | 大小 | 普通点读位置 |
| --- | --- | --- | --- |
| 1 | [直接下载](https://raw.githubusercontent.com/hxmmu/try/bnf-batch10-20261103/batch10-v1/babybus_library_1_v1.bnl) | 46.3 MB | 71 |
| 2 | [直接下载](https://raw.githubusercontent.com/hxmmu/try/bnf-batch10-20261103/batch10-v1/babybus_library_2_v1.bnl) | 52.8 MB | 78 |
| 3 | [直接下载](https://raw.githubusercontent.com/hxmmu/try/bnf-batch10-20261103/batch10-v1/babybus_library_3_v1.bnl) | 76.7 MB | 76 |
| 4 | [直接下载](https://raw.githubusercontent.com/hxmmu/try/bnf-batch10-20261103/batch10-v1/babybus_library_4_v1.bnl) | 63.2 MB | 43 |
| 5 | [直接下载](https://raw.githubusercontent.com/hxmmu/try/bnf-batch10-20261103/batch10-v1/babybus_library_5_v1.bnl) | 44.3 MB | 42 |

Mac 下载后将五个 `.bnl` 文件放入点读笔 `BOOK` 文件夹，安全弹出并重启。保留原始 BNF 备份。无需把网页文件复制到点读笔。

程序验证：全部 310 个正常点读位置、387 个音频索引通过原始固件离线模拟；387 段音频严格解码通过，原始 MPEG 帧保持一致。另有两个原始未定义记录，其原始字段保存在分析文件中，目标中不播放声音。

音频确认：此套没有游戏，无需新增或确认游戏提示音；录音按原包复制。

实机测试：尚未测试；离线通过不代表实机通过。

其余原包正在独立解析游戏和题库。未完成的书不会作为定稿上传。
