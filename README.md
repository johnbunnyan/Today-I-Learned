
# TIL (Today-I-Learned) : 오늘 배운 내용을 README에 커밋으로 기록합니다.

<!-- 1️⃣ 날짜 및 기분 작성 -->
# 🗓 2022.09.13(화) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 기분: 🤩





<!-- 2️⃣ 대표문장 작성 -->
phaser 강의를 들었다.
-------------
<!-- 강조라인 -->


<!-- 3️⃣ 배운 내용 요약 -->
1. phaser 게임엔진
   * phaser는 2D게임을 구현하는 js의 대표적인 게임 프레임워크 중 하나이다.
     * 이어
  

2. 파이썬 웹 IDE
    - replit은 다양한 개발언어환경을 제공한다.
      - kaboom.js를 구현하고 배포하는 대표적인 공간.

3. 블로그보다 깃헙에 치중하기
   + 블로그는 작성하려면 번거로운 감이 사실 많았다.
     + 깃헙을 쓰면 커밋 연습도 하고 커밋 기록도 쌓이니 더 동기가 부여된다.  




-----
## 인상깊었던 모먼트🙃🙃🙃🙃🙃
<!-- 4️⃣ 인상깊었던 내용 선정 -->

> 
### 참사 현장
<img src="./image/Snapshot 5.png" width="40%" height="30%" title="100px" alt="이미지제목"></img>

### 리액트 코드
```javascript
        {!data.length ? <Nothing whatIsDisplayed={'Search'}></Nothing> : data.map((el, idx) => {
              console.log(el)
              console.log(idx)
              if (data.length - 1 === idx) {
                return (
                  <div ref={ref}>
                    <PostCase
                      key={idx}
```
~~코드 스테이츠 당시 프로젝트를 리펙토링하려고 하는데 에러난리가 나서 당황한 모먼트~~   
보아하니 인덱스를 못잡는 것 같다.
<br>
<br>
<br>
*프로젝트 파일을 다시 하나하나 뜯어봐야 한다. 심지어 내가 구현하지도 않은 팀원의 코드를.*

>   > 일단 phaser.js 먼저 조지고 시작하기로 결정.


-----
## 🔗 참고
<!-- 5️⃣ 참고링크 -->

<http://google.com>



















<!-- 🔴기타 마크다운 문법 참고 -->


<!-- <헤더>

# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6 -->



<!-- <인덱스>

1. 첫번째
2. 두번째
3. 세번째

* 빨강
  * 녹색
    * 파랑

+ 빨강
  + 녹색
    + 파랑

- 빨강
  - 녹색
    - 파랑 -->



<!-- <줄 긋기>

* * *

***

*****

- - -

--------------------------------------- -->


<!-- <인용구>

> This is a first blockqute.
>	> This is a second blockqute.
>	>	> This is a third blockqute. -->

<!-- <문자굵기>

*single asterisks*
**double asterisks**
~~cancelline~~ -->



<!-- <이미지 삽입>

<img src="./img/jesus.jpeg" width="40%" height="30%" title="100px" alt="이미지제목"></img> -->


<!-- <코드박스>

```javascript
public class BootSpringBootApplication {
  public static void main(String[] args) {
    System.out.println("Hello, Honeymon");
  }
}
``` -->

<!-- <표>

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell
-->


<!--<링크>

<http://google.com> -->