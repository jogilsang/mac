# mac
맥북을 받게된 엔지니어의 좌충우돌 적응기

## INDEX
- [세팅](#세팅)
  - [앱](#앱)
  - [크롬](#크롬)
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
  - [aws-vault](#aws-vault)
  - [node](#node)
  - [eksctl](#eksctl)
  - [awscorretto](#awscorretto)
  - [logo-ls](#logo-ls)
  - [envsubst](#envsubst)
  - [gdate](#gdate)
  - [autosuggestions](#autosuggestions)
  - [syntaxhighlighting](#SyntaxHighlighting)
  
---

### 세팅
#### 앱
- EasyRes - 해상도 변경 어플리케이션
- Whale - AWS Console 용 (맥북 사파리 가끔멈춤, 크롬 SG 등에서 버튼안누리는 에러)
  - 단축키 추가 : cmd +, cmd -
  - ![image](https://user-images.githubusercontent.com/20831981/187103083-a15a5ab2-5890-41d9-a7fe-95b5b1d84907.png)
- [내배경화면](https://apps.apple.com/kr/app/id1552826194?mt=12) - 동적인 바탕화면 앱 (optional)
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
![image](https://user-images.githubusercontent.com/20831981/194474887-048203aa-7ddb-47a2-94c7-8eae0c714d0f.png)


- [GIPHY Capture] - 화면의 이미지들을 움짤로 만들기
- [clipy](https://clipy.softonic.kr/mac) - 스니펫과 클립보드 히스토리를 이용해서 정보를 저장 및 사용
  - preference > shortcut > histroy unable
  - cmd + shift + b
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
  - settings - general - launch at start
  - settings - Notification sound - none
- kap - gif생성
- iterm2 - 터미널
- Slack - 비즈니스 채팅앱
  - 환경설정 - 고급 - Enter 누를 시 전송버튼 변경하기
![image](https://user-images.githubusercontent.com/20831981/173468202-699c39ec-52c8-4d80-8120-3863ecfdebc1.png)


#### 크롬
> 플러그인
- [Gmail Conversation Thread Reversal by cloudHQ](https://chrome.google.com/webstore/detail/gmail-conversation-thread/fkplphcelnmocakmefjmpnohnfgkibkk/related)
- Chrome 용 스크린 레코더
- Douga Getter
- Video Downloader Professional
- User-Agent Switcher for Chrome
- [Authenticator, Two-factor authentication in your browser](https://authenticator.cc/) - MFA 인증
- [multi-highlight](https://www.highlighty.app/) - 여러단어를 highlight
- [AWS Extend Switch Roles](https://dev.classmethod.jp/articles/lim-extend-switch-roles/) - Role switch 목록저장
- [MultiLogin](https://chrome.google.com/webstore/detail/multilogin/ijfgglilaeakmoilplpcjcgjaoleopfi) - 동일 브라우저 교차aws 계정
- [MultiLogin](https://chrome.google.com/webstore/detail/multilogin/ijfgglilaeakmoilplpcjcgjaoleopfi) - 동일 브라우저 교차aws 계정 접속
- Octotree - GitHub code tree
- [AWS Colorful Reader](https://chrome.google.com/webstore/detail/aws-colorful-navbar/kgifmgnlchjjippdpkblbdlfidcpceme/related)
- [darkreader](https://chrome.google.com/webstore/detail/dark-reader/eimadpbcbfnmbkopoojfekhnkhdbieeh?hl=ko) : aws console을 dark theme로 적용
  - 제외도메인
    - mail.google.com : 메일버튼 안보임
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
- Media
  - Video Downloader PLUS
  - Video Downloader professional
  - Douga Getter

> 커맨드
- chrome://about/
- chorme://versions/
- chrome://flags/
- chrome://quota-internals/
- chrome://sync-internals
- chrome://system
- chrome://crashes
- chrome://gpu
- chrome://histograms
- chrome://device-log/
  - this is unsafe

> 단축키
- cmd + option + i : [크롬개발자도구](https://developer.chrome.com/docs/devtools/)
- cmd + ctrl + f : 전체화면
- 하이라이트(pdf) : ctrl + command + h
  - https://velog.io/@modyhoon/MacOS-%EB%AF%B8%EB%A6%AC%EB%B3%B4%EA%B8%B0-%EC%95%B1-%EC%9E%90%EC%A3%BC-%EC%93%B0%EB%8A%94-%EB%8B%A8%EC%B6%95%ED%82%A4-%EC%A0%95%EB%A6%AC

#### 설정
- Finder - 옵션 - 모든 데스크탑 (화면이동시 같이 따라옴)
- 시스템환경설정 - 손쉬운사용 - 확대/축소 - 키보드 단축키를 사용하여 확대/축소 Check
  - control + option + 8 : 포인터 지점 확대/축소
- 시스템환경설정 - 손쉬운사용 - 키보드 - 느린키활성화 - 반응속도 최대한 짧게
- 시스템환경설정 - 키보드 - 텍스트 - 맞춤법관련 체크해제 및 OFF하기
- 시스템환경설정 - 사운드효과 - 소리최소화
- 시스템환경설정 - 키보드 - 단축키설정 - 스크린샷 - 선택한영역 클립보드로 복사 - command + shift + 4
- Caps Lock 버튼을 한영 전환키로 사용하는 경우 아래의 방법으로 Caps Lock을 키고 끌 수 있습니다.
- 라인,슬랙 : 시스템 설정 - 알림 및 집중모드 - 미리보기 표시 - 항상
- 지메일 : 설저 - 기본설정 - 데스크톱 알림 - mac에서 보려며 알림확인 클릭
- cmd+q : "시스템 환경 설정 > 일반"을 클릭 후 "앱을 종료하면 윈도우 닫기" 
- 시스템환경설정 - 손쉬운사용 - 디스플레이 - 동작줄이기 체크
- 클렘셀 모드 (노트북 덮개 닫아도 실행) 라는게 아래조건 충족 시 자동으로 있음
  - 전원선 연결
  - 외장 마우스,키보드 연결
  - 모니터 연결
- Finder(탐색기) - 환경설정 - 고급 - 현재폴더에서 검색

#### vscode
- Themarro (theme, 테마)
  - ![image](https://user-images.githubusercontent.com/20831981/231071341-90e3f186-1d34-425c-ba00-30df93ff9468.png)
- keymap 변경
  - deleteline : control + y
- Extention
  - Paste Image - 클립보드 이미지를 mkdown에 추가하기
    - setting - keyboard shortcut - Paste Image (extention.pasteImage) - cmd control v
    - setting - keyboard shortcut - 키바인딩 된 다른 키 제거 - cmd control v
  - IntelliJ IDEA Keybindings - 잘 사용하는 편집기의 단축키를 vscode에 적용하기
  - One Dark Pro - theme를 적용할 수 있음
  - vscode-pdf - pdf파일을 vscode로 볼 수 있음
- code 명령어설정
```sh
vi ~/.zshrc
# 맨 밑에 추가
code () { VSCODE_CWD="$PWD" open -n -b "com.microsoft.VSCode" --args $* ;}
# 적용
source ~/.zshrc

```

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
- 빠른실행도구모음
  - ![image](https://user-images.githubusercontent.com/20831981/180003019-8b478211-cdcc-4423-b5b2-3937791973fc.png)

> PPT 단축키

- ppt 여러개 파일 중 하나 : ctrl + 아래방향키
- ppt 파일 간 화면이동 : cmd + ~
- 그리기 모드 토글 : COMMAND + CONTROL + Z
- 하이퍼링크 추가 : cmd + k
- 개체이동 : TAB, shift + TAB
- 텍스트 이동 : 텍스트 선택 후 shift 방향키
- 그림크기 조절 : shift + 방향키
- 그림회전 : option + 방향키
- 텍스트 창옵션 : cmd+t, cmd+option+m
- 텍스트 좌,우,중앙정렬 : cmd + e,l,r
- 화면보기 변경(일반,여러 슬라이드, 개요, 노트) : command + 1,2,3,4
- 마스터 화면보기 변경(일반,여러 슬라이드,개요,노트) : cmd + option + 1,2,3,4
- [Keyboard shortcuts for Microsoft PowerPoint on Mac](https://www.idownloadblog.com/2020/10/02/keyboard-shortcuts-microsoft-powerpoint-mac/)

- 기본 텍스트 상자지정
- ex : 나눔고딕 -> 내가원하는 폰트로 신규 텍스트 생성
- 테마글꼴 저장 - 슬라이드 마스터
- CTRL + Z, CTRL + Y
- 텍스트효과 + 휘기
- 폼 - 글머리기호, 눈금자로 조정가능, 눈금선
- 언어교정 - 자동고침옵션
- 글머리 및 기호매기기 - 시작번호매기기 수정
- EX) 1,2,3 -> 1,5,6
- 파워포인트 줄간격 - 배수
- 제목 1.3
- 본문 1.2,1.3
- 단락 뒤
- CTRL + Y 는 내가 실행했던 기능을 반복해줌
- 가나 -> 좁게 -> 값 증가
- ctrl 누르고 움직이면 복사
- ctrl+ shift + c -> ctrl + shift + v
- f2 글상자 편집 - TAB키로 이동가능
- 서식 - 맞춤 - 왼쪽맞춤,오른쪽맞춤
- 오른쪽마우스 - 빠른 실행도구모음에 추가
- 서식 - 도형병합 - 빼기
- 쉬프트를 누르고 좌우로 누르면, 크기가 조절됨
- 그룹을 하고 크기를 키우면, 기준점이 맞게됨
- ALT + PRINTSCREEN
- 서식 - 색 - 투명한 색지정


---

### 단축키 변경
> - 윈도우의 ctrl은 맥북에서는 command 라고 볼 수 있다
  - 닫기
    - cmd + w

- Spotlight : control + r
- Finder열기 : Option⌥ + Command⌘  + space bar
- 캡쳐사진 클립보드에 복사하기
```
시스템 환경설정 - 키보드 - 단축키 - 스크린샷 - 선택한 영역의 그림을 클립보드에 복사 (check)
              키보드 - 단축키 - 스크린샷 - 선택한 영역의 그림을 파일로 저장 (x)
```
- 런치패드 바로가기 - 커멘트 + L 로해보기-
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
    - https://goodgid.github.io/iTerm2-Natural-Text-Editing/
    - ![image](https://user-images.githubusercontent.com/20831981/194482496-aa42760c-0e71-4c31-914e-f2ff737ccfe3.png)

  - 2\. 실행단축키 설정
    - Preferences - Keys - Hotkey - (option + space)
  - 3\. 타이틀바 밑에 1px 라인 제거
    - Appearance > Windows > Show line under title bar when the tab bar is not visible: 체크 안함

- #### brew
  ```sh
  #1. Homebrew 설치 및 Path 설정
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
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

    # 4. 폰트 줄간격 변경
    Profiles > Text: n/n 줄간격 100 - 50 으로 변경
    ```
  - 참조
  - https://github.com/ohmyzsh/ohmyzsh

#### python
```sh
vi .zshrc
alias python='python3'
source .zshrc
python --version
```

#### kubectl
```sh
brew install kubernetes-cli
```

#### kubeval
```sh
brew tap instrumenta/instrumenta
brew install kubeval
```

#### aws
```sh
# 설치 후 설치 경로 확인(which 명령어로 확인), 설치가 잘 되었는지 확인
brew install awscli

which aws
aws --version
```
#### aws-vault
> 콘솔열기 용이, CLI 인증제공
```sh
# 설치출처 : https://www.44bits.io/ko/post/securing-aws-credentials-with-aws-vault

brew install aws-vault
aws-vault --version

aws-vault add chogilsang@captain
- Enter Access Key ID: AKIATTI2VDLZXHFFHEVW
- Enter Secret Access Key:
- Added credentials to profile "chogilsang@captain" in vault

# Example
# CLI 명령어 실행해보기
sudo aws-vault exec chogilsang@captain -- aws s3 ls

# 콘솔화면 열기
aws-vault login chogilsang@captain

```

#### logo-ls
  - 실행되지않는 프로그램 : 시스템 환경설정 - 보안 및 개인정보 보호 - 다음에서 다운로드 한 앱 허용
  - 출처 : https://blog.dnd.ac/settings-mac-terminal/
  - <img width="623" alt="image" src="https://user-images.githubusercontent.com/20831981/171620366-92d34352-745e-47bb-8ccd-f33c3089961b.png">

#### awscorretto
```
https://aws.amazon.com/ko/corretto/?filtered-posts.sort-by=item.additionalFields.createdDate&filtered-posts.sort-order=desc
wget https://corretto.aws/downloads/latest/amazon-corretto-17-x64-macos-jdk.pkg 
java —vision
javac -version
echo 'export JAVA_HOME=$(/usr/libexec/java_home -v 11)' >> ~/.zprofile
```

#### envsubst
> yaml > template
```
brew install gettext
```

#### node
```
https://nodejs.org/ko/  
node —version 
```

#### eksctl
```
https://github.com/weaveworks/eksctl
open eksctl
echo 'export PATH=$PATH:$HOME/k8sbook/bin' >> ~/.zprofile
```

#### gdate
> mac에서는 date명령어로 mill세컨트드를 표시할 수 없음
```
# you will have a version of date that supports milliseconds.
# https://apple.stackexchange.com/questions/135742/time-in-milliseconds-since-epoch-in-the-terminal

brew install coreutils
gdate +%s.%N
# 1655610273046338000
```

#### AutoSuggestions
```sh
# 설치
brew install zsh-autosuggestions

# 적용 (.zshrc 맨 밑에 추가해야 터미널을 껐다 켜도 적용됨)
# 환경에 따라 zsh 파일 위치가 다를 수 있으므로 설치 후 터미널 가이드 참고
source /opt/homebrew/share/zsh-autosuggestions/zsh-autosuggestions.zsh
```

#### dig
- DNS 질의
```sh
brew install dig
```

#### SyntaxHighlighting
```sh
# 설치
brew install zsh-syntax-highlighting

# 적용 (.zshrc 맨 밑에 추가해야 터미널을 껐다 켜도 적용됨)
# 환경에 따라 zsh 파일 위치가 다를 수 있으므로 설치 후 터미널 가이드 참고
source /opt/homebrew/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh
```

#### 압축하기
### tar.gz 형식으로 압축하기
### EX : tar -zcvf [파일명] [파일경로]
tar -zcvf web-php-v2.tar.gz ./web-php-v2

---

### EKS 세팅

aws eks --region <지역> update-kubeconfig --name <클러스터 이름>
sudo security add-trusted-cert -d -r trustRoot -k /Library/Keychains/System.keychain /usr/local/share/ca-certificates/amazon.crt



