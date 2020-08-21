# keycloak10-openshift
需要把两个文件夹拷贝到keycloak10.0.2的源代码中，使用mvn packages进行编译，

主要修改的是10.0.2(https://github.com/keycloak/keycloak.git)在使用user storage的spi时不能登录问题，把":"改成"_"

