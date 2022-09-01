# 📋googleform

## 📍 구글폼 연습페이지
구글폼 클론 코딩
<br>
<br>
🔗 url : https://seohee3478.github.io/googleform/003_googleform.html

- 기본 화면 상단
<img width="1419" alt="스크린샷 2022-08-31 오후 10 23 24" src="https://user-images.githubusercontent.com/78894678/187688711-df6a32ea-e433-461c-a358-efd67adf2b0e.png">

- 기본 화면 하단
<img width="1419" alt="스크린샷 2022-08-31 오후 10 23 48" src="https://user-images.githubusercontent.com/78894678/187688787-afb48167-a287-416e-9bf0-3c510c1562fe.png">

## 📍 기능 설명

1. input 의 `radio` type 사용하여 단일선택 할 수 있도록 설정
2. input 의 `checkbox` type 사용하여 중복선택 할 수 있도록 설정
3. input 의 `text` type 사용하여 짧게 주관식으로 입력받을 수 있도록 함
4. `textarea` 태그 사용하여 긴 주관식 입력받을 수 있도록 함
5. `datalist` 태그와 `option` 태그를 이용하여 답안을 선택지 중에서도 선택할 수 있도록 함
6. input 의 `time` type을 사용하여 날짜를 선택할 수 있도록 함
7. input 의 `date` type을 사용하여 시간을 선택할 수 있도록 함

## 📍 배운점
### 1. `label` 태그
  - 사용하는 이유
  1. `label` 태그는 `input` 태그를 설명할 때 사용
  2. for 속성을 연결하면 label 태그를 클릭했을 때 input 태그에 자동으로 포커스가 간다(체크박스와 라디오 버튼은 레이블을 클릭했을 때 해당 항목이 클릭 됨)
  2. 웹 접근성을 위해서 사용

  - 사용하는 방법
    1. 명시적 작성 방법(label의 for 속성과 input의 id 속성을 명시함으로써 연결해주는 방식)
      ```html
      <label for = "name">이름</label>
      <input type="text" id="name">
      ```
      `label` 태그의 for 속성에 `input` 태그의 id 속성을 입력해서 `label` 태그가 어떤 `input` 태그를 나타내는지 알려줌
      <br>
    2. 암시적 작성 방식(label 태그 안에 input 태그를 넣음으로 암묵적으로 연결)
    ```html
    <label>
      이름<input type="text" id ="name">
    </label>
    
###2. input 태그
- input 태그는 사용자로부터 정보를 입력받을 수 있게 해주는 태그
- type 속성에 따라 다양한 입력 양식을 사용할 수 있음
```html
<input type="유형" 속성="속성값">
```
- type : 입력 태그의 유형을 설정하는 속성입니다.
- name : 서버로 전달되는 이름을 설정하는 속성입니다.
- value : 입력 태그의 초기 값을 설정하는 속성입니다.

type 속성 종류

1. text : 기본 텍스트를 입력하는 창을 생성해줍니다.

2. password : 비밀번호를 입력하는 창을 생성해줍니다.

3. button : 기본 버튼을 생성해줍니다.

4. radio : 라디오 버튼을 생성해줍니다.

5. checkbox : 체크박스를 생성해줍니다.

6. file : 파일 첨부 버튼을 생성해줍니다.

7. hidden : 사용자에게 입력받지 않고 기본으로 설정된 값을 서버로 전송합니다.

8. submit : 서버로 제출하는 버튼을 생성해줍니다.

9. reset : form에서 입력한 input 값들을 reset 시킵니다.

10. url : url 입력을 위한 필드를 정의합니다.

11. search : 검색 문자열 입력을 위한 텍스트 필드를 정의합니다.

12. tel : 전화번호 입력을 위한 필드를 정의합니다. (모바일 브라우저에서 키보드 배열이 변경 됨)

13. email : 메일 주소 입력을 위한 필드를 정의합니다.(모바일 브라우저에서 키보드 배열이 변경 됨)

14. time : 시간 지정을 지정하는 요소입니다. (시간은 00:00부터 23:59까지 입력하거나 스핀 박스의 화살표를 클릭해서 선택함) * 아직 모든 브라우저를 지원하지는 않습니다.

            1) min - 날짜나 시간의 최솟값을 지정합니다.

            2) max - 날짜 시간의 최댓값을 지정합니다.

            3) step - 스핀 박스의 화살표를 누를 때마다 날짜나 시간의 증가값을 지정합니다.

            4) value - 화면에 표시할 초기값을 지정합니다.

 
