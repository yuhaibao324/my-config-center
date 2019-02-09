  
  配置文件说明
  ====
  
      spring.application.name=config-server
      server.port=8888
    
    
      spring.cloud.config.server.git.uri=https://github.com/yuhaibao324/my-config-center.git
      spring.cloud.config.server.git.searchPaths=respo
      spring.cloud.config.label=master
      #spring.cloud.config.server.git.username=
      #spring.cloud.config.server.git.password=
    
      #spring.cloud.config.server.git.uri：配置git仓库地址
      #spring.cloud.config.server.git.searchPaths：配置仓库路径
      #spring.cloud.config.label：配置仓库的分支
      #spring.cloud.config.server.git.username：访问git仓库的用户名
      #spring.cloud.config.server.git.password：访问git仓库的用户密码
    
      #如果Git仓库为公开仓库，可以不填写用户名和密码，如果是私有仓库需要填写
    
      eureka.client.serviceUrl.defaultZone=http://localhost:8761/eureka/
