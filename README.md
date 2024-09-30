# BookTracker



### 📖 프로젝트 설명
**BookTracker**는 사용자가 자신의 독서 목록을 관리할 수 있는 책 관리 시스템입니다. 사용자는 읽고 싶은 책, 읽고 있는 책, 그리고 이미 읽은 책을 구분하여 관리할 수 있으며, 해당 데이터를 효율적으로 저장하고 불러오는 RESTful API 기반의 애플리케이션입니다.



### 🔧 사용 스택
- **Backend**: Spring Boot, JPA, MySQL
- **Tools**: Lombok, JUnit, Git



### 📝 주요 기능
- 책 정보 추가, 조회, 수정, 삭제 기능 (CRUD)
- 책의 상태(읽고 싶은 책, 읽고 있는 책, 이미 읽은 책) 관리
- RESTful API를 통해 데이터 관리
- JPA를 통한 데이터베이스 연동
- JUnit을 사용한 단위 테스트 작성



### 💼 상세 업무 및 성과
- **RESTful API 설계 및 구현**: 사용자와 책 데이터를 효율적으로 관리할 수 있도록 API 설계
- **데이터베이스 연동**: JPA를 통해 MySQL 데이터베이스와 엔티티를 매핑하여 CRUD 작업을 처리
- **유효성 검사 및 예외 처리**: API 요청에 대한 유효성 검사 및 예외 처리 구현
- **테스트 코드 작성**: JUnit을 사용한 테스트 코드 작성으로 안정성과 코드 품질 보장
- **버전 관리**: Git을 통한 체계적인 버전 관리



### 🛠 설치 및 실행 방법

1. **레포지토리 클론**:
   ```bash
   git clone https://github.com/beomjookim/booktracker.git
   ```

2. **프로젝트 디렉토리로 이동**
   ```bash
   cd booktracker
   ```
   
3. **프로젝트 빌드**
   ```bash
   ./gradlew build
   ```

4. **앱 실행**
   ```bash
   ./gradlew bootRun
   ```

5. **API 엔드포인트**

* GET /api/books: 모든 책 조회
* POST /api/books: 책 추가
* PUT /api/books/{id}: 책 정보 수정
* DELETE /api/books/{id}: 책 삭제
