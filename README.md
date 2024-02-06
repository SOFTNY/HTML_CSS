# [🔗BEM](https://en.bem.info)
Block__Element--Modifier <br/>
- 목적과 기능을 명확히 전달할 수 있다.
- 요소의 구조를 효율적으로 전달한다.
- CSS명시도를 항상 낮은 수준으로 유지하기 때문에 구체성으로 인한 코드의 길어짐을 방지할 수 있다.
<br/>
출처 : https://velog.io/@kjwboa/CSS-CSS-%EB%B0%A9%EB%B2%95%EB%A1%A0-BEM-%EB%B0%A9%EC%8B%9D

<br/>
<br/>
<br/>

# [🔗anti-aliasing](https://developer.mozilla.org/en-US/docs/Web/CSS/font-smooth)
폰트가 더욱 부드럽게 보일 수 있지만, 선명함은 떨어질 수 있다.
```css
-webkit-font-smoothing: antialiased;
-moz-osx-font-smoothing: grayscale;

/* 미지원 브라우저 안티앨리어싱 */
transform: rotate(0.03deg);
```
출처 : https://creativestudio.kr/1398

<br/>
<br/>
<br/>

# [🔗Breakpoint](https://developer.mozilla.org/en-US/docs/Web/CSS/font-smooth)
반응형웹에서 레이아웃을 구성할 때 기기별 뷰포트의 크기를 어떻게 결정할 지를 정의하는 것을 의미

<br/>

[🔗Bootstrap Breakpoint](https://getbootstrap.com/docs/5.0/layout/breakpoints/)

|Breakpoint|Class infix|Dimensions|
|------|---|---|
|X-Small|None|<576px|
|Small|sm|≥576px|
|Medium|md|≥768px|
|Large|lg|≥992px|
|Extra large|xl|≥1200px|
|Extra extra large|xxl|≥1400px|

<br/>

[🔗Tailwindcss Breakpoint : Responsive Design](https://tailwindcss.com/docs/responsive-design)
|Breakpoint prefix|Minimun width|CSS|
|------|---|---|
|`sm`|640px|`@media (min-width: 640px) { ... }`|
|`md`|768px|`@media (min-width: 768px) { ... }`|
|`lg`|1024px|`@media (min-width: 1024px) { ... }`|
|`xl`|1280px|`@media (min-width: 1280px) { ... }`|
|`2xl`|1536px|`@media (min-width: 1536px) { ... }`|

<br/>
<br/>

# [🔗Pseudo-element](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes)
CSS에서, 가상 클래스 선택자는 문서 트리의 정보가 아닌 상태에 따라 요소를 대상으로 한다.
<br/>

출처 : https://developer.mozilla.org/ko/docs/Glossary/Pseudo-class

