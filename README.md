## langtools

* 版本: openjdk 7u
* 下载openjdk的langtools，http://hg.openjdk.java.net/jdk7u/jdk7u/langtools
* 源码目录: langtools/src/share/classes
* javac的入口Main类: `com.sun.tools.javac.Main`
* 新建Main类调用`com.sun.tools.javac.Main`的`main()`方法

```java
public class JavacLauncher {

    public static void main(String[] args) throws Exception {
        Main.main(args);
    }

}
```
