# Generator

mybatis 逆向工程

在idea中直接以maven项目导入
修改properties 里面的相关设置，并把目录下的mysql-connectorjava-1.5.40-jar包放到指定目录
修改generatorConfig里面的最下面需要生成的表名
然后点击 run =》edit Configurations
点击 绿色的 + 号
找到maven

设置name随便取：比如 generator
working directory 设置为项目路径
command line 输入“mybatis-generator:generate  -e”
然后点击 appaly 
然后点击 又上面的  generator运行就好了
