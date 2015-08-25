# Everything You Know About the GIL is Wrong -- RubyConf 2015

## Title

Everything You Know About the GIL is Wrong

## Abstract

One of the most pervasive misconceptions about Ruby is that it can't do concurrency. This is completely false. The Global Interpreter Lock (GIL), also called the Global VM Lock (GVL), does NOT prevent Ruby programs from performing concurrently. In this presentation we will discuss the true meaning of concurrency (hint: it's design), explore the inner-workings of the GIL, and gain a deeper understanding of its implications. Along the way we'll write a bunch of concurrent Ruby code, run it on different interpreters, and compare the results.
