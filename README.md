# Lab6

# version control
-소프트웨어 개발, 문서 작업에 중요, Git을 사용해 체계적으로 가능

# Changes vs. Snapshots
- 파일에 변화된 부분만 저장하는 방식
- git 에서는 Snapshots 이용

# Local, Centralized, and Distributed Version Control
- Local = 자신의 컴퓨터에만 버전에 대한 데이터 베이스 저장
- Centralized = 중앙 서버에서 데이터 베이스 관리
- Distributed = 중앙 서버에도 있고 각각의 컴퓨터에도 있음

# Three States in Git
- Working Directory, Stating Area, Git directory

# Git config
- System level: --system option. Affects all uses and repositories on the system (administrative)
 file: /etc/gitconfig
- Global (user) level: --global option. Affects all repositories of a current user
 file: ~/.config/git/config
- Local level: --local option. Specific to the current repository
 file: .git/gitconfig

## $ git init
- Initializing a Repository in an Existing Directory

## $ git status
- Checking Repository Status

## $ git add [file_name]
- Adding a new file to be staged (tracked)
- Tip
If there is a problem on nano (in Windows),
you can edit the file in any other text editor
(e.g., 메모장)

## $ git add
- Adding all files to be staged

## $ git rm --cached [file_name]
- Unstaging a file

## Ignoring a file

## Commit

## Change branch name
