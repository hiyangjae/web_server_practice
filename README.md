# web_server_practice

웹사이트 만들기 위해서 연습!!!

## 설치

`sudo apt isntall nginx`

기본 포트가 80으로 설정되어 있음

## 설정

### 기본적인 설정 파일 위치

```
/etc/nginx/nginx.conf
```

### 추가적인 설정 파일 위치

```
/etc/nginx/sites-enabled/default
```

여기에서 포트나 root 폴더 지정 가능

### 웹페이지 주소

```
http://175.117.20.132:8080
```

### nginx 다시 로드 하기

|                        |        |
| :--------------------: | :----: |
| `sudo nginx -s start`  |  시작  |
|  `sudo nginx -s stop`  |  중지  |
| `sudo nginx -s reload` | 리로드 |

### 폴더 구조

```
www
  │  index.html
  │
  ├─css
  │      Calculator.css
  │
  ├─html
  │      1.html
  │      2.html
  │      3.html
  │      Calculator_main.html
  │
  ├─js
  │      Calculator.js
  │
  └─res
          IMG_4294.JPG
          MVI_4222.MP4
          유튜브 프로필 사진최종(원형).png
```
