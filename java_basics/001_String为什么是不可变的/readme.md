1.构造方法是final的

2.常量池，多个String引用会指向String常量池中的一个值，
一个String应用改变，不影响其他String引用

3.hashMap的key是不可变的，用String作为hashMap的key

4.String类中有一个final修饰的成员hashcode，
String初始化就产生，避免多次计算hash
