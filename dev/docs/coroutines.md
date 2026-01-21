https://gist.github.com/stjordanis/ad0e97faab56f74a8eb5ba331281e723

cpp.std.coroutines.draft.md

# [C++ links](https://github.com/MattPD/cpplinks): Coroutines

https://github.com/MattPD/cpplinks / C++ Standard / C++20 / Coroutines

_(draft; work in progress)_

## Readings

- https://en.cppreference.com/w/cpp/language/coroutines
- Working Draft, C++ Coroutines
	- https://wg21.link/n4775
	- merged into C++20, http://wg21.link/p0912
- Coroutines TS Customization Points - https://hackmd.io/s/S1H_loeA7
- Dawid Pilarski
	- Coroutines introduction - https://blog.panicsoftware.com/coroutines-introduction/
	- Your first coroutine - https://blog.panicsoftware.com/your-first-coroutine/
	- co_awaiting coroutines - https://blog.panicsoftware.com/co_awaiting-coroutines/
- How C++ coroutines work - Kirit Sælensminde
	- https://kirit.com/How%20C%2B%2B%20coroutines%20work
- Lewis Baker
	- Coroutine Theory - https://lewissbaker.github.io/2017/09/25/coroutine-theory
	- C++ Coroutines: Understanding operator co_await - https://lewissbaker.github.io/2017/11/17/understanding-operator-co-await
	- C++ Coroutines: Understanding the promise type - https://lewissbaker.github.io/2018/09/05/understanding-the-promise-type
- What are coroutines and why should I care? - Marco Alesiani
	- http://www.italiancpp.org/2016/11/02/coroutines-internals/

## Software

- CppCoro - A coroutine library for C++
	- https://github.com/lewissbaker/cppcoro
- Conduit: Lazy High Performance Streams using Coroutine TS
	- https://github.com/loopperfect/conduit
- folly::coro - a developer-friendly asynchronous C++ framework based on Coroutines TS
	- https://github.com/facebook/folly/tree/master/folly/experimental/coro
	- https://cppcast.com/2019/03/kirk-shoop/

### Examples

- libc++
	- https://github.com/llvm/llvm-project/blob/release/8.x/libcxx/test/std/experimental/language.support/support.coroutines/end.to.end/generator.pass.cpp
	- https://github.com/llvm/llvm-project/blob/release/8.x/libcxx/test/support/coroutine_types.h
- http://cppcast.com/2017/07/gor-nishanov/
	- Compiler Explorer: Coroutines clang demo - https://godbolt.org/g/pq6x57
	- Wandbox: Coroutines with Ranges - https://wandbox.org/permlink/D60wIndMZbth7BXS
- David Hollman - https://twitter.com/TheWholeDavid/status/1063135275671535616
	- https://wandbox.org/permlink/OqlSdKihqjBX2qUs
- Boost.Asio
	- https://www.boost.org/doc/libs/release/doc/html/boost_asio/examples/cpp17_examples.html
- coro-async - C++ coroutine based networking library (WIP)
	- https://github.com/arun11299/coro-async
- Coroutine TS: A new way of thinking - https://github.com/arBmind/2018-cogen-en
	- https://github.com/arBmind/2018-cogen-en/tree/develop/code
- Exploring the C++ Coroutine - https://github.com/luncliff/coroutine/
	- https://github.com/luncliff/coroutine/wiki

## Talks

- 2019 C++ Korea Facebook Group: Park Dong Ha - Exploring the C++ Coroutine: Approach, Compiler, and Issues
	- https://github.com/luncliff/coroutine/wiki/Exploring-the-Cpp-Coroutine
- 2018 Meeting C++: Andreas Reischuck - Coroutine TS a new way of thinking
	- https://www.youtube.com/watch?v=RL5oYUl5548
	- https://github.com/arBmind/2018-cogen-en
- 2018 CppCon: G. Nishanov “Nano-coroutines to the Rescue! (Using Coroutines TS, of Course)”
	- https://www.youtube.com/watch?v=j9tlJAqMV7U
- 2018 LLVM Developers’ Meeting: J. McCall “Coroutine Representations and ABIs in LLVM”
	- https://www.youtube.com/watch?v=wyAbV8AM9PM&t=1017s
- 2018 Core C++: Yehezkel Bernat - Coroutines - Back to the Future
	- https://www.youtube.com/watch?v=eZrhz9v1ApE
	- https://corecppil.github.io/Meetups/2018-09-17_Sweet-C++/Coroutines.pdf
- 2017 CppCon: Anthony Williams “Concurrency, Parallelism and Coroutines” - https://www.youtube.com/watch?v=JvHZ_OECOFU
- 2017 CppCon: Gor Nishanov “Naked coroutines live (with networking)” - https://www.youtube.com/watch?v=UL3TtTgt3oU
- 2017 CppCon: Toby Allsopp “Coroutines: what can't they do?” - https://www.youtube.com/watch?v=mlP1MKP8d_Q
- 2017 Pacific++: Toby Allsopp "An Introduction to the Proposed Coroutine Support for C++"
	- https://www.youtube.com/watch?v=nWuXubffryo
- 2016 await/yield: C++ coroutines - Zbigniew Skowron - 30 November, 2016 - http://cpp.mimuw.edu.pl/files/await-yield-c++-coroutines.pdf
- 2016 CppCon: Gor Nishanov “C++ Coroutines: Under the covers" - https://www.youtube.com/watch?v=8C8NnE1Dg4A
- 2016 CppCon: James McNellis “Introduction to C++ Coroutines" - https://www.youtube.com/watch?v=ZTqHjjm86Bw
- 2016 LLVM Developers’ Meeting: G. Nishanov “LLVM Coroutines” - https://www.youtube.com/watch?v=Ztr8QvMhqmQ
- 2015 C++Now - Gor Nishanov: C++17 coroutines for app and library developers - https://www.youtube.com/watch?v=proxLbvHGEQ
- 2015 CppCon: Gor Nishanov “C++ Coroutines - a negative overhead abstraction" - https://www.youtube.com/watch?v=_fu0gx-xseY
- 2015 Meeting C++: An Introduction to C++ Coroutines - James McNellis - https://www.youtube.com/watch?v=YYtzQ355_Co
