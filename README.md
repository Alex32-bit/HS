# HS
HISTORIA SOCIAL SOBRE INSTALL KIVYENV
Pass a name to activate one of the following virtualenvs:
==============================================================================
No se encuentra el archivo

C:\Users\Acer Black>mkvirtualenv kivyenv
 C:\Users\Acer Black\Envs is not a directory, creating
created virtual environment CPython3.7.9.final.0-64 in 112523ms
  creator CPython3Windows(dest=C:\Users\Acer Black\Envs\kivyenv, clear=False, gl
obal=False)
  seeder FromAppData(download=False, pip=bundle, setuptools=bundle, wheel=bundle
, via=copy, app_data_dir=C:\Users\Acer Black\AppData\Local\pypa\virtualenv)
    added seed packages: pip==20.2.2, setuptools==49.6.0, wheel==0.35.1
  activators BashActivator,BatchActivator,FishActivator,PowerShellActivator,Pyth
onActivator,XonshActivator

(kivyenv) C:\Users\Acer Black>
(kivyenv) C:\Users\Acer Black>deactivate

C:\Users\Acer Black>workon

Pass a name to activate one of the following virtualenvs:
==============================================================================
kivyenv

C:\Users\Acer Black>workon kivyenv
(kivyenv) C:\Users\Acer Black>pip list
Package    Version
---------- -------
pip        20.2.2
setuptools 49.6.0
wheel      0.35.1
WARNING: You are using pip version 20.2.2; however, version 20.2.3 is available.

You should consider upgrading via the 'C:\Users\Acer Black\Envs\kivyenv\Scripts\
python.exe -m pip install --upgrade pip' command.

(kivyenv) C:\Users\Acer Black>pip install docutils pygments pypiwin32 kivy_deps.
sdl2==0.1.* kivy_deps.glew==0.1.*
Collecting docutils
  Downloading docutils-0.16-py2.py3-none-any.whl (548 kB)
     |¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦| 548 kB 409 kB/s
Collecting pygments
  Downloading Pygments-2.7.1-py3-none-any.whl (944 kB)
     |¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦| 944 kB 504 kB/s
Collecting pypiwin32
  Downloading pypiwin32-223-py3-none-any.whl (1.7 kB)
Collecting kivy_deps.sdl2==0.1.*
  Downloading kivy_deps.sdl2-0.1.23-cp37-cp37m-win_amd64.whl (2.5 MB)
     |¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦| 2.5 MB 1.3 MB/s
Collecting kivy_deps.glew==0.1.*
  Downloading kivy_deps.glew-0.1.12-cp37-cp37m-win_amd64.whl (115 kB)
     |¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦| 115 kB 731 kB/s
Collecting pywin32>=223
  Downloading pywin32-228-cp37-cp37m-win_amd64.whl (9.1 MB)
     |¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦| 9.1 MB 1.3 MB/s
Installing collected packages: docutils, pygments, pywin32, pypiwin32, kivy-deps
.sdl2, kivy-deps.glew
Successfully installed docutils-0.16 kivy-deps.glew-0.1.12 kivy-deps.sdl2-0.1.23
 pygments-2.7.1 pypiwin32-223 pywin32-228
WARNING: You are using pip version 20.2.2; however, version 20.2.3 is available.

You should consider upgrading via the 'C:\Users\Acer Black\Envs\kivyenv\Scripts\
python.exe -m pip install --upgrade pip' command.

(kivyenv) C:\Users\Acer Black>pip install kivy_deps.gstreamer==0.1.*
Collecting kivy_deps.gstreamer==0.1.*
  Downloading kivy_deps.gstreamer-0.1.18-cp37-cp37m-win_amd64.whl (77.2 MB)
     |¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦| 77.2 MB 1.9 kB/s
Installing collected packages: kivy-deps.gstreamer
Successfully installed kivy-deps.gstreamer-0.1.18
WARNING: You are using pip version 20.2.2; however, version 20.2.3 is available.

You should consider upgrading via the 'C:\Users\Acer Black\Envs\kivyenv\Scripts\
python.exe -m pip install --upgrade pip' command.

(kivyenv) C:\Users\Acer Black>pip install kivy_deps.angle==0.1.*
Collecting kivy_deps.angle==0.1.*
  Downloading kivy_deps.angle-0.1.10-cp37-cp37m-win_amd64.whl (4.1 MB)
     |¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦| 4.1 MB 939 kB/s
