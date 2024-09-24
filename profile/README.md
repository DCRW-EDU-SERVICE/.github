## Commit Message 규칙
> type: Subject -> 제목  
(한칸 띄우기)  
body(생략 가능) -> 본문  
(한칸 띄우기)  
footer(생략 가능) -> 꼬리말

** ex) feat: Add login api **

### Type<br>
- **feat** : 새로운 기능 추가, 기존의 기능을 요구 사항에 맞추어 수정
- **fix** : 기능에 대한 버그 수정
- build : 빌드 관련 수정
- chore : 패키지 매니저 수정, 그 외 기타 수정 ex) .gitignore
- ci : CI 관련 설정 수정
- docs : 문서(주석) 수정
- style : 코드 스타일, 포맷팅에 대한 수정
- refactor : 기능의 변화가 아닌 코드 리팩터링 ex) 변수 이름 변경
- test : 테스트 코드 추가/수정
- release : 버전 릴리즈 관리

참고자료 : https://kdjun97.github.io/git-github/commit-convention/

## 이슈 생성
- BUG Report: 버그 이슈 템플릿 사용하여 작성
- Feature Report: 기능 추가 요청 이슈 템플릿 사용하여 작성

( 다 템플릿 만듬 )

## Branch
- main : 제품으로 출시될 수 있는 브랜치. 여기서 작업 x (원래 이름 그대로)
- develop : 모든 기능이 추가되고 버그가 수정되면 develop 브랜치를 main 브랜치에 병합 (원래 이름 그대로)
- feature : 새로운 기능 개발, 버그 수정하는 브랜치. 로컬 저장소에서 관리. 개발 완료시 develop 브랜치로 merge (브랜치/기능 요약- (feature/home)
- release : 이번 출시 버전을 준비하는 브랜치 (release-1.7)
- hotfix : 출시 버전에서 발생한 버그를 수정 하는 브랜치 (hotfix-1.4.1)<br>
주로 main, develop, feature 쓰게 될 것 같아요 ! 

참고자료 : https://techblog.woowahan.com/2553/ | https://ej-developer.tistory.com/75
