># HTML, CSS, JavaScript에 대해 기술하시오.
- HTML   
웹 문서를 만들기 위하여 사용하는 기본적인 웹 언어의 한 종류이다.      
웹의 구조를 담당하는 정적 언어.   
마크업 언어.   
   
- CSS   
HTML구성 요소들의 표시 방법 개선에 사용되는 스타일 시트 언어.     
웹의 시각적인 표현을 담당.

   
- JavaScript   
웹페이지 구성요소들의 동작을 변경할 수 있는 도구를 제공.   
웹의 동적 처리를 담당.

------------------------------------------------------

># ECMAscript에 대해 기술하시오.
- ECMAScript는 ECMA-262에 의해 표준화된 자바스크립트의 새로운 이름이다.   
- ECMA스크립트는 웹의 클라이언트 사이드 스크립트로 사용되며 Node.js를 사용한 서버 응용 프로그램 및 서비스에도 사용된다. 

------------------------------------------------------

># typescript에 대해 기술하시오.
- 자바스크립트의 슈퍼셋인 오픈소스 프로그래밍 언어이며 자바스크립트의 모든 단점을 보완해 만든 언어이다.   
- 동적인 자바스크립트 언어에 타입을 미리 부여함으로써 컴파일 시 에러를 잡을 수 있다.

-----------------------------------------------------

># 자신을 소개하는 HTML태그 기술/ 태그마다 DOM객체 노드 형식으로
![ASDF](https://user-images.githubusercontent.com/80075223/208042276-0ee09600-bf15-4d3e-8ebb-6764de80e362.JPG)

-----------------------------------------------------

># Reflow와 Repaint
-Reflow : DOM 요소의 기하학적 속성이 변경될 떄, 브라우저 크기가 변할 때, 스타일 시트가 로딩 되었을 때 발생하는 변화들을 다시 계산 해주는 작업을 뜻한다.   
   
-Repaint : 변경된 요소를 실제로 화면에 그려주는 작업이고, Reflow가 발생하면 필연적으로 Repaint가 실행된다.

-----------------------------------------------------

># 자바스크립트에서 객체를 만드는 3가지 방법에 예와 함께 기술하시오.   
1.newObject() 생성자 사용
```
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

># 세션과 쿠키   
- 쿠키: 웹 서버가 브라우저에게 지시하여 사용자 로컬 컴퓨터에 저장하는 4k 이하의 작은 데이터이고, http의 무상태 프로토콜의 약점을 보완하기 위해 도입   
- 세션: 웹 사이트의 여러 페이지에 걸쳐 사용되는 사용자 정보를 저장하는 방법을 의미하며 사용자가 브라우저를 닫아 서버와의 연결을 끝내는 시점.

-----------------------------------------------------

># SPA MPA SCR CSR에 대해 기술하시오.
- SPA(Single Page Applicaton)는 서버로부터 새로운 페이지를 불러오지 않고 현재의 페이지를 동적으로 다시 작성함으로써 사용자와 소통하는 웹 애플리케이션이나 웹사이트이다.     
   
- MPA(Multi Page Application) 페이지가 요청될 때마다, 서버로부터 전체 페이지를 받아오고, 이후에 데이터의 수정이나 조회가 필요할 때 다른 페이지로 이동한다.   
   
- SSR은 서버에서 첫 페이지의 렌더링을 클라이언트 측이 아닌 서버 측에서 처리해준다.   
   
- CSR는 웹 페이지의 렌더링이 클라이언트(브라우저) 측에서 일어난다.   

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
