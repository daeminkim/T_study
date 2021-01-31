## 1월 31
*깃허브 관련 마크다운 문법 공부 
# Header size
## Header size
### Header size
#### Header size(6가지)
___

(언더스코어 3개 추가시 밑줄 추가)

*안녕* (이탈릭체)

**반가워** (볼드체)

 ~~strikethrough~~(strikethrough)
> 줄바꾸기가 안되냐
# header
* 분류
- 분류
<!--numbered list-->
1. 숫자
2. 목록
3. 만들기

* 링크 추가

click[here](https://www.youtube.com/watch?v=kMEb_BzyUqk&t=322s)

* 이미지 링크

![image description](링크를 넣는다.)

*테이블

|Header|Desciption|
|--:|:--:|
|안녕|어서와|
|안녕|어서와|
|안녕|어서와|
|안녕|어서와|

김대민 천재 `문서안에서 코딩을 보여주거나 할 때 가독성을 높일 수 있다.`
```python
이렇게 블럭을 만들어 코드를 집어 넣을 수도 있고 언어형식을 넣어 준다면 색깔까지 표현된다.
def rotation(key): # key: list
    total = []
    for i in range(len(key)):
        result = []
        for j in range(len(key)-1,-1,-1): # 90도 회전이기에 역순으로
            result.append(key[j][i])
        total.append(result)
    return total

```
You Tube 드림코딩 by 엘리 에서 공부함 
이미지 추가 관련 내용이 더 있고 필요할 때 찾아 보기
click here 에 링크 걸어 둠
```
