Github README.md 기본 문법
===

● 일반 Text 입력하기
---
일반 문구는 그냥 작성합니다
```
일반 문구는 그냥 작성합니다
```

● 큰 제목 넣기
---
큰 제목 넣기 > 아래에 === 를 작성합니다
===
```
큰 제목 넣기 > 아래에 === 를 작성합니다
===
```

● 작은 제목 넣기
---
작은 제목 넣기 > 아래에 --- 를 작성합니다
---
```
작은 제목 넣기 > 아래에 --- 를 작성합니다
---
```

● HTML h1 ~ h6 태그와 비슷하게 표현하는 방법 (1)
---

# # 한개가 앞에있으면 이렇게 됩니다
## # 두개로 앞에있으면 이렇게 됩니다
### # 세개로 앞에있으면 이렇게 됩니다
#### # 네개로 앞에있으면 이렇게 됩니다
##### # 다섯개로 앞에있으면 이렇게 됩니다
###### # 여섯개로 앞에있으면 이렇게 됩니다
```
# # 한개가 앞에있으면 이렇게 됩니다
## # 두개로 앞에있으면 이렇게 됩니다
### # 세개로 앞에있으면 이렇게 됩니다
#### # 네개로 앞에있으면 이렇게 됩니다
##### # 다섯개로 앞에있으면 이렇게 됩니다
###### # 여섯개로 앞에있으면 이렇게 됩니다
```

● HTML h1 ~ h6 태그와 비슷하게 표현하는 방법 (2)
---
# # 한개로 감싸주면 이렇게 됩니다 #
## # 두개로 감싸주면 이렇게 됩니다 ##
### # 세개로 감싸주면 이렇게 됩니다 ###
#### # 네개로 감싸주면 이렇게 됩니다 ####
##### # 다섯개로 감싸주면 이렇게 됩니다 #####
###### # 여섯개로 감싸주면 이렇게 됩니다 ######
```
# # 한개로 감싸주면 이렇게 됩니다 #
## # 두개로 감싸주면 이렇게 됩니다 ##
### # 세개로 감싸주면 이렇게 됩니다 ###
#### # 네개로 감싸주면 이렇게 됩니다 ####
##### # 다섯개로 감싸주면 이렇게 됩니다 #####
###### # 여섯개로 감싸주면 이렇게 됩니다 ######
```

● 글자 기울이기
---
*기울여쓰기(Italic)*<br>
_기울여쓰기(Italic)_
```
*기울여쓰기(Italic)* 또는
_기울여쓰기(Italic)_
```

● 글자 굵게하기
---
**굵게쓰기(Bold)**<br>
__굵게쓰기(Bold)__
```
**굵게쓰기(Bold)** 또는
__굵게쓰기(Bold)__
```

● 글자 기울임 + 굵게하기
---
***기울여서 굵게***<br>
___기울여서 굵게___
```
***기울여서 굵게*** 또는
___기울여서 굵게___    
```

● 리스트 작성하기
---
기본리스트

- You can use a minus sign for a bullet
+ Or plus sign
* Or an asterisk
```
기본리스트

- You can use a minus sign for a bullet
+ Or plus sign
* Or an asterisk
```

기본리스트

* 리스트1-1
* 리스트1-2
* 리스트1-3
```
기본리스트

* 리스트1-1
* 리스트1-2
* 리스트1-3
```

● 숫자와 리스트의 조합
---
1. 숫자 리스트 아래
    - 인덴트용 공백 4개를 넣었더니 또다시 리스트가
        * 공백이 8개면 한단계 더 아래!
    - 공백을 4개 넣으면 한단계 위로!
```
1. 숫자 리스트 아래
    - 인덴트용 공백 4개를 넣었더니 또다시 리스트가
        * 공백이 8개면 한단계 더 아래!
    - 공백을 4개 넣으면 한단계 위로!
```



● 한줄 음영 넣기
---
`[주의] 이 작업을 수행할때는 root user 권한이 필요합니다. sudo를 이용하세요`
```
`[주의] 이 작업을 수행할때는 root user 권한이 필요합니다. sudo를 이용하세요`
```

● 여러줄에 음영을 넣거나 회색 배경 박스를 만들기
---
```
padding이 적용되어서 내용물을 보기에 좋다

마음에 든다
```

```
	```
	padding이 적용되어서 내용물을 보기에 좋다

	마음에 든다
	```
```

● 배경박스속에 코드 넣기 (1)
---
	#include <stdio.h>

	int main() 
	{ 
	    printf("hello, world"); 
    	return 0; 
	}


```
	#include <stdio.h>

	int main() 
	{ 
	    printf("hello, world"); 
    	return 0; 
	}

	// ``` 표시 없이 코드 앞에 tab을 한번 넣어주거나 space 4개를 작성!

```

● 배경박스속에 코드 넣기 (2)
---
```javascript
function test() {
	console.log("Hello world!");
}
```

```
	```javascript
	function test() {
		console.log("Hello world!");
	}
	```
