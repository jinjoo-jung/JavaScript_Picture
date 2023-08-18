# 빠리지앵 직원 관리 페이지

- 배포링크 : http://js-employee-bucket.s3-website.ap-northeast-2.amazonaws.com/favicon.ico
- 프로젝트 기간 : 230808~230818

## [필수 요구사항]

- [x] “AWS S3 / Firebase 같은 서비스”를 이용하여 사진을 관리할 수 있는 페이지를 구현하세요.
- [x] 프로필 페이지를 개발하세요.
- [x] 스크롤이 가능한 형태의 리스팅 페이지를 개발하세요.
- [x] 전체 페이지 데스크탑-모바일 반응형 페이지를 개발하세요.
- [x] 사진을 등록, 수정, 삭제가 가능해야 합니다.
- [x] 유저 플로우를 제작하여 리드미에 추가하세요.
- [x] CSS 애니메이션 구현
- [x] 상대수치 사용(rem, em)
- [x] DOM event 조작

## [선택 요구사항]

- [x] 사진 관리 페이지와 관련된 기타 기능도 고려해 보세요.
- [x] 페이지가 보여지기 전에 로딩 애니메이션이 보이도록 만들어보세요.
- [x] 직원을 등록, 수정, 삭제가 가능하게 해보세요.
- [x] 직원 검색 기능을 추가해 보세요.
- [ ] infinity scroll 기능을 추가해 보세요.
- [ ] 사진을 편집할 수 있는 기능을 추가해 보세요.
- [ ] LocalStorage 사용

## 구현 이미지

### 작성해야 하는 요소들을 모두 작성해야 직원 등록이 가능

<img width="1175" alt="스크린샷 2023-08-18 오후 10 07 00" src="https://github.com/KDT1-FE/Y_FE_JAVASCRIPT_PICTURE/assets/85981963/0f15a98f-214b-4b9d-9b76-ab0e3aa32716">

### 직원 상세 페이지

<img width="434" alt="스크린샷 2023-08-18 오후 7 27 17" src="https://github.com/KDT1-FE/Y_FE_JAVASCRIPT_PICTURE/assets/85981963/4f03194b-2273-4280-a58d-1564750fb441">

### 애니메이션 사용

- 로고 움직임
- 상세 페이지 넘어갈 때 1초간 로딩 애니메이션 작동
- 상세페이지에 직원 이미지 움직이는 애니메이션 작동

https://github.com/KDT1-FE/Y_FE_JAVASCRIPT_PICTURE/assets/85981963/fc859cf5-57c2-4057-8a3c-98b9254be648

### 검색기능 구현

https://github.com/KDT1-FE/Y_FE_JAVASCRIPT_PICTURE/assets/85981963/69fbd961-074a-4055-9412-84e11cc33794

### 직원 정보 수정 , 삭제 (AWS S3에도 수정 삭제됨)

https://github.com/KDT1-FE/Y_FE_JAVASCRIPT_PICTURE/assets/85981963/8ddca87d-cf8a-41c8-aa5b-66c2362def96

### 반응형

<img width="409" alt="스크린샷 2023-08-18 오후 10 39 38" src="https://github.com/KDT1-FE/Y_FE_JAVASCRIPT_PICTURE/assets/85981963/8e8b2670-33bb-4772-9a2b-acf40eddaeea">

## USER FLOW

<img width="845" alt="스크린샷 2023-08-18 오전 1 01 02" src="https://github.com/KDT1-FE/Y_FE_JAVASCRIPT_PICTURE/assets/85981963/2ac5492c-a455-46de-be97-5db917adf41a">

#### 아쉬웠던 점

- async, await의 이해가 완벽했다면 코드를 짤 때 수월했을 것 같다
- 배포가 404에러로 잘 작동하지 않아 시간을 많이 소모하였고 결국 호스팅으로 배포했다
- LocalStorage를 이용하기 위해서 데이터를 넣고 저장하는 것까지 하였으나, 함수를 사용하는데에 있어서 코드에 계속 에러가 생겨서 저장해놓은 데이터를 화면에 띄우는 것 까지는 못 한점이 가장 아쉽다.
- 반응형 구현에 부족하여 더 세밀하게 구현하지 못한 점

#### 배운 점

- name이라는 변수명은 프로그래밍 언어나 프레임워크에서 특별한 의미를 가지는 키워드일 수 있기 때문에 변수명으로 사용하면 의도하지 않은 동작이 발생할 수도 있다는 점을 알게 되었다.
- 하나의 함수 안에 여러 기능을 넣는 것보다 함수를 여러 개 만들어 필요할 때 호출하는 것이 좋고 코드의 가독성도 좋아진다는 것을 알게 되었다.

### Develop

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=Javascript&logoColor=white)![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?style=for-the-badge&logo=Visual%20Studio%20Code&logoColor=white)![Github](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white)
