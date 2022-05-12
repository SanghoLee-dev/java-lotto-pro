# 로또
## 진행 방법
* 로또 요구사항을 파악한다.
* 요구사항에 대한 구현을 완료한 후 자신의 github 아이디에 해당하는 브랜치에 Pull Request(이하 PR)를 통해 코드 리뷰 요청을 한다.
* 코드 리뷰 피드백에 대한 개선 작업을 하고 다시 PUSH한다.
* 모든 피드백을 완료하면 다음 단계를 도전하고 앞의 과정을 반복한다.

## 온라인 코드 리뷰 과정
* [텍스트와 이미지로 살펴보는 온라인 코드 리뷰 과정](https://github.com/next-step/nextstep-docs/tree/master/codereview)

---

# 2단계 문자열 덧셈기 요구사항 정리

---

* 숫자로 작성된 문자열을 입력한다.
* 입력받은 문자열을 분리한다.
* 분리한 문자열을 숫자로 변경한다.
* 변경된 숫자의 합을 구한다.
* 입력값이 빈값이 들어올경우 0을 반환한다.
* 기본 구분자는 (,) (;)
* 커스텀 구분자는 문자열 앞에 `//` 와 `\n`사이에 위치하는 구분자를 지정 할 수 있다.
* 숫자 혹은 음수가 입렵된 경우 RuntimeException 발생해야한다.


### to-do

- [x] 입력 값을 분할하는 객체를 추가한다.
- [x] 문자열을 숫자로 변경하는 객체를 추가한다.
- [x] 양의 정수 객체를 추가한다.
- [x] 문자열 숫자를 더하는 기능을 추가한다.

---
