# Zach's diary
For the past 1-2 months I've been more seriously studying computer programming. This includes (to my friend's chagrin) learning Rust. See [https://github.com/mud2monarch/rustbook](https://github.com/mud2monarch/rustbook) for more. 

This file has random assorted snippets of things i'm thinking. train of consciousness and not likely to include capitalization at times. hopefully not too unhinged. I think this will end up reverse-chronological.

### 10/1/24
Time to lock back in. Some circumstances have changed where I should be able to pursue these hobbies more frequently. It is currently Tuesday, October 1st at 5:37 AM. I have about 1h20m to code until I probably should go work out.

Good morning.

First up: piglatinfy function, see [https://github.com/mud2monarch/rustbook/tree/main/piglatinfy](https://github.com/mud2monarch/rustbook/tree/main/piglatinfy).

Reading about `&str` vs `str` vs `String` vs `[u8]`.... Rust = WOKE????? Fk this UTF-8 support!

alright, 7:09 AM. What a great session! I implemented pig_latinfy() with an `Option<char>` return type and got through some of its usage in `fn main()`. Ran overtime LMEOW, guess I'll run (blurgh). I'll go for a run then I need to go to a 9 am breakfast in fidi unfortunately.

Thinking so much about agentic AI, see twitter.com/repligate... I think I'll write something about this phenomenon later.

### 9/29/24
gm.

I've been learning a lot about all the different languages. One thing that I think is so cute about computer scientists is that they adopt these catch phrases that stem from canonical resources for teaching. For example, the boar book about efficient data systems is a meme. Rust is Blazingly Fast and has Fearless Concurrency. Even when people are talking about other things they still accede the meme. I haven't been in another ecosystem that is SO BIG (there are 10s of millions of coders!) but still maintains these memetics. Maybe because it is mostly American-dominated, at least culturally? So it's actually not that big of an ecosystem as you might think?

I also notice that crypto phrases spread to coding culture. Like ngmi.

*Links*
- https://blog.janestreet.com/what-the-interns-have-wrought-2024-edition-index/ - specifically the ocaml rewrite of the Polars library that got me interested in rust. JS culture seems cool.
- https://www.phoronix.com/news/Rust-Linux-Maintainer-Step-Down this and all its derivatives.
- https://www.wsj.com/tech/ai/open-ai-division-for-profit-da26c24b
- https://www.linkedin.com/pulse/6-secrets-building-super-team-eric-ryals/ (mirror of Greg Brockman's post, which is dead link on his website.). There is some advice that immediately contradicts impulses I've had, such as not hiring to fill a short term need, but one through line learning for me is how important it is to get away from short-term needs and focus on long term success. I have not wanted to interview candidates because it takes ~2-3 hours of work time per 30-min interview to: (1) read jd, (2) read resume and research candidate, (3) read interview script and think about what to ask, (4) do interview, (5) write coherent feedback and recommendation... that is so small relative to everything GB recommends! I think it would probably make sense to think of at least 5 hours per week of every team member's time (could scale up more for different teammates) as allocated to hiring/integration/"team growth" generally. Making that expectation explicit - that your job is not *just* to close tickets or (in my case) finish things on my todo list but to contribute to team growth - makes a lot of sense, and is probably very high ROI.

Separately, some of these things we do well at UL, some we don't (not a condemnation).
- https://cs3110.github.io/textbook/chapters/intro/present.html on immutability and functional programming.

pet peeve: why do websites only allocate 40% of the screen to reading? see [here](https://imgur.com/a/chxakHL)
ed.: PAUL GRAHAM DOES THIS ARRGGHHH [new essay](https://paulgraham.com/when.html)

why is bret taylor so important?

https://www.science.org/content/article/research-misconduct-finding-neuroscientist-eliezer-masliah-papers-under-suspicion

now digging in to writing my telegram bot with (teloxide)[https://github.com/teloxide]. i think that rust is probably not the best language for a telegram bot, but I don't want to learn another language.
first up: understanding "chain-of-responsibility" structure. done.
next: looking at some examples for using teloxide. (here's a good one)[https://medium.com/@arjunbhasin88/from-latex-to-visuals-how-i-built-a-telegram-bot-to-empower-medium-writers-cc7ef7a4b00d].
.......
holy fuck this is hard lmao