# 两个对象是否相等

`==` 比较的是对象的指针，自定义对象的时候需要实现 `-(Bool)isEqual` 和 `-(NSUInteger)hash` 两个方法，也可以实现 `-(Bool)isEqualToXXXX` 。