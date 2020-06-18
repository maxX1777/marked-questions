# marked-questions
Python之random.seed()用法
seed()方法改变随机数生成器的种子，可以在调用其他随机模块函数之前调用此函数
以下是seed()方法的语法
random.seed( x )
我们调用 random.random() 生成随机数时，每一次生成的数都是随机的。但是，当我们预先使用 random.seed(x) 设定好种子之后，其中的 x 可以是任意数字，如10，这个时候，先调用它的情况下，使用 random() 生成的随机数将会是同一个。
