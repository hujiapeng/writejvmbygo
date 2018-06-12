1. 创建HelloWorld.java文件，并写代码如下<br/>
	<pre>
	public class HelloWorld{
        public static void main(String[] args){
            System.out.println("Hello World");
        }
    }
	</pre>

2. 编译文件：javac HelloWorld.java<br/>
   执行文件：java HelloWorld<br/>
   ![](https://raw.githubusercontent.com/hujiapeng/writejvmbygo/master/src/jvmgo/ch01/imgs/helloworld.png)

3. 执行go install jvmgo\ch01时报错，在%GOPATH%\src下找不到对应package，所以又将src\jvmgo\ch01的上一级文件夹路径加入GOPATH（加入方式是使用分号分割）
4. 执行完go install jvmgo\ch01后，在src同级目录下有个bin文件夹，bin下有个ch01.exe，命令窗口模式下执行ch01.exe -help或ch01.exe -version或ch01.exe -cp cn/ittutu MyApp arg1 arg2
   ![](https://raw.githubusercontent.com/hujiapeng/writejvmbygo/master/src/jvmgo/ch01/imgs/jvmgo.png)
    