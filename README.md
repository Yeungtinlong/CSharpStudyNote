# CSharpStudyNote

## C#协变`out`与逆变`in`

```c#
class Animal {}
class Cat : Animal {}

// 这句肯定没问题，多态的应用
Animal ani = new Cat();

// 报错！Cat是继承自Animal，但List<Cat>并不继承自List<Animal>
List<Animals> animalList = new List<Cat>();

// 修改测试
```