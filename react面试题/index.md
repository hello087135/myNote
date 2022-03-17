#### 如何理解react元素的不可变性
1. 在react17之前只是一个规定，在react17之后修改会报错（修改包括添加属性），如果想要让一个元素只读的话可以使用object.freeze
2. object.freeze和object.seal的区别是，前者不能修改和添加新的属性，后者是可以修改但是不能够添加属性
#### 