Installing collected packages: kivy-deps.angle
Successfully installed kivy-deps.angle-0.1.10
WARNING: You are using pip version 20.2.2; however, version 20.2.3 is available.

You should consider upgrading via the 'C:\Users\Acer Black\Envs\kivyenv\Scripts\
python.exe -m pip install --upgrade pip' command.

(kivyenv) C:\Users\Acer Black>pip install kivy==1.11.1
Collecting kivy==1.11.1
  Downloading Kivy-1.11.1-cp37-cp37m-win_amd64.whl (4.1 MB)
     |¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦| 4.1 MB 1.1 MB/s
Requirement already satisfied: pygments in c:\users\acer black\envs\kivyenv\lib\
site-packages (from kivy==1.11.1) (2.7.1)
Requirement already satisfied: docutils in c:\users\acer black\envs\kivyenv\lib\
site-packages (from kivy==1.11.1) (0.16)
Collecting Kivy-Garden>=0.1.4
  Downloading kivy-garden-0.1.4.tar.gz (6.8 kB)
Collecting requests
  Downloading requests-2.24.0-py2.py3-none-any.whl (61 kB)
     |¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦| 61 kB 55 kB/s
Collecting certifi>=2017.4.17
  Downloading certifi-2020.6.20-py2.py3-none-any.whl (156 kB)
     |¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦| 156 kB 1.3 MB/s
Collecting chardet<4,>=3.0.2
  Downloading chardet-3.0.4-py2.py3-none-any.whl (133 kB)
     |¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦| 133 kB 1.3 MB/s
Collecting idna<3,>=2.5
  Downloading idna-2.10-py2.py3-none-any.whl (58 kB)
     |¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦| 58 kB 530 kB/s
Collecting urllib3!=1.25.0,!=1.25.1,<1.26,>=1.21.1
  Downloading urllib3-1.25.10-py2.py3-none-any.whl (127 kB)
     |¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦¦| 127 kB 1.3 MB/s
Building wheels for collected packages: Kivy-Garden
  Building wheel for Kivy-Garden (setup.py) ... done
  Created wheel for Kivy-Garden: filename=Kivy_Garden-0.1.4-py3-none-any.whl siz
e=4536 sha256=79043639f4dc0f5b97d4785449924f76d036711df442791babe60eb88f57ef11
  Stored in directory: c:\users\acer black\appdata\local\pip\cache\wheels\3f\43\
e3\50289d555356f0421d1c388c82d052d5788f22a34d0cd8659d
Successfully built Kivy-Garden
Installing collected packages: certifi, chardet, idna, urllib3, requests, Kivy-G
arden, kivy
Successfully installed Kivy-Garden-0.1.4 certifi-2020.6.20 chardet-3.0.4 idna-2.
10 kivy-1.11.1 requests-2.24.0 urllib3-1.25.10
WARNING: You are using pip version 20.2.2; however, version 20.2.3 is available.

You should consider upgrading via the 'C:\Users\Acer Black\Envs\kivyenv\Scripts\
python.exe -m pip install --upgrade pip' command.

(kivyenv) C:\Users\Acer Black>cd moviles

(kivyenv) C:\Users\Acer Black\moviles>dir
 El volumen de la unidad C no tiene etiqueta.
 El número de serie del volumen es: 3C57-3FF1

 Directorio de C:\Users\Acer Black\moviles

28/09/20  20:25    <DIR>          .
28/09/20  20:25    <DIR>          ..
28/09/20  20:25    <DIR>          Practicas_kivy_espanol
               0 archivos              0 bytes
               3 dirs  462,181,826,560 bytes libres

(kivyenv) C:\Users\Acer Black\moviles>cd Practicas_kivy_espanol

(kivyenv) C:\Users\Acer Black\moviles\Practicas_kivy_espanol>dir
 El volumen de la unidad C no tiene etiqueta.
 El número de serie del volumen es: 3C57-3FF1

 Directorio de C:\Users\Acer Black\moviles\Practicas_kivy_espanol

28/09/20  20:25    <DIR>          .
28/09/20  20:25    <DIR>          ..
               0 archivos              0 bytes
               2 dirs  462,185,246,720 bytes libres

