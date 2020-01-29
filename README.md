# MACOS 개발환경을 위한 기본 설정

1. `homebrew` 설치
    - 터미널에 아래 코드 입력
    ```bash
   /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" 
   ```

2. `git` 설치
    - 터미널에 아래 코드 입력
    ```bash
   brew install git 
   // 설치 완료 후 확인 
   git --version
   ```
   
3. `nvm` 설치
    - 터미널에 아래 코드 입력
    ```bash
   curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.31.3/install.sh | bash
   // 설치 완료 후 확인
   nvm
   ```
   - 만약 `nvm:command`를 찾을 수 없다면
   ```bash
   touch ~/.bash_profile
   // 파일을 생성 후 위 설치 스크립트 다시 실행
   ```
   - 사용설명은 [NVM](https://github.com/nvm-sh/nvm)에서 확인
   - [Node site](https://nodejs.org/ko/)에서 버전 확인 후 `nvm install 버전`으로 설치
   - `node -v`로 노드 설치 확인
   - `npm -v`로 npm 설치 확인
   
4. `iterm2` 설치
    - [iterm2](https://www.iterm2.com/downloads.html)에서 설치파일 다운로드
    - zsh 설치 `brew install zsh`
    - 기타 테마 설치 참고주소 [참고](https://tutorialpost.apptilus.com/posts/tools/mac-cli-with-iterm2-zsh/)