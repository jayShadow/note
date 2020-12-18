# Oauth2 

## 1.grant_type

password,authorization_code,refresh_token,client_credentials,implicit

Oauth2 

requestMatchers=[Ant [pattern='/oauth/token'], Ant [pattern='/oauth/token_key'], Ant [pattern='/oauth/check_token']]], 
[   
    org.springframework.security.web.context.request.async.WebAsyncManagerIntegrationFilter@3fa7df1, 
    org.springframework.security.web.context.SecurityContextPersistenceFilter@12c0c0b3, 
    org.springframework.security.web.header.HeaderWriterFilter@6b6eae52, 
    org.springframework.security.web.authentication.logout.LogoutFilter@34d713a2, 
    org.springframework.security.oauth2.provider.client.ClientCredentialsTokenEndpointFilter@45545e7a, 
    org.springframework.security.web.authentication.www.BasicAuthenticationFilter@4e224df5, 
    org.springframework.security.web.savedrequest.RequestCacheAwareFilter@9c73fff, 
    org.springframework.security.web.servletapi.SecurityContextHolderAwareRequestFilter@32bb0072, 
    org.springframework.security.web.authentication.AnonymousAuthenticationFilter@4dd90166, 
    org.springframework.security.web.session.SessionManagementFilter@7af52ec7, 
    org.springframework.security.web.access.ExceptionTranslationFilter@7c20cdd0, 
    org.springframework.security.web.access.intercept.FilterSecurityInterceptor@7237f3c1
]

WebSecurity
[
	org.springframework.security.web.context.request.async.WebAsyncManagerIntegrationFilter@994544, 
	org.springframework.security.web.context.SecurityContextPersistenceFilter@54463380, 
	org.springframework.security.web.header.HeaderWriterFilter@53f7a906, 
	-------------------------1---------------------------
	org.springframework.web.filter.CorsFilter@5df92089, 
	org.springframework.security.web.authentication.logout.LogoutFilter@61d2f267, 
	cn.jay.security.filter.login.UserPwdAuthenticationFilter@5db3d57c, 
	cn.jay.security.filter.login.SmsCodeAuthenticationFilter@53a50b0a, 
	org.springframework.security.web.session.ConcurrentSessionFilter@7b7068d8, 
	-------------------------end---------------------------
	org.springframework.security.web.savedrequest.RequestCacheAwareFilter@819fb19, 
	org.springframework.security.web.servletapi.SecurityContextHolderAwareRequestFilter@782ac148, 
	org.springframework.security.web.authentication.AnonymousAuthenticationFilter@6f0c45f4, 
	org.springframework.security.web.session.SessionManagementFilter@2154652c, 
	org.springframework.security.web.access.ExceptionTranslationFilter@1b3bec6c, 
	org.springframework.security.web.access.intercept.FilterSecurityInterceptor@7e58f697
]

AuthorizationServer
[
	org.springframework.security.web.context.request.async.WebAsyncManagerIntegrationFilter@4e94669c, 
	org.springframework.security.web.context.SecurityContextPersistenceFilter@64910b2d, 
	org.springframework.security.web.header.HeaderWriterFilter@7d3bf8db, 
	-------------------------1---------------------------
	org.springframework.security.web.authentication.logout.LogoutFilter@2b098563, 
	org.springframework.security.oauth2.provider.client.ClientCredentialsTokenEndpointFilter@67b560fe, 
	org.springframework.security.web.authentication.www.BasicAuthenticationFilter@2475fba3, 
	-------------------------end---------------------------
	org.springframework.security.web.savedrequest.RequestCacheAwareFilter@6fef75c6, 
	org.springframework.security.web.servletapi.SecurityContextHolderAwareRequestFilter@2fac80a8, 
	org.springframework.security.web.authentication.AnonymousAuthenticationFilter@41bb1f09, 
	org.springframework.security.web.session.SessionManagementFilter@27bb4dc5, 
	org.springframework.security.web.access.ExceptionTranslationFilter@7bc2ae16, 
	org.springframework.security.web.access.intercept.FilterSecurityInterceptor@451816fd
]

