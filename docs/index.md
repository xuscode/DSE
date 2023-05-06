# HOME

欢迎来到题库的世界

人生苦短。我有一个问题库!

以后大家可以将题库复制到txt，我们将对题库进行总结并上传到本网站;

## 本地使用

安装python，然后运行下面代码安装主题

```bash

pip install mkdocs
pip install mkdocs-material
pip install mkdocs-material-extensions
pip install mkdocs-video

```
然后启动start.bat 即可


```bash

REM cd /d C:Program Files (x86)Mozilla Firefox
REM start firefox.exe http://127.0.0.1:8000/

REM cd /d "C:\Program Files\Google\Chrome\Application"
REM start chrome.exe http://127.0.0.1:8000/

cd /d C:\Program Files (x86)\Microsoft\Edge\Application
start msedge.exe http://127.0.0.1:8000/

cd /d %~dp0\
mkdocs build
mkdocs serve

pause


```