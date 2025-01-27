# mml2Gcode
Converts MML to Gcode. 转换MML乐谱到Gcode

MML(Music Macro Language)是一些在线游戏（如洛奇）的乐谱代码



## 用法
```
usage: mml2beep.py [-h] [-t TRACK] [-f {json,cpp}] mml_file beep_file

转换MML乐谱到Gcode

positional arguments:
  mml_file              输入的MML文件，格式为txt
  beep_file             输出的Gcode文件路径

optional arguments:
  -h, --help            show this help message and exit
  -t TRACK, --track TRACK
                        输出第几个音轨，默认为1
  -f {json,cpp}, --format {json,cpp}
                        输出格式，默认为json
```

## 链接
* [MML语法参考](https://mabinogi.fws.tw/ac_com_annzyral.php)
* [获取MML乐谱](https://mabinogi.fws.tw/ac_comproser.php)
