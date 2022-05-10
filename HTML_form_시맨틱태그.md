# form

* __form__ :

  * form태그는 html에서 사용자가 입력할 수 있는 양식을 제공하는 태그.
  * form태그 내의 input태그들을 통해 사용자가 입력한 정보를 서버로 넘기는 역할을 한다.
  * `action:` 입력받은 데이터를 보낼 곳을 입력.
  * `method:` get/post 등의 전송방식을 지정.

* ```html
  <form>
          <fieldset method = "post"> <!-- method가 없을지 디폴트로 get방식 적용 -->
              <legend>필드셋의 제목을 작성하는 부분</legend>
              <label>입력!: </label><input type="text"><br>
              <label>입력!: </label><input type="text"><br>
              <label>입력!: </label><input type="text"><br>
          </fieldset>
          <fieldset>
              <legend>태그추가</legend>
              <label>입력!: </label><input type="text"><br>
              <label>입력!: </label><input type="text"><br>
              <label>입력!: </label><input type="text"><br>
          </fieldset>
      </form>
  ```

---

* __text와 관련된 input태그__

```html
 <form method="post">
        <h2>text와 관련된 input태그</h2>
        <label>아이디: </label> <input type="text" name="userid" size="20" placeholder="아이디를 입력하세요." maxlength="10" value="multi" autofocus>
        <br>
        <label>비밀번호: </label> <input type="password" name="userpw" size="20" placeholder="비밀번호를 입력하세요." maxlength="15" >
        <br>
        <label>홈페이지: </label> <input type="url" name="homepage" value="https://">
        <br>
        <label>이메일: </label> <input type="email">
        <br>
        <label>전화번호: </label><input type="phone" placeholder="전화번호를 입력하세요">
        <br><br>
        <input type="submit" value="전송">&nbsp;<input type="reset" value="취소">
    </form>
```



* __숫자와 관련된 input태그__

```html
<form method="get">
        <h2>숫자와 관련된 input태그</h2>
        수량: <input type="number" name="amount" min="10" max="100" value="10" step="5">
        <br>
        점수: <input type="range" name="point" min="0" max="100" value="50" step="10">   
        <br><br>
        <input type="submit" value="전송">
    </form>
```



* __라디오버튼과 체크박스__

```html
 <form>
        <h2>라디오버튼과 체크박스</h2>
        성별: <input type="radio" name="gender" value="F" id="female"><label for="female">여자</label>&nbsp;&nbsp;
              <input type="radio" name="gender" value="M" id="male" checked><label for="male">남자</label>
        <br>
        취미: <input type="checkbox" id="baseball" name="hobby" value="baseball" checked><label for="baseball">야구</label>&nbsp;&nbsp;
              <input type="checkbox" id="football" name="hobby" value="football" checked><label for="football">축구</label>&nbsp;&nbsp;
              <input type="checkbox" id="basketball" name="hobby" value="basketball"><label for="basketball">농구</label>

        <br><br>
        <input type="submit" value="전송">
    </form>
```



* __날짜와 관련되 input 태그__

```html
 <form>
        <h2>날짜와 관련되 input 태그</h2>
        date: <input type="date" value="2022-09-11" min="2020-01-01" max="2030-12-31"><br>
        month: <input type="month"><br>
        week: <input type="week"><br>
        time: <input type="time"><br>
        datetime-local: <input type="datetime-local"><br>
        <br><br>
        <input type="submit" value="전송">
    </form>
```



* __그 밖에 input태그__

```html
 <form>
        <h2>그 밖에 input태그</h2>
        색상선택: <input type="color" name="color"><br>
        파일선택: <input type="file"><br>
        안보임: <input type="hidden" name="hiddenVal" value="1"><br>
        버튼: <input type="button" value="버튼" onclick="window.alert('하하');">
        <br><br>
        <input type="submit" value="submit">
    </form>
```

---

* __select태그와 option태그__

```html
 <form>
        <h2>select태그와 option태그</h2>
        국적: 
        <select>
            <option value="ko">한국</option>
            <option value="us">미국</option>
            <option>영국</option>
            <option>기타</option>
        </select>
        <br><br>
        국적:
        <select size="2" name="con">
            <option value="ko">한국</option>
            <option value="us">미국</option>
            <option>영국</option>
            <option>기타</option>
      </select>
        <br><br>
        <input type="submit" value="전송">
    </form>
```

