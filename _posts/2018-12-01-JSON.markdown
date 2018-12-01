# JSON

**JSON**（JavaScript Object Notation）是一种通过普通字符串描述数据的手段，用于表示有结构的数据。类似于编程语言中字面量的概念 。语法上跟 JavaScript 的字面量非常类似。

> 作用：表述数据的手段
>
> 现如今用的最多的数据格式

### JSON 数据类型

+ null

  ```json
  null
  ```

+ string

  ```json
  "hello world"
  ```

+ number

  ```json
  2048
  ```

+ boolean

  ```json
  true
  ```

+ object

  ```json
  {
      "name": "zs",
      "age": 19,
      "sex": "女",
      "gender": true;
      "_friend": null
  }
  ```

+ array

  ```json
  ["zhangsan","lisi","wangmazi"]
  ```


### json注意事项：

> JSON 中属性名称必须用双引号包裹
>
> JSON 中字符串必须要用双引号包裹
>
> JSON 中不允许使用注释
>
> JSON 中没有 undefined 这个值