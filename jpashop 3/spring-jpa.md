# 221127

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

# 221129

#### h2 데이터베이스 생성 방법 
- jdbc:h2:~/jpashop (최소 한번)
- ~/jpashop.mv.db 파일 생성 확인
- 이후 부터는 jdbc:h2:tcp://localhost/~/jpashop 이렇게 접속