(kivyenv) C:\Users\Acer Black\moviles\Practicas_kivy_espanol>git
"git" no se reconoce como un comando interno o externo,
programa o archivo por lotes ejecutable.

(kivyenv) C:\Users\Acer Black\moviles\Practicas_kivy_espanol>dir
 El volumen de la unidad C no tiene etiqueta.
 El número de serie del volumen es: 3C57-3FF1

 Directorio de C:\Users\Acer Black\moviles\Practicas_kivy_espanol

28/09/20  20:33    <DIR>          .
28/09/20  20:33    <DIR>          ..
22/09/18  22:24    <DIR>          Practicas_kivy_espanol-master
28/09/20  20:31        15,542,570 Practicas_kivy_espanol-master.zip
               1 archivos     15,542,570 bytes
               3 dirs  462,123,757,568 bytes libres

(kivyenv) C:\Users\Acer Black\moviles\Practicas_kivy_espanol>cd Practicas_kivy_e
spanol-master

(kivyenv) C:\Users\Acer Black\moviles\Practicas_kivy_espanol\Practicas_kivy_espa
nol-master>dir
 El volumen de la unidad C no tiene etiqueta.
 El número de serie del volumen es: 3C57-3FF1

 Directorio de C:\Users\Acer Black\moviles\Practicas_kivy_espanol\Practicas_kivy
_espanol-master

22/09/18  22:24    <DIR>          .
22/09/18  22:24    <DIR>          ..
22/09/18  22:24    <DIR>          Animatron
22/09/18  22:24    <DIR>          extra
22/09/18  22:24               550 README.md
22/09/18  22:24    <DIR>          SQLite 1
22/09/18  22:24    <DIR>          Temas con kivy
22/09/18  22:24    <DIR>          Tuto 01 Hola Mundo
22/09/18  22:24    <DIR>          Tuto 02 BoxLayout
22/09/18  22:24    <DIR>          Tuto 03 AnchorLayout
22/09/18  22:24    <DIR>          Tuto 04 FloatLayout
22/09/18  22:24    <DIR>          Tuto 05 RelativeLayout
22/09/18  22:24    <DIR>          Tuto 06 GridLayout
22/09/18  22:24    <DIR>          Tuto 07 StackLayout
22/09/18  22:24    <DIR>          Tuto 08 Button
22/09/18  22:24    <DIR>          Tuto 09 Label
22/09/18  22:24    <DIR>          Tuto 10 Properties
22/09/18  22:24    <DIR>          Tuto 11 IDs
22/09/18  22:24    <DIR>          Tuto 12 Instrucciones graficas
22/09/18  22:24    <DIR>          Tuto 13 Clock
22/09/18  22:24    <DIR>          Tuto 14 Builder
22/09/18  22:24    <DIR>          Tuto 15 atlas y clock
22/09/18  22:24    <DIR>          Tuto 16 Screenmanager
22/09/18  22:24    <DIR>          Tuto 17 Scroll view
22/09/18  22:24    <DIR>          UnaApp
               1 archivos            550 bytes
              24 dirs  462,126,837,760 bytes libres

(kivyenv) C:\Users\Acer Black\moviles\Practicas_kivy_espanol\Practicas_kivy_espa
nol-master>cd "Tuto 01 Hola Mundo"

(kivyenv) C:\Users\Acer Black\moviles\Practicas_kivy_espanol\Practicas_kivy_espa
nol-master\Tuto 01 Hola Mundo>dir
 El volumen de la unidad C no tiene etiqueta.
 El número de serie del volumen es: 3C57-3FF1

 Directorio de C:\Users\Acer Black\moviles\Practicas_kivy_espanol\Practicas_kivy
_espanol-master\Tuto 01 Hola Mundo

22/09/18  22:24    <DIR>          .
22/09/18  22:24    <DIR>          ..
22/09/18  22:24                83 main.kv
22/09/18  22:24               381 main.py
               2 archivos            464 bytes
               2 dirs  462,126,604,288 bytes libres

