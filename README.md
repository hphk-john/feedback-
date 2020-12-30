# 질문 & 피드백
특강 관련 질문 & 피드백

## Pull Request 연습 및 피드백
branch와 pull request를 활용하여 강의 피드백을 반영하기

1. 피드백 프로젝트(저장소)를 `clone` 받습니다.

2. 본인의 영어 이름의 `branch`를 생성 후 이동합니다.
    - ex) 
    ```shell
    $ git branch john
    $ git checkout john
    ```
3. 본인의 이름을 딴 마크다운 파일 `한글이름.md`을 생성 후, 이번 수업에 대한 질문, 기타 궁금한 사항, 피드백을 적습니다.

4. 해당 파일을 저장 후, `commit` 합니다.

5. 해당 커밋을 기존에 생성한 브랜치의 이름으로 `push` 합니다.
    - ex)
    ```shell
    $ git push origin john
    ```

6. push된 브랜치에 대한 `pull request`를 생성합니다.