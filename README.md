# Qt_Player

使用QT + C++搭建的一个基础的本地视频播放器, 基于qmake构建, Qt Creator实现

---

# 窗体设计

- 主体以QWidget作为承载，另起一个QWidget提升为QVideoWidget作为播放器的载具
- 设计QMedioPlayer部件作为视频播放器，同时设计七个基础QPushButton键位用于实现基础的按键
- 设计一个QTextEdit部件作为快捷键提示文本，并用一个QCheckBox控件进行控制收放
- 设计一个QSlider作为视频播放进度条
- 设计好几个QLabel作为提示性文本的载具，如播放剩余事件和音量

所有部件和对应快捷施法如图：
![a9a7431f37b846471a03b370098796c8](https://github.com/LeeJc02/Qt_Player/assets/129182487/df37692c-b6f2-47ee-bf4e-fe717bc16ae6)

