# mavendemo
ssm_maven多模块开发

在maven中指定对应的Jdk
        <maven.compiler.source>1.8</maven.compiler.source>  
        <maven.compiler.target>1.8</maven.compiler.target>  
        <maven.compiler.compilerVersion>1.8</maven.compiler.compilerVersion> 

然后进行跳过测试打包


package -Dmaven.test.skip=true
