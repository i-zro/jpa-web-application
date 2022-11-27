
## Getter, Setter (Lombok 적용)

```java
@Getter
@Setter
public class Hello {
    private String data;
}
```

```java
		Hello hello = new Hello();
		hello.setData("Hello World!");
		String data = hello.getData();
		System.out.println("data = " + data);
```