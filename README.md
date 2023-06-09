# 순수 타입스크립트 TO-DO-LIST

## 프로젝트 목표
순수 타입스크립트를 이용하여 간단한 CRUD 기능이 있는 투두리스트 앱 구현

## 프로젝트 사용 기술
TypeScript, HTML, CSS


## 프로젝트 기능
### 할 일 추가
* 상단의 Input에 텍스트를 적고 Enter키 혹은 오른쪽의 추가 버튼을 누르면 할 일이 목록에 저장되고 할 일 목록에 노출됩니다.
* 글자 수가 1자 이상 20자 이하 이하일 때만 등록이 가능합니다.(이상, 이하일 경우 알럿 노출)
* 각 할 일 색상을 설정할 수 있습니다. 설정하지 않을 경우, 랜덤 색상으로 지정됩니다.

### 할 일 완료(체크 기능)
* 할 일의 체크박스를 클릭하면 체크가 되고 완료된 할 일 목록으로 이동합니다.
* 완료된 할 일의 체크 표시를 헤제하면 할 일 목록으로 이동합니다.

### 할 일 수정
* 오른쪽에 있는 수정버튼을 클릭하면 해당 할 일의 수정이 가능한 폼으로 변경됩니다.
* Input의 텍스트, 색상을 수정 저장 버튼을 클릭하면 할 일의 텍스트와 색상이 수정됩니다.
* 수정한 할 일은 수정된 날짜가 표시됩니다.

### 할 일 삭제
* 상단의 전체 삭제 버튼을 클릭하면 할 일의 전체 목록이 삭제되고 삭제 목록에 저장됩니다.
* 상단의 완료된 할 일 삭제 버튼을 클릭하면 완료된 할 일의 목록이 삭제되고 삭제 목록에 저장됩니다.
* 각 할 일의 삭제 버튼을 클릭하면 목록에서 삭제되고 삭제 목록에 저장됩니다.
* 위 3가지 방법으로 삭제된 항목들은 삭제된 할 일에 노출됩니다.

## 빌드

```bash
yarn build
```

## 실행

```bash
yarn 
yarn start
```

📌 자동으로 브라우저가 켜지지는 않으니 브라우저에 `http://localhost:3000`을 입력하여 접속해 주세요.
