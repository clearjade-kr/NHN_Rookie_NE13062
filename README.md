# NHN_Rookie_NE13062

프로젝트 기본 구조

Thymeleaf Page : layout template 을 활용해서 처리

--> Controller 계층 - GuestbookController Class : 브라우저에서 들어오는 Request 처리

--> Service 계층 - GuestbookService Interface : GuestbookController 에게 주입, 이를 통해서 작업 처리
		GuestbookServiceImpl Class

--> Repository 계층 - GuestbookRepository : Spring Data JPA를 통해 구현, 
		GuestbookServiceImpl 클래스에 주입하여 사용





Testing Fork