# Qt_Player

使用QT + C++搭建的一个基础的本地视频播放器, 基于qmake构建, Qt Creator实现
![image](https://github.com/LeeJc02/Qt_Player/assets/129182487/c9b9e036-0ec7-41e1-a179-f03d33bad91a)

---

# 窗体设计

- 主体以QWidget作为承载，另起一个QWidget提升为QVideoWidget作为播放器的载具
- 设计QMedioPlayer部件作为视频播放器，同时设计七个基础QPushButton键位用于实现基础的按键
- 设计一个QTextEdit部件作为快捷键提示文本，并用一个QCheckBox控件进行控制收放
- 设计一个QSlider作为视频播放进度条
- 设计好几个QLabel作为提示性文本的载具，如播放剩余事件和音量
- 同时提供一个QLineEdit用于输入URL路径和一个用于确认的QPushButton按键

# 快捷键绑定

所有部件和对应快捷施法如图：
![a9a7431f37b846471a03b370098796c8](https://github.com/LeeJc02/Qt_Player/assets/129182487/df37692c-b6f2-47ee-bf4e-fe717bc16ae6)

除上图所示外另新添功能：
![image](https://github.com/LeeJc02/Qt_Player/assets/129182487/241a7923-6486-4526-ae6f-f01291e7d711)
