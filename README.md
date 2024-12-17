### Julius

I love math, rally racing video games, statistics, and number theory (in that order).

Recent projects:
 - a tool that transpiles Python code into expression-only syntax (lambda functions and list comprehensions only), in addition to reflowing that code into ASCII art called [Exprify](https://github.com/juliusgeo/exprify)
 - a (somewhat) branchless version of the binary search algorithm that beats the `bisect` module in terms of speed using C-extensions. See the [`README`](https://github.com/juliusgeo/branchless_bisect) for more details: 
 - the Gauss Legendre algorithm in Julia to generate 20 million digits of [Pi in under 1 minute](https://gist.github.com/juliusgeo/41811563811a6e523086e514ef2bec4a)
 - implemented complete Binary Finite Field Arithmetic in Python using bitwise operators on integers: [bff](https://gist.github.com/juliusgeo/9e4eff4c0519f7f7b9af122d59a3253e)
 - using that arithmetic, I then proved it worked by calculating the [Rijdnael S-Box in less than 512 bytes (and it also spells out AES)](https://gist.github.com/juliusgeo/969c722b2152e53e4f6bb94ca2696c7a).
 - used Simon Plouffe's 2022 paper on using Bernoulli numbers to generate Pi digits, [I made it into the shape of pi itself as well.](https://gist.github.com/juliusgeo/1da759d07af0b447a78d0ccb14162c57)
 - made a concurrency fuzzer that injects byte-code to opportunistically release the Global Interpreter Lock called [Confuzzion](https://github.com/juliusgeo/confuzzion)
 - made a transpiler from Python to MongoDB Aggregations called [PyMongoAgg](https://github.com/juliusgeo/PyMongoAgg)
