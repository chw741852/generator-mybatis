生成mybatis model,dao,mapper 文件

idea中启动：新建启动maven -> 修改Command line:-Dmybatis.generator.overwrite=true mybatis-generator:generate -e
# ... -Dmybatis.generator.configurationFile=src/main/resources/local.xml   指定配置文件,默认generatorConfig.xml