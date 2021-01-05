# springcloud-config
springcloud-config统一管理配置文件



##有application.yml，这个文件就会自动去读这里面的数据
原application.yml数据如下

  spring:
    profiles:
      active:
      - dev
  ---
  spring:
    profiles: dev     #开发环境
    application: 
      name: config-dev
  ---
  spring:
    profiles: test     #测试环境
    application: 
      name: config-test
  #  请保存为UTF-8格式

   #测试失败
