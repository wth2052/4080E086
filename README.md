# 4080E086

6
lab@906f0d80ad09:/tmp/4080E086$ ^C
lab@906f0d80ad09:/tmp/4080E086$
lab@906f0d80ad09:/tmp/4080E086$
lab@906f0d80ad09:/tmp/4080E086$ ps aux w | grep socat
root       24408  0.0  0.0  24360  2888 pts/0    S    Oct12   0:00 socat TCP-LISTEN:2111,reuseaddr,fork EXEC:/bin/flag
lab        30313  0.0  0.0  11280  1084 pts/8    S+   03:40   0:00 grep --color=auto socat
lab@906f0d80ad09:/tmp/4080E086$

7
r=auto socat
lab@906f0d80ad09:/tmp/4080E086$ ^C
lab@906f0d80ad09:/tmp/4080E086$ curl 127.0.0.1
<!DOCTYPE html>
<html>
<head>
<title>BreakALLCTF</title>
</head>
<body>
BreakALLCTF{Ef94iSQPRI66Ws4ECqV9}
</body>
</html>lab@906f0d80ad09:/tmp/4080E086$

8
</html>lab@906f0d80ad09:/tmp/4080E086$ ^C
lab@906f0d80ad09:/tmp/4080E086$ tar zxvf ForYou.tar.gz
ForYou
lab@906f0d80ad09:/tmp/4080E086$

lab@906f0d80ad09:/tmp/4080E086$ vi ForYou

BreakALLCTF{U6TLCzQsk73HwcW7rqAW}

9

lab@906f0d80ad09:/tmp/4080E086$ file TobeExe
TobeExe: ELF 32-bit LSB executable, Intel 80386, version 1 (SYSV), dynamically linked, interpreter /lib/ld-linux.so.2, for GNU/Linux 2.6.32, BuildID[sha1]=10558357d3700c05f1426a6d2a09b920bda2e464, not stripped
lab@906f0d80ad09:/tmp/4080E086$ ls -al TobeExe
-rw-r--r-- 1 lab lab 7348 Nov 15  2017 TobeExe
lab@906f0d80ad09:/tmp/4080E086$ chmod +x Tobe exe
chmod: cannot access 'Tobe': No such file or directory
chmod: cannot access 'exe': No such file or directory
lab@906f0d80ad09:/tmp/4080E086$ chmod +x TobeExe
lab@906f0d80ad09:/tmp/4080E086$ ./TobeExe
BreakALLCTF{UvB3IUqxCCiTVxeOuWrL}
lab@906f0d80ad09:/tmp/4080E086$


10 

lab@906f0d80ad09:/tmp/4080E086$ chmod +x reverse
lab@906f0d80ad09:/tmp/4080E086$ strings reverse

lab@906f0d80ad09:/tmp/4080E086$
lab@906f0d80ad09:/tmp/4080E086$
lab@906f0d80ad09:/tmp/4080E086$ strings reverse | grep CTF
BreakALLCTF{VLJekKONoWld7ari6HHJ}
lab@906f0d80ad09:/tmp/4080E086$

strings reverse | grep CTF
