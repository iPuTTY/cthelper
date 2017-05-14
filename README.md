cthelper
==

***cthelper*** 는 ***PTY*** helper 프로그램이며, ***iPuTTY***의 cygterm 백엔드를 사용할 때 필요 합니다.

***cthelper*** 는 [***PuTTYCyg***](https://code.google.com/archive/p/puttycyg/) 의 [putty-0.60-cygterm-20101029.patch](https://storage.googleapis.com/google-code-archive-downloads/v2/code.google.com/puttycyg/putty-0.60-cygterm-20101029.patch.gz) 에서 추출하였습니다.

## Build

***cthelper*** 빌드는 ***Cygwin*** 환경에서 할 수 있습니다.

 * ***Required***
   * Cygwin
   * gcc
   * make

***cthelper*** 디렉토리에서 다음의 명령으로 빌드를 합니다.

```bash
[user@host cthelper]$ make
make
cthelper.o
buffer.o
message.o
cthelper.exe
[user@host cthelper]$ 
```

## Usage

생성된 ***cthelper.exe*** 파일을 ***Cygwin*** 의 ***/bin*** 디렉토리에 복사 합니다.
