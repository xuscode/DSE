# HOME

个人收藏学习

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