# Java

## 基础

- 什么是面向对象（OOP）？

     [什么是面向对象（OOP）？](https://www.jianshu.com/p/7a5b0043b035)

- 什么是多态？实现多态的机制是什么？

- <span id="interface-abstract">接口（Interface）与抽象类（Abstract Class）的区别？</span>

     抽象类是一个可同时包含具体方法和抽象方法(方法未被实现)的类。抽象方法必须被该抽象类的子类实现。抽象类是可以继承的。

     接口像是描述类的一张蓝图或者说是类的一种契约，它包含了许多空方法，这代表着它的所有的子类都应该拥有共同点。它的子类应该提供这些空方法的具体实现。一 个类需要用 implements 来实现接口，接口可以用 extends 来继承其他接口。

- 重写（Override）与重载（Overload）的区别?

     1. 覆盖是子类与父类之间的关系，是一种垂直关系；重载是同一个类中方法之间的关系，是水平关系
     2. 覆盖只能由一个方法或者只能由一对方法产生关系；重载是多个方法之间的关系
     3. 覆盖要求参数列表要相同；重载要求参数列表不同
     4. 覆盖关系中，调用方法体是根据对象的类型（对象对应存储空间类型）决定，重载是根据调用的时候实参表和形参表来选择方法
- 父类的静态方法能否被子类重写？
- 静态属性和静态方法是否可以被继承？是否可以被重写？为什么？
- 什么是内部类？内部类、静态内部类、局部内部类和匿名内部类的区别及作用？
- == 和 equals() 和 hashCode() 的区别？
- Integer 和 int 之间的区别？
- String 转换成 Integer 的方式及原理？
- 自动装箱实现原理？类型转换实现原理？
- 对 String 的了解？
- String 为什么要设计成不可变的？
- final、finally 和 finalize 的区别？
- static 关键字有什么作用？
- 列举 Java 的集合以及集合之间的继承关系?
- List、Set、Map 的区别？
- ArrayList、LinkedList 的区别？
- HashMap，HashTable，ConcurrentHashMap 实现原理以及区别？
- HashSet 与 HashMap 怎么判断集合元素重复？
- String、StringBuffer、StringBuilder 之间的区别？
- 什么是序列化？怎么实现？有哪些方式？
- 对反射的了解？
- 对注解的了解？
- 对依赖注入的了解？
- 对泛型的了解？
- 泛型中 extends 和 super 的区别？
- 对 Java 的异常体系的了解？
- 对解析与分派的了解？
- 静态代理和动态代理的区别？有什么场景使用？
- 谈谈对 Java 状态机理解？

## 线程与并发

- 线程和进程的区别？
- 开启线程的三种方式
- 如何正确的结束一个Thread?
- Thread 与 Runnable 的区别？
- run() 与 start() 方法的区别？
- sleep() 与 wait() 方法的区别？
- wait 与 notify 关键字的区别？
- synchronized 关键字的用法、作用及实现原理？
- volatile 关键字的用法、作用及实现原理？
- transient 关键字的用法、作用及实现原理？
- ReentrantLock、synchronized、volatile 之间的区别？
- 什么是线程池，如何使用?
- 多线程断点续传的实现原理？
- 什么是深拷贝和浅拷贝？
- Java 中对象的生命周期？
- 对并发编程的了解？

## JVM

- 简述 JVM 内存模型和内存区域？
- 简述垃圾回收器的工作原理？
- 如何判断对象的生死？垃圾回收算法？新生代，老生代？
- 哪些情况下的对象会被垃圾回收机制处理掉？
- 垃圾回收机制与调用 System.gc() 的区别？
- 强引用、软引用、弱引用、虚引用之间的区别？
- 强引用设置为 null，会不会被回收？
- 简述 ClassLoader 类加载机制？
- 对双亲委派模型的了解？
- String a = "a"+"b"+"c" 在内存中创建几个对象？
- 对 Dalvik、ART 虚拟机的了解？
- 对动态加载（OSGI）的了解？
- 常见编码方式有哪些？
- utf-8 编码中的中文占几个字节？int 型占几个字节？