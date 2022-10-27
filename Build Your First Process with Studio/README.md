# Build Your Frist Process with Studio


1. 이 워크플로우는 모든 읽지 않은 메일 중 제목에 'Course Invoices'가 들어간 메일을 불러온다.
2. 메일들은 mailmessage list 타입 변수에 저장된다.
3. 각 메일의 첨부파일들은 'Invoices' 폴더에 저장된다.
4. 각 첨부파일들의 고객 코드 값을 복사해서 변수 ClientCode에 저장한다.
5. https://acme-test.uipath.com/first-automation에 접속한 후 Part2를 클릭하고 고객 코드를 입력한 뒤 할인값을 추출한다.
6. 할인값을 변수 DiscountValue에 저장한다. (모든 고객마다 반복)
7. 할인값이 "$"를 포함하면 인보이스 파일의 "E18"셀에 입력하고 아니면 "$0"을 입력한다.
8. 시그니처를 인보이스 파일의 맨 밑에 추가한다.
9. 업데이트된 인보이스 파일을 첨부한 초안 메일을 작성한다.

---
![Untitled1](https://user-images.githubusercontent.com/114542921/198343897-c4007cfd-c442-4f41-bca3-a8bd863a5414.png)
![Untitled](https://user-images.githubusercontent.com/114542921/198343954-dd7f378e-1349-4baa-8265-58e80b3b5407.png)
