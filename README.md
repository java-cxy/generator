# mybatis逆向工程生成代码

1.把项目拷贝到项目根目录下

2.修改文件中标志数字的地方

3.在命令行中进入generator目录，执行如下命令：

    java -jar mybatis-generator-core-1.3.2.jar -configfile genertor.xml -overwrite

  自动生成mapper，dao，model的数据库文件
