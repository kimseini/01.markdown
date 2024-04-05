# Markdown 으로 작성한 글입니다.
마크다운은 John Gruber 가 2024년 개발한 Markup Language 의 일종입니다.

## Markdown 특징
1. 문법이 쉽고 간결합니다.
2. 관리가 쉽습니다.
3. 별도의 도구없이 작성이 가능합니다.
4. 다양한 플랫폼에서 사용합니다.

---
# Markdown 기본문법

## 1. Heading(문단 제목)

# 문단 제목 1
## 문단 제목 2
### 문단 제목 3
#### 문단 제목 4
##### 문단 제목 5
##### 문단 제목 6
---

## 2. Paragraphs(문단)

문단입니다.
엔터 한번으로는 줄이 안 바뀝니다.

엔터 두번이 되어야 줄이 바뀌고, 다음 문단으로 인식합니다.

---

## 3. Line Breaks(줄바꿈)

새로운 문단이 아닌, 문단 내부에 엔터를 추가하고 싶다면  
공백 두개와 함께 엔터를 해주면 줄이 바뀝니다.

---

## 4. Emphasis(글강조)
굵은 글씨를 표현하고 싶다면 **별을 두개** 넣어주세요.

기울인 글씨는 *별 하나* 로 만들 수 있습니다.

굵으면서 기울은 글씨는 ***별이 세개*** 필요합니다.

---

## 5. Block Quotes(인용문)

인용문을 작성하고 싶으면 > 문을 문단의 시작에 넣어줍니다.  
아래는 인용문을 나타냅니다.
> A quotation is the repetition of a sentence, phrase, or passage from speech or text that someone has said or written.

---

## 6. Lists(목록)

순서를 가진 여러개의 항목을 가진 목록을 표현하고 싶을때, [1.] 부터 시작해서 하나씩 추가해가며 작성할 수 있습니다.  

아침에 할일
1. 일어나기
2. 세수하기
3. 컴퓨터 하기
4. 코딩하기

순서가 중요하지 않은 목록을 표현하고 싶으면 [-],[*],[+] 를 사용합니다. 어떤걸 사용하는지가 중요하지 않지만 가독성과 호환성을 위해 하나로 통일해줍니다.  
사용할 수 있는 언어
- Java
- Python
- JavaScript

아침에 할일
1. 일어나기
2. 세수하기
3. 컴퓨터 켜기
4. 코딩
   - 백준
   - 프로그래머스
  
---

## 7. 코드(Code)

마크다운에서 코드를 표현하고 싶다면 `print("Hello World")`라고 써봅시다. 

만약에 정말 만약에 백틱을 써야한다면 `` ` `` 처럼 해주면 됩니다.

여러줄의 코드를 표현할 떄는 8칸 이상의 공백 뒤에 작성하는게 기본 문법이지만, 많은 서비스에서 백틱 세개를 사용하는 확장 문법을 지원합니다.
```
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello Java!!!");
    }
}
```

사용하는 언어를 표기하여 해당 언어의 문법에 따라 글자색 변경 가능  
아래 코드는 Java 코드입니다.  

```java
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello Java!!!");
    }
}
```

---
## 8.  Horizontal Rules(가로줄)
가로로 그어지는 구분선을 넣어주고 싶다면, --- 을 사용해줍니다.  

아래는 가로줄로 표현합니다.

---

내용을 구분할 때 유용합니다.

---
## 9. Links(링크)
가장 간단한 링크 생성법 입니다. <https://www.naver.com>

[네이버](https://www.naver.com)라는 글귀에 네이버 링크를 달아보았습니다.

---

## 10. Images(이미지)
이미지를 넣고 싶다면, 느낌표(!)로 시작해, 대괄호([])로 이미지에 대한 설명, 이후 괄호로 이미지의 위치를 넣어줍니다.  

![컴퓨터 이미지)(computer.jpg)

웹 이미지도 넣어줄 수 있습니다.

![Java](https://upload.wikimedia.org/wikipedia/commons/thumb/7/79/Spring_Boot.svg/120px-Spring_Boot.svg.png)

