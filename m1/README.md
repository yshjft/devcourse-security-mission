# mission1 & mission2

## mission 1

- [X] configure(AuthenticationManagerBuilder auth) 메소드 override
    -[X] passwordEncoder는 NoOpPasswordEncoder로 사용함 
    -[X] 기본 로그인 계정을 AuthenticationManagerBuilder 클래스를 통해 추가
- [ ] 로그아웃, Cookie 기반 자동 로그인 (Remember-Me) 기능 설정하기
    - [X] HttpSecurity 클래스의 logout() API를 통해 로그아웃 기능을 설정
        - 로그아웃 처리 path “/logout”
        - 로그아웃 성공 후 리다이렉션 path “/”  
    - [ ] HttpSecurity 클래스의 rememberMe() API를 통해 Cookie 기반 자동 로그인 기능을 설정
        - 파라미터명 “remember-me”
        - 자동 로그인 토큰 유효기간 5분

## mission 2
- [ ] AnonymousAuthenticationFilter, ExceptionTranslationFilter 에 대해 정리해보기
- [ ] 대칭 키 암호화, RSA 암호화에 대해 정리해보기
- [X] SSL 인증서를 직접 생성해보고, Spring Boot 프로젝트에 적용해보기