# Git Command

## git init

Git에게 "이 디렉토리에서 작업을 하겠다" 라고 알려주는 것

## git status

현재 상태에 대해서 알려준다

만약에 새로운 파일이 생성되었다면 `git status` 명령어를 입력하면 Untracked files로 분류가 된다.

## git add (파일명)

해당 파일을 Tracked 상태로 바꿔준다. 이때부터 `commit`이 가능하게 된다.

## git commit

변경 사항들을 커밋하는 명령어로 `git commit`를 하게되면 vim이 실행된다

이때 커밋을 설명하는 `commit message`를 작성할 수 있다.

## git log

저장소의 커밋 이력을 보여준다

내용은 커밋 날짜, 커밋 아이디, 커밋한 사람의 정보를 알려준다

## git diff (commit id)...(commit id2)

두 커밋의 차이에 대해서 출력이 된다.

## git reset (돌아가길 원하는 시점의 커밋 아이디)

커밋 이력을 되돌린다.

해당 명령어에 대한 여러 옵션이 있다

주의사항으로는 push를 한 후에는 reset을 하면 안된다.

## git revert (취소할 시점의 커밋 아이디)

revert는 reset과 유사한데

reset : 해당 시점으로 돌아가기

revert : 해당 시점을 삭제하고 새 버전을 생성
