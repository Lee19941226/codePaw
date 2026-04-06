# 🐾 CodePaw - 유기동물 보호소 플랫폼

> Semi Project | 2025.07 - 2025.08 | 팀 4명

유기동물 보호소 기반 분양 신청 및 후기 공유 플랫폼입니다.

## 🛠 기술 스택
- **Backend**: Java 17, Spring Boot 3.5, MyBatis
- **Frontend**: HTML5/CSS3, jQuery, Thymeleaf
- **Database**: Oracle 11g XE
- **Tools**: Eclipse, GitHub Desktop

## 👤 담당 기능 (이용재)
- **회원 인증 시스템**: Spring Security 없이 세션 기반 인증 구현, BCrypt 암호화 적용
- **이메일 인증**: JavaMailSender + 3분 타이머 검증, 재전송 시 이전 번호 무효화
- **아이디/비밀번호 찾기**: 이름·전화번호 다중 조건 쿼리 + 이메일 2단계 인증
- **관리자 페이지**: 동물 입소 등록·상태 관리, 입양 승인·거절, 회원 등급 변경
- **개인정보 수정**: 닉네임·이메일·비밀번호 별도 쿼리 분리, Ajax 중복 체크

## 📐 아키텍처
Client (HTML/jQuery) → Thymeleaf SSR → Spring Boot (Controller → Service → DAO) → MyBatis → Oracle DB

## 🔗 Links
- [포트폴리오](https://leeyongjae-portfolio.vercel.app)
