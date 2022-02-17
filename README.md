
#### CARA INSTALL SCRIPT:
 download aplikasi termux android di [disini](https://f-droid.org/repo/com.termux_117.apk)
 lalu buka aplikasinya ketikan perintah dibawah ini.
 ```
 $ pkg update && pkg upgrade
 $ pkg install python git clang
 $ pip install requests bs4 futures cython
 $ rm -rf zmbf
 $ git clone https://github.com/40R3C/zmbf
 ```
#### CARA MENJALANKAN SCRIPT:
 sekarang karena script sudah diinstall tinggal kita jalankan, ketikan perintah dibawah ini:
 ```
  $ cd zmbf
  $ cythonize -i zmbf.c
  $ python run.py
 ```
