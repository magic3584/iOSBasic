# NSString, NSMutableString, strong, copy

直接上图，注意比较属性和局部变量的地址。



1. `@property (nonatomic, copy) NSString * constantString`

   [copy-string-string-string](http://p8gcuv9g8.bkt.clouddn.com/copy-string-string-string.png)

   [copy-string-string-mutable](http://p8gcuv9g8.bkt.clouddn.com/copy-string-string-mutable.png)

   [copy-string-mutable-string](http://p8gcuv9g8.bkt.clouddn.com/copy-string-mutable-string.png)

   [copy-string-mutable-mutable](http://p8gcuv9g8.bkt.clouddn.com/copy-string-mutable-mutable.png)

   ​

2. `@property (nonatomic, strong) NSString * constantString`

   [strong-string-string-string](http://p8gcuv9g8.bkt.clouddn.com/strong-string-string-string.png)

   [strong-string-string-mutable](http://p8gcuv9g8.bkt.clouddn.com/strong-string-string-mutable.png)

   [strong-string-mutable-string](http://p8gcuv9g8.bkt.clouddn.com/strong-string-mutable-string.png)

   [strong-string-mutable-mutable](http://p8gcuv9g8.bkt.clouddn.com/strong-string-mutable-mutable.png)

   ​

3. `@property (nonatomic, copy) NSMutableString * mutableString`

   [copy-mutable-string-string](http://p8gcuv9g8.bkt.clouddn.com/copy-mutable-string-string.png)

   [copy-mutable-string-mutable](http://p8gcuv9g8.bkt.clouddn.com/copy-mutable-string-mutable.png)

   [copy-mutable-mutable-string](http://p8gcuv9g8.bkt.clouddn.com/copy-mutable-mutable-string.png)

   [copy-mutable-mutable-mutable](http://p8gcuv9g8.bkt.clouddn.com/copy-mutable-mutable-mutable.png)

   ​

4. `@property (nonatomic, strong) NSMutableString * mutableString`

   [strong-mutable-string-string](http://p8gcuv9g8.bkt.clouddn.com/strong-mutable-string-string.png)

   [strong-mutable-string-mutable](http://p8gcuv9g8.bkt.clouddn.com/strong-mutable-string-mutable.png)

   [strong-mutable-mutable-string](http://p8gcuv9g8.bkt.clouddn.com/strong-mutable-mutable-string.png)

   [strong-mutable-mutable-mutable](http://p8gcuv9g8.bkt.clouddn.com/strong-mutable-mutable-mutable.png)

