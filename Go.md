

### 1.基础

#### 1.1环境变量

>GOROOT：go的sdk安装目录
>
>GOPATH：工作目录「创建项目时，指定的存放目录」，计算机会自动帮你定位到那
>
>PATH：go语言的sdk下的bin目录

#### 1.2注释

// 行注释(官方推荐)

/*

*/ 块注释

#### 1.3格式化

```go
gofmt -w xx.go
```

#### 1.4规范

- Go 应用程序的执行入口是 main()函数；

- Go 应用程序的执行入口是 main()函数；

- Go 语言严格区分大小写；

- Go 方法由一条条语句构成，每个语句后不需要分号

- go是一行一行编译不可以把多个语句写在同一行

- 定义的变量或者import引入的包未使用都会报错

- 括号都要匹配

- 每一行不要超过80个字符

  ```
  fmt.Prinf("aaaa",
  "hello");
  ```

  