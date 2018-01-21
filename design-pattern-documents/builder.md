# 构建者设计模式
###### builder，也称为“构造器模式”或“生成器模式”
## 1.使用场景
构建者设计模式适用于具有较多属性的对象的构建构成。<br/>
仔细理解下这句话，需要自己思索下<br/>
- 传统的对象是如何构建的？当然，首先想到的是构造函数了。但是构造函数有一个很大的
弊端就是可读性查，当参数过多的时候，这个问题尤为明显，代码的可读性在实际开发中是
非常关键的，降低别人使用或者你代码所需要的时间，本身就是代码质量的一种体现。

## 2.基本构成

