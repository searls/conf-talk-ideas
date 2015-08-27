# Everything You Know About the GIL is Wrong

Conferences: RubyConf 2015

## Title

Everything You Know About the GIL is Wrong

## Abstract

Breaking this up line-by-line:

> One of the most pervasive misconceptions about Ruby is that it can't do concurrency. This is completely false. 

Let's make this a little punchier, something like:

"When a Rubyist hears 'concurrency', they usually google Elixir, Go, or even Node.js. Turns out, Ruby can be great for concurrency!"

Or similar. I'm out of punchiness.

Next:

> The Global Interpreter Lock (GIL), also called the Global VM Lock (GVL), does NOT prevent Ruby programs from performing concurrently. 

+1. If you need to save chars, whack the GVL aside as it's not critical.

> In this presentation we will discuss the true meaning of concurrency (hint: it's design),

The paranthetical here irks me because when you suggest "it's design", it encourages the reader to start imagining for themselves where you're leading them, and it'll take different people in different directions. For example, when I read that I assumed "Oh, Jerry's going to use some sleight of hand and show off patterns that aren't truly concurrent and just workaround the GIL", which isn't what you're going for.

> explore the inner-workings of the GIL, and gain a deeper understanding of its implications. 

+1. Possibly better word choice for "implications"

> Along the way we'll write a bunch of concurrent Ruby code, run it on different interpreters, and compare the results.

Always good.
