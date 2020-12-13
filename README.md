

2020-12-13 09:26:53.320  INFO 10520 --- [           main] c.p.t.s.SpringRedditCloneApplication     : Starting SpringRedditCloneApplication using Java 13.0.1 on DESKTOP-EV67VQO with PID 10520 (D:\Programowanie\spring-disabled\target\classes started by User in D:\Programowanie\spring-disabled)
2020-12-13 09:26:53.322  INFO 10520 --- [           main] c.p.t.s.SpringRedditCloneApplication     : No active profile set, falling back to default profiles: default
2020-12-13 09:26:53.403  WARN 10520 --- [kground-preinit] o.s.h.c.j.Jackson2ObjectMapperBuilder    : For Jackson Kotlin classes support please add "com.fasterxml.jackson.module:jackson-module-kotlin" to the classpath
2020-12-13 09:26:54.892  INFO 10520 --- [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat initialized with port(s): 8080 (http)
2020-12-13 09:26:54.899  INFO 10520 --- [           main] o.apache.catalina.core.StandardService   : Starting service [Tomcat]
2020-12-13 09:26:54.900  INFO 10520 --- [           main] org.apache.catalina.core.StandardEngine  : Starting Servlet engine: [Apache Tomcat/9.0.39]
2020-12-13 09:26:55.007  INFO 10520 --- [           main] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring embedded WebApplicationContext
2020-12-13 09:26:55.007  INFO 10520 --- [           main] w.s.c.ServletWebServerApplicationContext : Root WebApplicationContext: initialization completed in 1646 ms
2020-12-13 09:26:55.046  WARN 10520 --- [           main] ConfigServletWebServerApplicationContext : Exception encountered during context initialization - cancelling refresh attempt: org.springframework.beans.factory.UnsatisfiedDependencyException: Error creating bean with name 'securityConfig' defined in file [D:\Programowanie\spring-disabled\target\classes\com\programming\techie\springredditclone\config\SecurityConfig.class]: Unsatisfied dependency expressed through constructor parameter 0; nested exception is org.springframework.beans.factory.UnsatisfiedDependencyException: Error creating bean with name 'userDetailsServiceImpl' defined in file [D:\Programowanie\spring-disabled\target\classes\com\programming\techie\springredditclone\service\UserDetailsServiceImpl.class]: Unsatisfied dependency expressed through constructor parameter 0; nested exception is org.springframework.beans.factory.NoSuchBeanDefinitionException: No qualifying bean of type 'com.programming.techie.springredditclone.repository.UserRepository' available: expected at least 1 bean which qualifies as autowire candidate. Dependency annotations: {}
2020-12-13 09:26:55.048  INFO 10520 --- [           main] o.apache.catalina.core.StandardService   : Stopping service [Tomcat]
2020-12-13 09:26:55.062  INFO 10520 --- [           main] ConditionEvaluationReportLoggingListener : 

Error starting ApplicationContext. To display the conditions report re-run your application with 'debug' enabled.
2020-12-13 09:26:55.077 ERROR 10520 --- [           main] o.s.b.d.LoggingFailureAnalysisReporter   : 

***************************
APPLICATION FAILED TO START
***************************

Description:

Parameter 0 of constructor in com.programming.techie.springredditclone.service.UserDetailsServiceImpl required a bean of type 'com.programming.techie.springredditclone.repository.UserRepository' that could not be found.


Action:

Consider defining a bean of type 'com.programming.techie.springredditclone.repository.UserRepository' in your configuration.


Process finished with exit code 1
