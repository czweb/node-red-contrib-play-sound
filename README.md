# node-red-contrib-play-sound

1、node-red-contrib-play-sound这个插件依赖系统播放器，需要先装，
2、经测试mplayer播放器延迟有1秒吧
3、sox播放器速度还可以，基本上感觉不到延迟
4、所以在使用node-red这个插件前安装sudo apt-get install sox libsox-fmt-all -y

## Install
Run the following npm command in your Node-RED environment.
```
npm install node-red-contrib-play-sound
```

## Usage
This package add 1 output node (PlaySound) to Node-RED.

The PlaySound node expect the following payload :
* `start` (or empty): Start playing
* `stop`: Stop all sound playing
* `pause`: Pause all sound playing
* `resume`: Resume all sound playing


The PlaySound node comprises the following options:

* **audioURI**: File name or url to play - If empty, then the one in dialog is used
* **options**: Options - If empty, then the one in dialog is used


## License
The MIT License (MIT)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
