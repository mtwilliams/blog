# Why C++ is back.

I love C++, [too](http://simpleprogrammer.com/2012/12/01/why-c-is-not-back/). It's an amazing tool.

Six years ago I began my never-ending learning experience, programming. It started with an arcane toolkit called [Jamagic](http://kartones.net/blogs/kartones/archive/2004/12/02/jamagic-a-good-idea-that-faded-away.aspx) (which was unfortunately discontinued). Jamagic's scripting language, JamagicScript is an amalgamation of C++, Java, and multimedia wrappers that allow for simple games and "simulators" to be developed without extensive knowledge of math or programming--a perfect fit for an eager ten year-old. It wasn't, at least for me. I soon grew tired of Jamagic primarily due to the abstract nature of it; I wanted to program, not point and click (albeit with some scripting).

This lead me to C, a succinct and pragmatic language--a perfect fit for me. I quickly picked up the ropes (memory management, pointer arithmetic, etc.). I started hammering out code. I could keep track of my piggy bank, or determine prime numbers! I felt amazing, because I was creating. As I became more adjusted to the intricacies of the language I picked up C++. Over the next three years I learned about the Win32 API and the underlying structures that made Windows. I mastered C++, or so I thought.

C++ is ever evolving (as is my knowledge of it[^1]). The latest standard, [C++11](http://wiki.apache.org/stdcxx/C%2B%2B0xCompilerSupport) definitely makes it easier to become proficient. Making it easier to learn might be a natural extension of that: smart pointers are an incredibly powerful abstraction that might help new programmers, lambdas make code more succinct thus more understandable, etc. With C++ becoming more [accessible](http://clang.llvm.org/diagnostics.html) it is illogical to dissuade newcomers from learning C++, perhaps shameful:

 * Knowledge. Learning a craft or skill is hard, C++ especially so. It requires perseverance and courage--fundamental skills for success (especially as a founder) that a large portion of today's youth lack. Learning C++ also results in heaps domain specific knowledge. The same goes for [functional languages](http://common-lisp.net/).

 * Hireability. As mentioned previously, extensive domain specific knowledge is acquired, and that knowledge is in [heavy demand](http://www.tiobe.com/index.php/content/paperinfo/tpci/index.html). Especially bit twiddling (which I assume pays better).

 * Portability. C# and Java require virtual machines, that immediately limits portability to supported platforms. [Abstractions leak](http://www.joelonsoftware.com/articles/LeakyAbstractions.html): threading is a great example of this (Go is an honourable mention here; it handles [concurrency](http://golang.org/doc/effective_go.html#concurrency) elegantly). Furthermore, embedded systems require C or a relative like C++, or Obj-C.

To summarize, [more](http://www.tiobe.com/index.php/content/paperinfo/tpci/index.html) and [more](https://github.com/facebook) companies are relying on C and C++. Learning an in demand skill is a no-brainer, and with C++ becoming "easier" to learn we have produced a low-hanging fruit. Expect a resurgence.

[^1]: [An example of the intricacies of C.](http://blog.regehr.org/archives/721)
