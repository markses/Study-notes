# JavaScript初步学习

* ```javascript
  document.getElementById("demo")
  文档对象模型通过id获取文档对象中的元素
  ```

  > ## JavaScript 四种输出
  >
  > * 使用 **window.alert()** 弹出警告框 <color> 
  >
  > * 使用 **document.write()** 方法将内容写到 HTML 文档中
  > * 使用 **innerHTML** 写入到 HTML 元素
  > * 使用 **console.log()** 写入到浏览器的控制台    

  ## JavaScript 数据类型  

  * var用来申明变量

  * 多种数据类型

  * ```javascript
    var length = 16;                                  // Number 通过数字字面量赋值
    var points = x * 10;                              // Number 通过表达式字面量赋值
    var lastName = "Johnson";                         // String 通过字符串字面量赋值
    var cars = ["Saab", "Volvo", "BMW"];              // Array  通过数组字面量赋值
    var person = {firstName:"John", lastName:"Doe"};  // Object 通过对象字面量赋值
    ```

* 值类型(基本类型)：字符串（String）、数字(Number)、布尔(Boolean)、对空（Null）、未定义（Undefined）、Symbol(表示独一无二的值)

* **引用数据类型**：对象(Object)、数组(Array)、函数(Function)

* 不包含任何值的数据类型：null 、undefined  

* 

* null 和 undefined 的值相等，但类型不等

* Javascript对象：键值对

* typeof 操作符：检查值的类型

## JavaScript比较运算符

* ===  绝对等于，值和类型均相等
* !== 不绝对等于，值和类型有一个或者两个都不相等

###  JavaScript关键字this

* 在方法中，表示方法所在的对象
* 单独使用，则全局对象 [**object Window**]
* 事件中的this,指向了接收事件的 HTML 元素

### 新增的两个关键字

* let:  let 声明的变量只在 let 命令所在的代码块内有效

  ```javascript
  { 
      let x = 2;
  }
  // 这里不能使用 x 变量
  ```

* const(类似常量):  const 用于声明一个或多个常量，声明时必须进行初始化，且初始化后值不可再修改

### JSON 数据(键值对)

* JavaScript 内置函数 JSON.parse() 将字符串转换为 JavaScript 对象
* JSON.stringify(),将 JavaScript 值转换为 JSON 字符串

