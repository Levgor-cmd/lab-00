## Отчёт к лабораторной работе 00

### Выполним инструкции, соглсно учебному материалу. Установим необходимые утилиты, выполнив следующие команды: (при необходимости подтверждаем)

```bash
sudo apt install cmake
sudo apt install curl
sudo apt install git
sudo apt install g++
sudo apt install make
sudo apt install tree
sudo apt install wget
sudo apt install openssl
```

### После установки утилит, проверим их версии

```bash
lev@debian:~$ cmake --version
cmake version 3.31.6

CMake suite maintained and supported by Kitware (kitware.com/cmake).



lev@debian:~$ curl --version
curl 8.14.1 (x86_64-pc-linux-gnu)


lev@debian:~$ git --version
git version 2.47.3



lev@debian:~$ g++ --version
g++ (Debian 14.2.0-19) 14.2.0
Copyright (C) 2024 Free Software Foundation, Inc.



lev@debian:~$ make --version
GNU Make 4.4.1



lev@debian:~$ tree --version
tree v2.2.1 © 1996 - 2024 by Steve Baker, Thomas Moore, Francesc Rocher, Florian Sesser, Kyosuke Tokoro



lev@debian:~$ wget --version
GNU Wget 1.25.0 для linux-gnu.



lev@debian:~$ openssl --version
OpenSSL 3.5.5 27 Jan 2026 (Library: OpenSSL 3.5.5 27 Jan 2026)
```

### После проверки сгенерируем персональный с правами гист и сохраним его в файл. Для этого переходим в настройки GitHub, где выбираем раздел Developer settings, затем Personal access tokens и Tokens classic. Генерируем новый токен с соответствующими правами доступа. Сохраняем токен в файл:

```bash
echo "{токен}" > github_token.txt
```
