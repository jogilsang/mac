# mac
맥북을 받게된 엔지니어의 좌충우돌 적응기

## INDEX
- [세팅](#세팅)
  - [앱](#앱)
  - [플러그인](#플러그인)
  - [설정](#설정)
  - [vscode](#vscode)
- [PPT](#ppt)
- [단축키](#단축키)
  - 닫기
- [패드](#패드)
- [iterm](#iterm)
  - [brew](#brew)
  - [zsh](#zsh)
  - [python](#python)
  - [aws](#aws)
  - [node](#node)
  - [eksctl](#eksctl)
  - [awscorretto](#awscorretto)
  - [logo-ls](#logo-ls)
  - [envsubst](#envsubst)
---

### 세팅
#### 앱
- Copyless 2 - 클립보드 히스토리 앱
- twitter - 트위터 앱
- spark - 이메일 앱
- spectacle - 분할화면
```
시스템 환경설정 -> 보안 및 개인정보보호 -> 개인정보보호 -> 좌측하단 자물쇠 클릭 -> 
애플계정 비밀번호 입력 -> 손쉬운 사용 -> Spectacle 체크
출처: https://dailylog2020.tistory.com/10 [알아두면 언젠가, 쓸모있을 정보들.:티스토리]

check - launch spectacle at login
in the status menu
```
![image](https://user-images.githubusercontent.com/20831981/173234394-17178596-35a6-40b6-89ed-eaf83aad3597.png)


- fork - [git 브런치 툴](https://git-fork.com/)
- [Twilio Authy - MFA 모바일 앱과 mac 앱으로도 사용가능](https://authy.com/download/)
  - 모바일부터 설치하고, 멀티디바이스 enalbe 한뒤 stanby로 데스크톱도 설치
- cheatsheet app - 맥북 단축키 알려줌
- alfred - 어플리케이션 실행, 파일찾기
  - en 다음 원하는단어
  - youtube
  - 웹사이트 단어
  - 커맨드+스페이스
- karabiner-element - 단축키 관리
  - 한영키 : Simple Modification - add Item -> Fromkey(Right_option) -> to Key (f18)
- be focused - 포모도르
- kap - gif생성
- iterm2 - 터미널

#### 플러그인
> 크롬

- Octotree - GitHub code tree
- [AWS Colorful Reader](https://chrome.google.com/webstore/detail/aws-colorful-navbar/kgifmgnlchjjippdpkblbdlfidcpceme/related)
- [darkreader](https://darkreader.org/help/en/) : aws console을 dark theme로 적용
- Turn Off the Lights
- User-Agent Switcher for Chrome : 웹 요청의 user-agent 헤더 변경가능
- Browsec VPN : 국가정보 변경접속하기
- cacoo : 아키텍처 그리기
  - 커뮤니티 : https://community.nulab.com/c/cacoo/12
  - 단축키 : https://support.cacoo.com/hc/en-us/articles/900005489286-Shortcut-keys
- liner : 화면에 밑줄표시
- vimum : 마우스없이 키보드로 화면이동
  - ag 슬라이드 이동
  -f 누르면 클릭효과

> 
- cmd + option + i : 개발자도구
- cmd + ctrl + f : 전체화면

#### 설정
- 시스템환경설정 - 키보드 - 단축키설정 - 스크린샷 - 선택한영역 클립보드로 복사 - command + shift + 4
- Caps Lock 버튼을 한영 전환키로 사용하는 경우 아래의 방법으로 Caps Lock을 키고 끌 수 있습니다.
- 라인,슬랙 : 시스템 설정 - 알림 및 집중모드 - 미리보기 표시 - 항상
- 지메일 : 설저 - 기본설정 - 데스크톱 알림 - mac에서 보려며 알림확인 클릭
- cmd+q : "시스템 환경 설정 > 일반"을 클릭 후 "앱을 종료하면 윈도우 닫기" 
- 시스템환경설정 - 손쉬운사용 - 디스플레이 - 동작줄이기 체크
- 클렘셀 모드 : 덮개 닫아도 실행 
  - 전원선 연결
  - 외장 마우스,키보드 연결
  - 모니터 연결

#### vscode
- Paste Image - 클립보드 이미지를 mkdown에 추가하기
- IntelliJ IDEA Keybindings - 잘 사용하는 편집기의 단축키를 vscode에 적용하기
- One Dark Pro - theme를 적용할 수 있음
- vscode-pdf - pdf파일을 vscode로 볼 수 있음

---

#### PPT 
- [add-in](https://appsource.microsoft.com/en-us/marketplace/apps?src=office)
  - QR4Office : QR코드생성
  - pexels free stock images : 무료 
  - pixton comic characters : 캐릭터 이미지 사용
  - pro word cloud : 단어목록을 통해 이미지 생성
  - emoji keyboard
  - pickit
- MS 업데이트 끄기
  - https://iboxcomein.com/block-mac-office-updates/


- ctrl + 아래방향키 : ppt 여러개 파일 중 하나 
- [Keyboard shortcuts for Microsoft PowerPoint on Mac](https://www.idownloadblog.com/2020/10/02/keyboard-shortcuts-microsoft-powerpoint-mac/)


---

### 단축키
> - 윈도우의 ctrl은 맥북에서는 command 라고 볼 수 있다
  - 닫기
    - cmd + w

- Finder열기 : Option⌥ + Command⌘  + space bar
- 캡쳐사진 클립보드에 복사하기
```
시스템 환경설정 - 키보드 - 단축키 - 스크린샷 - 선택한 영역의 그림을 클립보드에 복사 (check)
              키보드 - 단축키 - 스크린샷 - 선택한 영역의 그림을 파일로 저장 (x)
```
- 런치패드 바로가기 - 커멘트 + ㅣ 로해보기-
- 상단제어센터 아이콘 - CMD누른채로 빼기
- 브라우저 - 탭그룹 저장가능
- 새로운폴더에 한꺼번에 다 넣기 : cmd + ctrl + n
- 파일정보확인 : cmd + i
- 새로운 FINDER : cmd + option + n
- FINDER 전환 : CMD + `
- 동영상 Rotate변환 : cmd+r
- 바탕화면보기 + CMD + F3
- 미션컨트롤 : 컨트롤 + 위방향키/f3
- 텍스트만 복사 : cmd + shift + v 

#### 브라우저
- cmd + option + 상,하 : 탭 그룹이동

---

### 패드
- 마우스패드가 아니라 `트랙패드` 라고한다.
- 두 손가락으로 위아래로 굴리면, 스크롤
- 세 손가락으로 누르면, 화면생성
- 세 손가락으로 좌우로 굴리면, 화면이동

---

### iterm
- 단축키
  - 전체/부분 선택 `Command + Shift + I`- 
  - 터미널히스토리 보기	`Shift + Cmd + H`
  - 가로 분할 `Command + D` 
  - 세로 분할 `Command + Shift + D`
- 세팅
  - 1\. 편집키 적용
    - profiles - open profiles - keys - presets - natural text edditing
  - 2\. 실행단축키 설정
    - Preferences - Hotkey
  - 3\. 기본 전체화면 설정
    - profile - window - style - maximized 체크

- #### brew
  ```sh
  #1. Homebrew 설치 및 Path 설정
  /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
  echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/user/.zprofile
    eval "$(/opt/homebrew/bin/brew shellenv)"

  #2. telnet설치
  brew tap theeternalsw0rd/telnet
  brew install telnet
  ```
- #### zsh
  - 설치
    - sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
  - theme
    ```sh
    vi ~/.zshrc
    ZSH_THEME="node"
    ```
    - https://github.com/ohmyzsh/ohmyzsh/wiki/Themes
    - https://github.com/ohmyzsh/ohmyzsh/wiki/External-themes
      - <img width="675" alt="image" src="https://user-images.githubusercontent.com/20831981/169723114-297f3e7d-3d17-4908-adfe-8e34bbe4e028.png">
    - https://github.com/skuridin/oh-my-zsh-node-theme
  - font 및 한글적용
    ```sh
    # 1. 글꼴설치
    brew tap homebrew/cask-fonts
    brew install --cask font-fira-mono-nerd-font

    # 터미널 설정에서 편집 – 프로파일 기본 설정
    # 사용자 지정 글꼴 : FiraMono Nerd Font 변경

    # 3. 자음분리현상 : iterm설정 >  profile > 해당 프로필 선택  > Text  Tab > Unicode  Field의 "Unicode normalization from" -> None -> NFC로 변경 
    ```
  - 참조
  - https://github.com/ohmyzsh/ohmyzsh

#3. code 명령어설정
```sh
vi ~/.zshrc
# 맨 밑에 추가
code () { VSCODE_CWD="$PWD" open -n -b "com.microsoft.VSCode" --args $* ;}
# 적용
source ~/.zshrc

```

- python
```sh
vi .zshrc
alias python='python3'
source .zshrc
python --version
```

- aws
```sh
# 설치 후 설치 경로 확인(which 명령어로 확인), 설치가 잘 되었는지 확인
brew install awscli

which aws
aws --version
```
- logo-ls
  - 실행되지않는 프로그램 : 시스템 환경설정 - 보안 및 개인정보 보호 - 다음에서 다운로드 한 앱 허용
  - 출처 : https://blog.dnd.ac/settings-mac-terminal/
  - <img width="623" alt="image" src="https://user-images.githubusercontent.com/20831981/171620366-92d34352-745e-47bb-8ccd-f33c3089961b.png">

- awscorretto
```
https://aws.amazon.com/ko/corretto/?filtered-posts.sort-by=item.additionalFields.createdDate&filtered-posts.sort-order=desc
wget https://corretto.aws/downloads/latest/amazon-corretto-17-x64-macos-jdk.pkg 
java —vision
javac -version
echo 'export JAVA_HOME=$(/usr/libexec/java_home -v 11)' >> ~/.zprofile
```

- envsubst
> yaml > template
```
brew install gettext
```

- node
```
https://nodejs.org/ko/  
node —version 
```

- eksctl
```
https://github.com/weaveworks/eksctl
open eksctl
echo 'export PATH=$PATH:$HOME/k8sbook/bin' >> ~/.zprofile
```


    