```

● 체크 리스트 만들기
---
- [x] 완료된 항목
- [ ] 완료하지 못한 항목
- [ ] 완료하지 못한 항목2
- [x] 이슈번호 7번 **빨리** 처리하기

● 표 만들기
---
First Header 	| Second Header
--------------	| --------------
Content cell 1	| Content cell 2
Content column 1| Content column 2

```
First Header 	| Second Header
--------------	| --------------
Content cell 1	| Content cell 2
Content column 1| Content column 2
```

● 인용박스 만들기
---
> The syntax is based on the way email programs
> usually do quotations. You don't need to hard-wrap
> the paragraphs in your blockquotes, but it looks much nicer if you do.

```
> The syntax is based on the way email programs
> usually do quotations. You don't need to hard-wrap
> the paragraphs in your blockquotes, but it looks much nicer if you do.
```

● 인용의 인용박스 만들기
---
> A: "어제 중국집 가서 짜장면 시켜 먹었는데 정말 맛있더군요." (평범한 문제 제기) 
> > B: "짜장면이 뭐가 맛있어요? 우동이 훨 맛있지" (평범한 반론) 
> > > C: "우동이요? 에이, 우동보다는 짜장면이죠. 돼지고기도 들어가고." (재반론, A의 의견에 합류) 
> > > > D: "짜장면에 돼지고기라면 우동에는 해물이죠. 맛을 안다면 역시 우동!" (재재반론, B의 의견에 합류. ~~을 안다면.. 이라는 말 나왔음) 
> > > > > A: "님, 그럼 우동 안 먹는 사람은 맛을 모른단 말인가요?" (말꼬리 잡기 시작) 
> > > > > > B: "그만큼 우동이 낫다는 거죠. 에이, 짜장은 느끼해서.." (상대가 좋아하는 것을 깎아내림) 
> > > > > > > C: "님께서 짜장면에 대해서 잘 모르시는군요. 제가 설명해 드리죠. (잘 모르시는군요.. 나왔음. 지식과 데이터, 증거, 등등 늘어놓기 시작) 

```
> A: "어제 중국집 가서 짜장면 시켜 먹었는데 정말 맛있더군요." (평범한 문제 제기) 
> > B: "짜장면이 뭐가 맛있어요? 우동이 훨 맛있지" (평범한 반론) 
> > > C: "우동이요? 에이, 우동보다는 짜장면이죠. 돼지고기도 들어가고." (재반론, A의 의견에 합류) 
> > > > D: "짜장면에 돼지고기라면 우동에는 해물이죠. 맛을 안다면 역시 우동!" (재재반론, B의 의견에 합류. ~~을 안다면.. 이라는 말 나왔음) 
> > > > > A: "님, 그럼 우동 안 먹는 사람은 맛을 모른단 말인가요?" (말꼬리 잡기 시작) 
> > > > > > B: "그만큼 우동이 낫다는 거죠. 에이, 짜장은 느끼해서.." (상대가 좋아하는 것을 깎아내림) 
> > > > > > > C: "님께서 짜장면에 대해서 잘 모르시는군요. 제가 설명해 드리죠. (잘 모르시는군요.. 나왔음. 지식과 데이터, 증거, 등등 늘어놓기 시작) 
```

● 선이 긋고 싶을 때
---

---
```
---
```

***
```
***
```

___
```
___
```

( - / * / _ 중 한개가 연속 3번 등장하면 선으로 변환됨 )


● 링크걸기 (1)
---
* 인라인 링크 [Google](http://www.google.com/)
* 참조 링크 [Google] [1]
* 읽기 편한 링크 [Yahoo!]

[1]: http://www.google.com/
[yahoo!]: http://www.yahoo.com/

```
* 인라인 링크 [Google](http://www.google.com/)
* 참조 링크 [Google] [1]
* 읽기 편한 링크 [Yahoo!]

[1]: http://www.google.com/
[yahoo!]: http://www.yahoo.com/
```

● 링크걸기 (2)
---
<http://naver.com>
```
<http://naver.com>
```

● 링크걸기 (3)
---
http://naver.com

```  
http://naver.com
```

● 이메일 링크걸기
---
<me@privacy.net>

```
<me@privacy.net>
```

이메일 주소는 <me@privacy.net> 와 같은 형식을 이용하여 작성할 경우<br>
복합한 형태의 HTML 코드로 변환해주어 스팸 로봇의 이메일 수집을 어렵게 만들어줌

● 그림넣기
---
![Valid XHTML](http://w3.org/Icons/valid-xhtml10)

```
![Valid XHTML](http://w3.org/Icons/valid-xhtml10)

[ ] 속에는 이미지에 대한 설명을 작성합니다
img Element의 alt property에 해당합니다
```

● 키보드의 키값을 표시하고 싶어요
---
<kbd>Ctrl</kbd>+<kbd>C</kbd> : 복사
<kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>V</kbd> : 미지원

```
<kbd>Ctrl</kbd>+<kbd>C</kbd> : 복사
<kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>V</kbd> : 미지원

kbd태그 속에 원하는 값을 입력하면 된다
```

● 이모티콘 넣기
---
GitHub supports emoji!
:+1: :camel: :tada: :rocket: :octocat:

```
GitHub supports emoji!
:+1: :camel: :tada: :rocket: :octocat:
```
지원하는 emoji 목록은 <http://emoji-cheat-sheet.com>에서 확인!