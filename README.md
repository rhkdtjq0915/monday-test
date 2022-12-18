># HTML, CSS, JavaScript에 대해 기술하시오.
-HTML : 웹 문서를 만들기 위하여 사용하는 기본적인 웹 언어의 한 종류이며, 웹 페이지에서 제목, 이미지, 동영상, 문단, 표, 등을 정의하고 그 구조와 의미를 부여하는 정적 언어이다. 웹의 구조를 담당.   
   
-CSS : HTML로 만들어진 문서의 (컬러, 폰트, 스타일, 레이아웃, 반응형 특징 등의) 스타일을 지정하는 방식의 규정하는 스타일 시트 언어이며, CSS는 웹사이트를 시각적으로 더 매력적으로 만드는 기능을 제공한다.   
   
-JavaScript : 브라우저 자체에서 내장된 해석기능을 이용한 클라이언트 기반의 일종의 스크립트 언어이다. 콘텐츠를 바꾸고 움직이는 등 페이지를 동적으로 구며주는 역할을 하는 프로그래밍 언어이다.

------------------------------------------------------

># ECMAscript에 대해 기술하시오.
-Ecma라는 기관이 만든 script 언어이며, ECMA-262 표준을 따르고 있다. ECMA-262는 규격이며, ECMAScript는 ECMA-262에 의해 표준화된 자바스크립트의 새로운 이름이다.

------------------------------------------------------

># typescript에 대해 기술하시오.
-마이크로스프트에서 구현한 JavaScript의 슈퍼셋(superset) 프로그래밍 언어. 확장자로는 .ts를 사용하며, 컴파일의 결과물로 JavaScript 코드를 출력한다. 최종적으로 런타임에서는 이렇게 출력된 JavaScript 코드를 구동시키게 된다.

-----------------------------------------------------

># 자신을 소개하는 HTML태그 기술/ 태그마다 DOM객체 노드 형식으로
![ASDF](https://user-images.githubusercontent.com/80075223/208042276-0ee09600-bf15-4d3e-8ebb-6764de80e362.JPG)

-----------------------------------------------------

># Reflow와 Repaint
-Reflow : DOM 요소의 기하학적 속성이 변경될 떄 , 브라우저 크기가 변할 때, 스타일 시트가 로딩 되었을 때 발생ㅎ아는 변화들을 다시 계산 해주는 작업을 뜻한다.   
   
-Repaint : 변경된 요소를 실제로 화면에 그려주는 작업이고, Reflow가 발생하면 필연적으로 Repaint가 실행된다.

-----------------------------------------------------

># 자바스크립트에서 객체를 만드는 3가지 방법에 예와 함께 기술하시오.
1.newObject() 생성자 사용
```
 * @type {Object}
 */
let Human = new Object();
Human.name = 'alba';
Human.sex = 'female';
```
   
2.객체 리터럴 방식 사용하기
```
let Human2 = {
  name: 'john',
  sex: 'male'
};
```
   
3.프로토타입 객체
```
var student = {
  name: 'Lee',
  score: 90
};

// student에는 hasOwnProperty 메소드가 없지만 아래 구문은 동작한다.
console.log(student.hasOwnProperty('name')); // true

console.dir(student);
```

-----------------------------------------------------

># 이벤트 리스너를 작성하는 4가지 방법에 대해 예와 함께 기술하시오.
```java
function over() {
		p.style.backgroundColor="orchid";
}
```
1.HTML 태그 내에서 작성
```
<p id="p" onmouseover="this.style.backgroundColor='orchid'"
	마우스 올리면 orchid 색으로 변경
</p>
```   
   
2.DOM 객체의 이벤트 리스너 프로퍼티 작성
```
function over() {
	p.style.backgroundColor="orchid";
}
p.onmouseover = over;
```
   
3.DOM 객체의 addEventListener() 메소드 이용
```
p.addEventListener("mouseover", over);
```
   
4.익명 함수 이용
```
p.onmouseover = function () { this.style.backgroundColor="orchid"; }; 
```
-----------------------------------------------------

># SPA MPA SCR CSR에 대해 기술하시오.
SPA(Single Page Applicaton)는 말 그래도 하나의 파일로 전체 사이트를 구현한다는 뜻이다.   
   
MPA(Multi Page Application) 다중 페이지 응용프로그램이라고 불리기도 하며, 전통적인 웹 애플리케이션 개발 방식이다.   
   
SSR은 서버에서 첫 페이지의 렌더링을 클라이언트 측이 아닌 서버 측에서 처리해주는 방식.   
   
CSR는 웹 페이지의 렌더링이 클라이언트(브라우저) 측에서 일어나는 것을 의미.   

------------------------------------------------------

># 인의예지신 
인은 측은지심으로 불쌍한 것을 가엾게 여겨 정을 나누는 마음   
의는 수오지심으로 불의를 부끄러워하고 약한 것을 미워하는 마음   
예는 사양지심으로 겸손하여 남을 위해 사양하고 배려하는 마음   
지는 시비지심으로 옳고 그름을 가릴 줄 아는 마음   
신은 광명지심으로 중심을 잡고 가운데 바르게 서 밝은 빛을 냄으로 믿음을 주는 마음   
   
지나치게 인자한 사람은 세상이 그를 얕잡아 우습게 알고   
지나치게 의로운 사람에게는 적이 많은 법이며   
지나치게 예를 갖춘 사람은 간사한 사람으로 오해받기 쉽고   
지나치게 지혜로운 사람은 가시꾼이 아닐까 경계의 대상이 되기 싶고   
지나치게 남을 잘 믿는 사람은 다른 사람에게 이용당하기 십상이다.   

># 중도
불수편애편오 왈인 : 치우쳐 사랑하거나 미워한다는 평을 받지 않는 것이 인이요.   
불수전시전비 왈의 : 모두 옳다거나 모두 그르다는 평을 받지 않는 것이 의요.   
불수전강전편 왈예 : 너무 강하다거나 너무 의만을 따른다는 평을 받지 않는 것이 지요.   
불수자총자명 왈지 : 방자하게 총명함을 뽐내는 평을 받지 않는 것이 지요.   
불수남물남욕 왈신 : 함부로 낭비하고 과한 욕심을 부린다는 평을 받지 않는 것이 신이라고 했다.   
