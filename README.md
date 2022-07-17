# springboot-netflix-zuul-security 

* Reference for How to Fix WebSecurityConfigurerAdapter Deprecated:
    > https://spring.io/blog/2022/02/21/spring-security-without-the-websecurityconfigureradapter
    >
    > https://codejava.net/frameworks/spring-boot/fix-websecurityconfigureradapter-deprecated
  
* When we write SecurityConfig with permitAll except patient-Service. It will allow all other url except patient-service.
* It will allow:
  > http://localhost:8100/doctor-service/doctors
  
* It will throw access denied error:
  > http://localhost:8100/patient-service/patients