ResourceServer
[
	org.springframework.security.web.context.request.async.WebAsyncManagerIntegrationFilter@6b8b5020, 
	org.springframework.security.web.context.SecurityContextPersistenceFilter@2c9306d3,
	org.springframework.security.web.header.HeaderWriterFilter@2bd8f7db, 
	-------------------------1---------------------------
	org.springframework.security.web.authentication.logout.LogoutFilter@486bd064, 
	org.springframework.security.oauth2.provider.authentication.OAuth2AuthenticationProcessingFilter@2b6fb197, 
	-------------------------end---------------------------
	org.springframework.security.web.savedrequest.RequestCacheAwareFilter@2dfa02c1, 
	org.springframework.security.web.servletapi.SecurityContextHolderAwareRequestFilter@599f1b7, 
	org.springframework.security.web.authentication.AnonymousAuthenticationFilter@7d37ee0c, 
	org.springframework.security.web.session.SessionManagementFilter@63e5b8aa, 
	org.springframework.security.web.access.ExceptionTranslationFilter@3e6ec74, 
	org.springframework.security.web.access.intercept.FilterSecurityInterceptor@5ec9eefa
]
[
    org.springframework.security.web.context.request.async.WebAsyncManagerIntegrationFilter@457692cb, 
    org.springframework.security.web.context.SecurityContextPersistenceFilter@6d7865d6, 
    org.springframework.security.web.header.HeaderWriterFilter@3b2db389, 
    
    org.springframework.security.web.authentication.logout.LogoutFilter@e5c5e6, 
    org.springframework.security.oauth2.provider.authentication.OAuth2AuthenticationProcessingFilter@56c6d515,
     
    org.springframework.security.web.savedrequest.RequestCacheAwareFilter@77f03916, 
    org.springframework.security.web.servletapi.SecurityContextHolderAwareRequestFilter@492c9892, 
    org.springframework.security.web.authentication.AnonymousAuthenticationFilter@350342e0, 
    org.springframework.security.web.session.SessionManagementFilter@2dc3ece8, 
    org.springframework.security.web.access.ExceptionTranslationFilter@7884f722, 
    org.springframework.security.web.access.intercept.FilterSecurityInterceptor@e994ca
]
AuthorizationServer
[
	org.springframework.security.web.context.request.async.WebAsyncManagerIntegrationFilter@2401856,
	org.springframework.security.web.context.SecurityContextPersistenceFilter@309dcdf3,
	org.springframework.security.web.header.HeaderWriterFilter@2eda4eeb,
	--------------------------1----------------------------
	org.springframework.security.web.csrf.CsrfFilter@35bfa1bb,
	org.springframework.security.web.authentication.logout.LogoutFilter@149b4d20,
	org.springframework.security.web.authentication.UsernamePasswordAuthenticationFilter@1b57c345,
	org.springframework.security.web.authentication.ui.DefaultLoginPageGeneratingFilter@35dece42,
	org.springframework.security.web.authentication.ui.DefaultLogoutPageGeneratingFilter@6d6f6860,
	org.springframework.security.web.authentication.www.BasicAuthenticationFilter@2a8b33ba,
	-------------------------end---------------------------
	org.springframework.security.web.savedrequest.RequestCacheAwareFilter@7573b9ee, 
	org.springframework.security.web.servletapi.SecurityContextHolderAwareRequestFilter@543d5863, 
	org.springframework.security.web.authentication.AnonymousAuthenticationFilter@2a4f8009, 
	org.springframework.security.web.session.SessionManagementFilter@5ba90d8a, 
	org.springframework.security.web.access.ExceptionTranslationFilter@4ea17147, 
	org.springframework.security.web.access.intercept.FilterSecurityInterceptor@8e25d3f
]