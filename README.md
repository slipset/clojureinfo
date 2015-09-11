# clojureinfo
A list (or something) about useful resources when starting out with Clojure

# What is this?
My friend [Stian Hundhammer](https://twitter.com/stianhundhammer) and I normally bump into each other at  [JavaZone](http://www.javazone.no), and this year was no different. We got talking and he said he was interested in starting out with Clojure, and asked me if he could drop me an email if he had some questions. 

I said of course, got all fired up and told him I'd send him an email with some links and stuff to help him get started. But then I thought again, and figured out, I could just write it here, so I could add to it as we went along.

# Some presentations for inspiration
For me, what got my facination for Clojure going, was [Bodil Stokkes](https://twitter.com/bodil) talk at Øredev in 2013. [Here](http://oredev.org/2013/wed-fri-conference/hands-on-with-clojure) she implements a full CRUD application in some 101 lines of Clojure. Code is [here](https://github.com/bodil/hands-on-with-clojure/blob/master/src/bestpony/server.clj)

Then, as I started to dig into this, I discovered the talks by Rich Hickey, [changelog.com](https://changelog.com/rich-hickeys-greatest-hits/) has a nicely curated list of his greatest hits.

After a while, I found there was a conference called [clojure/conj](http://clojure-conj.org) which has some very nice talks. Also there is [Clojure/West](http://clojurewest.org). Two of my favourites from these are [Zack Oates](https://www.youtube.com/watch?v=0GzzFeS5cMc) and [Bruce Hauman](https://www.youtube.com/watch?v=j-kj2qwJa_E).

# What about the types
For me the discussion with myself wether or not strong typing is good never ceases. In my domain, which is web-applications, we generally tend to send JSON around to various rest-apis. We fetch this data by querying databases with SQL, and we persist in the same way. So in your average Java app, you consume JSON, convert it to some domain object and then create some sql based on the domain object to persist it. Add to that a liberal amount of annotations which are also not always checked by the compiler, and you start wondering how types help you at all.
[Jessica Kerr](https://twitter.com/jessitron) nails this in this [talk](https://www.youtube.com/watch?v=GFQqyXoL0YQ)

# What editor?
Personally, setting this whole development environment thing up was a slight struggle, since [clojure on emacs](https://github.com/clojure-emacs) was not as dominant as it is today. Searching around, you still found references to Slime and nnrepl.el. This is much simpler now. Either you use Emacs with [CIDER](https://github.com/clojure-emacs/cider), vi (please forgive me) with [fireplace](https://github.com/tpope/vim-fireplace), or the excellent [cursive](https://cursiveclojure.com) if you use Intellij.

# Getting the hang of things
[4Clojure](https://www.4clojure.com) is a great site for teaching yourself the ropes with Clojure. The easier problems are all great intros to Clojure, whereas I find the harder ones hard not so much because of Clojure, but because the problems are, well, harder.

# Getting in touch
The [#clojure](http://clojure-log.n01se.net) channel on irc.freenode.net used to be the most popular hangout for Clojurians. It is still used alot, but many have moved on to [clojurians.slack.com](http://clojurians.net).

So, Stian, I guess we'll start out here, and open issues if there is anything you want to know!
