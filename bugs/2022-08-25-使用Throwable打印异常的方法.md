![image](../images/Snipaste_2022-08-25_22-17-07.png)

如图所示，同事用这个打印异常，提交代码，主管看到之后，发在群里，禁止大家这样写。

printStackTrace作用打印异常到控制台，会将产生错误堆栈字符串存入到字符串池内存空间。存到这里边，如果这个controller，有很多请求进来，将会导致常量池空间被占满，导致OOM。