(kivyenv) C:\Users\Acer Black\moviles\Practicas_kivy_espanol\Practicas_kivy_espa
nol-master\Tuto 01 Hola Mundo>python main.py
[WARNING] [Config      ] Older configuration version detected (0 instead of 21)
[WARNING] [Config      ] Upgrading configuration in progress.
[INFO   ] [Logger      ] Record log in C:\Users\Acer Black\.kivy\logs\kivy_20-09
-28_0.txt
[INFO   ] [deps        ] Successfully imported "kivy_deps.gstreamer" 0.1.18
[INFO   ] [deps        ] Successfully imported "kivy_deps.angle" 0.1.10
[INFO   ] [deps        ] Successfully imported "kivy_deps.glew" 0.1.12
[INFO   ] [deps        ] Successfully imported "kivy_deps.sdl2" 0.1.23
[INFO   ] [Kivy        ] v1.11.1
[INFO   ] [Kivy        ] Installed at "C:\Users\Acer Black\Envs\kivyenv\lib\site
-packages\kivy\__init__.py"
[INFO   ] [Python      ] v3.7.9 (tags/v3.7.9:13c94747c7, Aug 17 2020, 18:58:18)
[MSC v.1900 64 bit (AMD64)]
[INFO   ] [Python      ] Interpreter at "C:\Users\Acer Black\Envs\kivyenv\Script
s\python.exe"
[INFO   ] [Factory     ] 184 symbols loaded
[INFO   ] [Image       ] Providers: img_tex, img_dds, img_sdl2, img_gif (img_pil
, img_ffpyplayer ignored)
[INFO   ] [Window      ] Provider: sdl2
[INFO   ] [GL          ] Using the "OpenGL" graphics system
[INFO   ] [GL          ] GLEW initialization succeeded
[INFO   ] [GL          ] Backend used <glew>
[INFO   ] [GL          ] OpenGL version <b'3.1.0 - Build 9.17.10.4229'>
[INFO   ] [GL          ] OpenGL vendor <b'Intel'>
[INFO   ] [GL          ] OpenGL renderer <b'Intel(R) HD Graphics'>
[INFO   ] [GL          ] OpenGL parsed version: 3, 1
[INFO   ] [GL          ] Shading version <b'1.40 - Intel Build 9.17.10.4229'>
[INFO   ] [GL          ] Texture max size <8192>
[INFO   ] [GL          ] Texture max units <16>
[INFO   ] [Window      ] auto add sdl2 input provider
[INFO   ] [Window      ] virtual keyboard not allowed, single mode, not docked
[INFO   ] [Text        ] Provider: sdl2
[INFO   ] [Base        ] Start application main loop
[INFO   ] [GL          ] NPOT texture support is available
[INFO   ] [Base        ] Leaving application in progress...
 Traceback (most recent call last):
   File "main.py", line 20, in <module>
     MainApp().run()
   File "C:\Users\Acer Black\Envs\kivyenv\lib\site-packages\kivy\app.py", line 8
55, in run
     runTouchApp()
   File "C:\Users\Acer Black\Envs\kivyenv\lib\site-packages\kivy\base.py", line
504, in runTouchApp
     EventLoop.window.mainloop()
   File "C:\Users\Acer Black\Envs\kivyenv\lib\site-packages\kivy\core\window\win
dow_sdl2.py", line 747, in mainloop
     self._mainloop()
   File "C:\Users\Acer Black\Envs\kivyenv\lib\site-packages\kivy\core\window\win
dow_sdl2.py", line 479, in _mainloop
     EventLoop.idle()
   File "C:\Users\Acer Black\Envs\kivyenv\lib\site-packages\kivy\base.py", line
339, in idle
     Clock.tick()
   File "C:\Users\Acer Black\Envs\kivyenv\lib\site-packages\kivy\clock.py", line
 563, in tick
     current = self.idle()
   File "C:\Users\Acer Black\Envs\kivyenv\lib\site-packages\kivy\clock.py", line
 543, in idle
     usleep(1000000 * sleeptime)
   File "C:\Users\Acer Black\Envs\kivyenv\lib\site-packages\kivy\clock.py", line
 727, in usleep
     _usleep(microseconds, self._sleep_obj)
   File "C:\Users\Acer Black\Envs\kivyenv\lib\site-packages\kivy\clock.py", line
 405, in _usleep
     _kernel32.WaitForSingleObject(obj, 0xffffffff)
 KeyboardInterrupt

(kivyenv) C:\Users\Acer Black\moviles\Practicas_kivy_espanol\Practicas_kivy_espa
nol-master\Tuto 01 Hola Mundo>
