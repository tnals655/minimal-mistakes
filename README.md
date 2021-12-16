# tnals655.github.io

이름: 20213102 황수민   

## Project Build 과정

선택한 테마를 통해 Build를 하는 과정, 진행 중 이슈에 대해서 차례로 설명   

### 1. Build 과정
---

Github에서 [mmistakes/minimal-mistakes](https://github.com/mmistakes/minimal-mistakes) Repository를 fork하여 저장소 이름을 'tnals655.github.io'로 변경하였다.

이후 git clone 을 통해 로컬 저장소를 생성했고, 로컬 저장소에서 포스팅, 블로그 정보 수정 작업 등을 진행했다.   

블로그 수정 작업은 로컬 저장소 내에 _config.yml 을 통해 진행했다.

+ 사이트에 favicon 추가 완료
+ Google Analytics 적용 완료

### 2. 진행 중 이슈 (댓글 기능)
---

처음에 강의 시간에 시범으로 적용되었던 lanyon 테마를 이용했고, 이 테마에서 [Disqus](https://disqus.com)를 이용해 댓글 기능을 추가하려 했지만, 무슨 이유 때문인지 댓글 표시 창 자체가 뜨지 않았다. 원인을 찾으려 노력해보았지만, 결국 실패하였다.   

결국 테마를 바꿔서 진행해보기로 결정했고, lanyon 테마 대신 현재 테마인 minimal-mistakes 테마를 사용하기로 했다.
그러나, 이 테마에서도 똑같이 댓글 기능이 적용되지 않아 아예 Disqus가 아닌 다른 걸 이용해 댓글 기능을 추가하기로 했다.   

그래서 찾은 것이 바로 [utterances](https://github.com/utterance/utterances) 였다.   
그러나, utterances로 적용한 댓글 창마저도 표시되지 않았다...




