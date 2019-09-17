# Homework-5

---

## 复习部分

1. 假设以下示例都是完整程序的一部分，他们打印的结果分别什么？

   - ```c
     printf("He sold the painting for $%2.2f.\n", 2.345e2);
     ```

   - ```c
     printf("%c%c%c\n", 'H', 105, '\41');
     ```

   - ```c
     #define Q "His Hamlet was funny without being vulgar."
     
     printf("%s\nhas %d characters.\n", Q, strlen(Q));
     ```

   - ```c
     printf("Is %2.2e the same as %2.2f?\n", 1201.0, 1201.0);
     ```

2. 打印以下各项内容要分别使用什么转换说明？

   - 一个字段宽度与位数相同的十进制整数
   - 一个形如8A，字段宽度为4的十六进制整数
   - 一个形如232.346，字段宽度为10的浮点数
   - 一个形如2.33e+002，字段宽度为12的浮点数

## 实践部分

- 编写一个程序， 提示用户输入以兆位每秒（Mb\s）为单位的下载速度和以兆字节（MB）为单位的文件大小。程序应计算文件的下载时间。注意，这里1字节等于8位。