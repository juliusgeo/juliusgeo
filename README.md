### Julius

I love math, rally racing video games, statistics, and number theory (in that order).
My primary professional experience has been maintaining PyMongo, PyMongoArrow, Motor, and PyMongoExplain.
Before that I did a research project utilizing advanced NLP techniques to categorize patents.

Recent projects:
 - I implemented the Gauss Legendre algorithm in Julia to generate 20 million digits of [Pi in under 1 minute](https://gist.github.com/juliusgeo/41811563811a6e523086e514ef2bec4a)
 - I implemented complete Binary Finite Field Arithmetic in Python using bitwise operators on integers: [bff](https://gist.github.com/juliusgeo/9e4eff4c0519f7f7b9af122d59a3253e)
 - Using that arithmetic, I then proved it worked by calculating the [Rijdnael S-Box in less than 512 bytes (and it also spells out AES)](https://gist.github.com/juliusgeo/969c722b2152e53e4f6bb94ca2696c7a).
 - I used Simon Plouffe's 2022 paper on using Bernoulli numbers to generate Pi digits, [I made it into the shape of pi itself as well.](https://gist.github.com/juliusgeo/1da759d07af0b447a78d0ccb14162c57)

I also love messing around with the Python interpreter and internals:
 - I made a concurrency fuzzer that injects byte-code to opportunistically release the Global Interpreter Lock called [Confuzzion](https://github.com/juliusgeo/confuzzion)
 - I made a transpiler from Python to MongoDB Aggregations called [PyMongoAgg](https://github.com/juliusgeo/PyMongoAgg)
 - I made a tool that will automatically reflow Python code into any piece of ASCII art called [PyFlate](https://github.com/juliusgeo/pyflate)
