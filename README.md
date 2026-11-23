# Ditto（跟读）· 免费课程

给 [Ditto（跟读）](https://github.com/limkown-stack/ditto-mac) App 用的现成课程：从美国之音 **VOA Learning English** 的节目里挑选，
逐词转写、切成一句一句、按语速和生词量定好难度。App 里「课程 → 免费」直接下载，不需要 Mac。

- `library.json`：课程目录（节目、标题、难度、时长、分几节）
- Release `v1`：每节课的 `lesson.json`（逐词时间的字幕）和 `audio.m4a`（音频），文件名是「课程id__文件名」

## 来源和授权

所有音频和文字来自 Voice of America（[learningenglish.voanews.com](https://learningenglish.voanews.com)）。
按 VOA 的使用条款，VOA 自己制作的文字、音频、视频属于公有领域（public domain），使用时注明来源 VOA。
这里只收 VOA 自己制作的音频和转写，不收节目配图（常是美联社等第三方的照片，不属于公有领域）。

转写由本机的 Whisper 模型自动生成，可能有少量错误。
