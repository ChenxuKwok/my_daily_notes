# c++ learning

> 参考资料：
>
> - *Programming Abstractions in C++* -- Eric S. Roberts
> - 面向对象程序设计课程 -- 浙江大学 翁恺

## Lecture 1

Course Contents

- Introduction to oop
- with a strong software engineering foundation
- aimed at producing and maintaining large, high-quality software systems

```c++
#include <iostream>
using namespace std;

int main(){
    cout << "Hello World" << endl; // << is inserter
}
```

### string

所有的编程语言，只有 c 语言在字符串末尾加上 "\0" 来识别字符串末尾。

```c++
//You must add this at the beginning of your code
#include <string>
using namespace std;
int main(){
    string str = "Hello";
    cin >> str;
    // str += "Hello";
    // functions
    cout << str.length() << endl; // 5 not including '\0'
    // ctor
    string place("Hangzhou"); // 也可以使用括号来初始化变量，和用等号是一样的道理
}
```

