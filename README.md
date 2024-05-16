# Civil_Complaint

- Function: Summary, similar complaint search, and automatic generation of complaint answers
<img src="https://user-images.githubusercontent.com/101242683/233226262-ce5c476e-1d22-4929-addb-75e80b982e23.png" width="600" height="400"/>


- ## Data Collection
    - Collecting Complaints in Jung-gu, Incheon
  ![image](https://github.com/2hy03/Civil_Complaint/assets/101242683/35fd9977-d0e3-48fc-b0dd-9e613332ed34)
  - post요청방식으로 구현되어있기 때문에, selenium모듈을 활용하여 직접페이지 이동하도록 구현
    -  1차 민원목록리스트 크롤링, 2차 민원내용 크롤링
    - 테이블 join을 통해 MinwonDF구성


- ## Data Preprocessing
  - 삭제된 민원, 다부처병렬, 이송이첩 상태 민원삭제
  - 담당 부서별 민원 확인
      - 부서 재편으로 인한 이름 변경 추가 확인 및 변경 필요
      - 교통, 건축건설 관련 민원이 대부분
      - 국제도시건설국 교통과, 도시공원과 민원을 통해 임의 챗봇개발 진행



- ## Example>
<img src="https://github.com/2hy03/Civil_Complaint/assets/101242683/05363987-1066-4b3a-ba90-fc73fac0410a.png" width="700" height="400"/>

