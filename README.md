### Hi, I'm Nicolás Barroso 👋🏻

```java
public class Info {

    public static void main(String[] args) {

        String name = "Nico"; //some friends call me "vraxh"
        String[] code = {"Java", "Python"}; //currently much more Java
        String[] tools = {"Maven", "Spring" ,"Spring boot" ,"Spring data", "Hibernate", "Docker", "VSCode"};
        String[] databases = {"MySql", "sqlite"};

        AboutMe myInfo = new AboutMe(name, code, tools, databases);

        System.out.println("Personal Information:");
        myInfo.showInfo();
    }
}
```
