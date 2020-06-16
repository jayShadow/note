- bootstrap.yml 与 application.yml 的区别

--------
    bootstrap.yml优先执行,在Config Server中 启动应使用bootstrap.yml
--------
    配置文件命名规则
    /{application}/{profile}[/{label}]
    
    /{application}-{profile}.yml
    /{label}/{application}-{profile}.yml
    
    /{application}-{profile}.properties
    /{label}/{application}-{profile}.properties
