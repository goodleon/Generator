# Generator
生成器：
1.  代码生成器；但代码都是乱码, 并不是可读的
2. 文件生成器。


```
public static void main(String[] args){

    generateCode("/Users/guoqiang/Desktop/Code/", 20);

}
```
- 前面参数是代码生成路径,后面是文件数量
- 把Java代码编译下：
`javac   /Users/guoqiang/Desktop/CodeGenerator/src/com/generator/Generator.java`

编译成 class 文件

然后执行 到bin目录执行下面 这个class文件

`java com.generator.Generator`
