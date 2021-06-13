# 뉴크 다운로드 및 설치

## TheFoundry 가입
foundry.com에 가입을 해야 제품을 다운로드 할 수 있습니다.

가입을 진행합니다.

https://www.foundry.com/products/nuke/try-nuke 를 클릭하고 로그인해서 제품을 다운로드 받으세요.

## 설치

```bash
$ cd ~/Downloads
$ tar -xvf Nuke12.2v5-linux-x86-release-64.tgz
$ ./Nuke12.2v5-linux-x86-release-64-installer
```

관리자(root) 계정으로 뉴크를 설치하지 않았습니다.
관리자의 개입을 최소화 하기 위함입니다.
사용자 권한으로 설치하게 되면 뉴크는 홈디렉토리에 설치됩니다. 위치는 아래와 같습니다.

```
~/Nuke12.2v5
```

## 에러
아래 에러가 발생하면 mesa-libGLU를 설치해주세요.
```
Failed to load libstudio-12.2.5.so: libGLU.so.1: cannot open shared object file: No such file or directory
```

```
# yum install mesa-libGLU
```
