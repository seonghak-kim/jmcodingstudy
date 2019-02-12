
# 코드카데미 HTML 학습 노트

## HTML 뜻

* Hyper Text Markup Language
  * Hyper Text: 이동할 수 있는 텍스트
  * **Markup** : raw text의 구조와 재현을 정의하는 특징

## HTML을 사용하는 이유

* HTML 태그를 사용하여 raw text에 기능을 부여한다.


## Element
* opening tag + content + closing tag
* `<p>seonghak kim</p>`

## 구조
* HTML은 계층적 구조를 가지고 있다.
* Space 두 칸

## Heading
* 제목 넣는 것. 내가 잘 못 쓰고 있었음
* 6개 존재

## Div
* Html은 상자로 구성되어있다고 생각
* 그래야 나중에 CSS(styling 편함)

## Attribute
* name 과 value 존재
* id="~"
* `<div id="introduction"></div>`

---

## Displaying Text

* `<p>` - paragraph </p>
* `<span>` - 따로 떼 두는 것. 문장안에서(cf, div)

## Styling Text

* `<em></em>` - 강조, <em>이탤릭 서체</em>
* `<strong></strong>` - 굵게, <strong>bold</strong>

## Line Breaks

* `<br>` - 한줄 띄기, `closing tag 없음!!`


## Unordered List

* `<ul></ul>` - 땡땡이로 나열할때
리스트 앞뒤로 `<li></li>` 표기

```html
<ul>
  <li>이렇게</li>
  <li>요렇게</li>
</ul>
```

## Ordered Lists

* `<ol></ol>` - 숫자로 순서 나열할때
리스트 앞뒤로 `<li></li>`표기

```HTML
<ol>
  <li>이렇게</li>
  <li>요렇게</li>
</ol>
```

## Images

* `<img src="image-location.jpg" />`
* img는 클로징태그 없이 끝에 한칸 띄고 슬래쉬하고 닫기
* src="URL(Uniform resource locator)"

## Alt

* Alt = alternative text(이미지를 대처하는 용도, 손상된이미지나 마우스오버시)

`<img src="~" alt="설명" />`

---



---
