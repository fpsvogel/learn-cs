<!-- omit in toc -->
# Learn Computer Science

I'm second-career web developer (writing mostly Ruby) since 2022, meaning I didn't get a computer science degree. So this list is me catching up.

<!-- omit in toc -->
## Table of contents

- [Networking / the Web](#networking--the-web)
- [Hardware systems](#hardware-systems)
- [Operating systems](#operating-systems)
- [Linux / command line](#linux--command-line)
- [Concurrency / distributed systems](#concurrency--distributed-systems)
- [Database internals](#database-internals)
  - [Database readings](#database-readings)
    - [PostgreSQL](#postgresql)
  - [Database exercises](#database-exercises)
- [Compilers](#compilers)
- [Math / logic](#math--logic)
- [Data structures and algorithms](#data-structures-and-algorithms)
  - [Textbooks / courses](#textbooks--courses)
  - [Interview guides](#interview-guides)
  - [LeetCode](#leetcode)
- [Software architecture](#software-architecture)
- [Performance](#performance)
- [Low-level programming](#low-level-programming)
  - [C](#c)
  - [Zig](#zig)
  - [Implement a Forth](#implement-a-forth)

## Networking / the Web

- **HTTP:**
  - [x] 💲[Noah Gibbs - Rebuilding HTTP](https://noahgibbs.gumroad.com/l/rebuilding_http).
  - [ ] [http2 explained](https://daniel.haxx.se/http2/)
  - [ ] [HTTP/3 explained](https://http3-explained.haxx.se/)
  - [ ] 💲[HTTP/2 in Action](https://www.manning.com/books/http2-in-action)
  - [ ] 💲[Build Your Own Web Server From Scratch In Node.JS](https://leanpub.com/byo_web_server/) <!-- Related: [Ruby HTTP server from the ground up](https://www.dmitry-ishkov.com/2021/07/ruby-http-server-from-ground-up.html), [Building a simple websockets server from scratch in Ruby](https://www.honeybadger.io/blog/building-a-simple-websockets-server-from-scratch-in-ruby/), [Build Your Own Web Server](https://codingchallenges.fyi/challenges/challenge-webserver/), [How to Build a Web App with and without Rails Libraries](https://shopify.engineering/building-web-app-ruby-rails), [a Reddit discussion with helpful comments](https://www.reddit.com/r/ruby/comments/vfc02l/newb_here_have_you_written_your_own_web_server) -->
- **Networking:**
  - [ ] [High Performance Browser Networking](https://hpbn.co/)
  - [ ] [Computer Networking : Principles,Protocols and Practice](https://www.computer-networking.info/)
  - [x] 💲[Computer Networking: A Top-Down Approach](https://gaia.cs.umass.edu/kurose_ross/index.php)
  - [ ] [Jesse Storimer - Working with TCP Sockets](https://workingwithruby.com/wwtcps/intro) <!-- Related: [How to build a network stack in Ruby](https://medium.com/geckoboard-under-the-hood/how-to-build-a-network-stack-in-ruby-f73aeb1b661b) -->
  - [ ] [Beej's Guide to Network Programming](https://beej.us/guide/bgnet/)
  - [ ] Experiment with CDNs or reverse proxies (e.g. Nginx, Varnish,	HAProxy, Cloudflare) to understand caching, TLS termination, load balancing, and security filtering (rate limiting, WAF, etc.).
- **Security:**
  - [x] 💲[Grokking Web Application Security](https://www.manning.com/books/grokking-web-application-security) and the free accompanying site [Hacksplaining](https://www.hacksplaining.com/)
  - [ ] [PortSwigger - web security exercises](https://portswigger.net/web-security/all-topics)
- **Browsers:**
  - [ ] [Web Browser Engineering](https://browser.engineering/)
  - [ ] [High Performance Browser Networking](https://hpbn.co/)

## Hardware systems

- [x] 💲[Code: The Hidden Language of Computer Hardware and Software](https://www.informit.com/store/code-the-hidden-language-of-computer-hardware-and-software-9780137909100)
- [ ] [NandGame](https://nandgame.com) and solutions: [1](https://www.reddit.com/r/nandgame_u/wiki/index/level-solutions/), [2](https://github.com/timlg07/NandGame-Solutions/blob/master/Solutions.md), [3](https://github.com/simsieg/nandgame-solutions)
- [x] From Nand to Tetris: [Part 1](https://www.coursera.org/learn/build-a-computer), [Part 2](https://www.coursera.org/learn/nand2tetris2)
- [ ] Circuit sandboxes:
  - [CircuitVerse](https://circuitverse.org/)
  - [Logisim Evolution](https://github.com/logisim-evolution/logisim-evolution)
  - [wireworld](https://danprince.github.io/wireworld/)
  - 💲[Turing Complete](https://store.steampowered.com/app/1444480/Turing_Complete/)
  - 💲[Virtual Circuit Board](https://store.steampowered.com/app/1885690/Virtual_Circuit_Board/)
  - 💲[Circuit Artist](https://store.steampowered.com/app/3139580/Circuit_Artist/)
- [ ] [CS61C: Great Ideas in Computer Architecture](https://cs61c.org) and [2020 lectures](https://www.youtube.com/@berkeley-cs61c/videos) or [2014 lectures](https://archive.org/details/UCBerkeley_Course_Computer_Science_61C)
- [ ] [Computer Organization and Design](https://archive.org/details/computerorganiza0000patt_u5t2)
- [ ] [Dive into Systems](https://diveintosystems.org/singlepage)
- [ ] [What Every Programmer Should Know About Memory](https://people.freebsd.org/~lstewart/articles/cpumemory.pdf)
- [ ] [What's new in CPUs since the 80s?](https://danluu.com/new-cpu-features/)
- [ ] 💲[Casey Muratori - Performance-Aware Programming](https://www.computerenhance.com/i/99218768/performance-aware-programming-series)
- [ ] 💲[Digital Design and Computer Architecture](https://pages.hmc.edu/harris/ddca/)
- [ ] 💲[Computer Systems: A Programmer's Perspective](https://csapp.cs.cmu.edu/)

## Operating systems

- [x] [Operating Systems: Three Easy Pieces](http://pages.cs.wisc.edu/~remzi/OSTEP/)
- [ ] [CS612: Operating Systems and System Programming](https://cs162.org/) and [lectures](https://www.youtube.com/playlist?list=PLF2K2xZjNEf97A_uBCwEl61sdxWVP7VWC)
- [ ] [xv6, a simple Unix-like teaching operating system (MIT course)](https://pdos.csail.mit.edu/6.1810/2024/xv6.html)
- [ ] [Lions' Commentary on UNIX 6th Edition](https://cs3210.cc.gatech.edu/r/unix6.pdf) and [source code](https://warsus.github.io/lions-/)

## Linux / command line

- [ ] [Linux Journey](https://linuxjourney.com/)
- [ ] [Sundeep Agarwal - Linux Command Line Computing](https://learnbyexample.github.io/cli-computing/)
- [ ] [The Linux Command Line](https://linuxcommand.org/tlcl.php)
- [ ] [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line)
- [ ] [Sundeep Agarwal - "Linux CLI and shell scripting" list](https://learnbyexample.github.io/curated_resources/linux_cli_scripting.html)
- [ ] [Julia Evans - Your Linux Toolbox](https://jvns.ca/blog/2019/10/21/print-collection-of-my-first-7-zines/)
- [ ] 💲[Efficient Linux at the Command Line](https://www.oreilly.com/library/view/efficient-linux-at/9781098113391)
- [ ] 💲[How Linux Works](https://nostarch.com/howlinuxworks3)
- [ ] 💲[Julia Evans - Bite Size zine pack](https://wizardzines.com/zines/bite-size-pack/)
- [ ] 💲[Wicked Cool Shell Scripts](https://nostarch.com/wcss2)

<!-- "learn terminal" for kids:
https://github.com/KanoComputing/terminal-quest
https://web.mit.edu/mprat/Public/web/Terminus/Web/main.html
https://github.com/veltman/clmystery
https://overthewire.org/wargames/
-->

<!-- examples of terminal-based games:
https://github.com/vattam/BSDGames/
https://ascii-patrol.com/
https://a-nikolaev.github.io/curseofwar/
-->

## Concurrency / distributed systems

- [ ] 💲[Foundations of Scalable Systems](https://www.oreilly.com/library/view/foundations-of-scalable/9781098106058/)
- [ ] [Is Parallel Programming Hard, And, If So, What Can You Do About It?](https://arxiv.org/abs/1701.00854)
- [ ] [Distributed Systems](https://www.distributed-systems.net/index.php/books/ds4/)
- [ ] [On Transactional Concurrency Control](https://link.springer.com/book/10.1007/978-3-031-01873-2)
- [ ] [Gossip Glomers (distibuted systems challenges)](https://fly.io/dist-sys/)

## Database internals

### Database readings

- [ ] [How does a relational database work?](https://web.archive.org/web/20230307091314/http://coding-geek.com/how-databases-work/)
- [ ] [CS186: Introduction to Database Systems](https://cs186berkeley.net/) and [lectures](https://archive.org/details/ucberkeley-webcast-PL-XXv-cvA_iBVK2QzAV-R7NMA1ZkaiR2y)
- [ ] [Architecture of a Database System](https://dsf.berkeley.edu/papers/fntdb07-architecture.pdf)
- [ ] 💲[Database Internals](https://www.databass.dev/)
- [ ] [Transaction Processing](https://archive.org/details/transactionproce0000gray/page/n5/mode/2up)
- [ ] [Readings in Database Systems](http://www.redbook.io/)
- [ ] [PGTune](https://pgtune.leopard.in.ua/)

#### PostgreSQL

- [ ] [Postgres Playground](https://www.crunchydata.com/developers/tutorials)
- [ ] [Yeah, Postgres can do that](https://dev.to/efertsch/series/20415)
- [ ] [Introduction to PostgreSQL Indexes](https://dlt.github.io/blog/posts/introduction-to-postgresql-indexes/)
- [ ] [The Internals of PostgreSQL](https://www.interdb.jp/pg/)
- [ ] [PostgreSQL docs](https://www.postgresql.org/docs/current/)
- [ ] 💲[The Art of PostgreSQL](https://theartofpostgresql.com/)
- [ ] 💲[PostgreSQL Query Optimization: The Ultimate Guide to Building Efficient Queries](https://link.springer.com/book/10.1007/978-1-4842-6885-8)

### Database exercises

- [ ] 💲[Build a Database Server](https://technicaldeft.com/build-a-database-server)
- [ ] 💲[Build Your Own Database From Scratch in Go](https://leanpub.com/build_your_own_database_from_scratch/)
- [ ] [Build Your Own Redis with C/C++](https://build-your-own.org/redis/)
- [ ] [Build Redis from scratch](https://www.build-redis-from-scratch.dev) <!-- https://logowik.com/content/uploads/images/redis.jpg -->
<!-- Related: [Build Your Own Redis Server](https://codingchallenges.fyi/challenges/challenge-redis/), [Build Your Own Redis CLI Tool](https://codingchallenges.fyi/challenges/challenge-redis-cli/), [Build Your Own Fast, Persistent KV Store](https://dineshgowda.com/posts/build-your-own-persistent-kv-store/), [Build Your Own Redis (incomplete)](https://rohitpaulk.com/articles/redis-0), [Rebuilding Redis in Ruby (incomplete)](https://redis.pjam.me/) -->

## Compilers

- [ ] [Destroy All Software - A Compiler from Scratch](https://www.destroyallsoftware.com/screencasts/catalog/a-compiler-from-scratch)
- [ ] [Writing a compiler in Ruby, bottom up](https://hokstad.com/compiler) and related resources at the bottom of that page
- [ ] [Let's make a Teeny Tiny compiler](https://austinhenley.com/blog/teenytinycompiler1.html)
- [ ] [Stanford: SOE-YCSCS1 Compilers](https://online.stanford.edu/courses/soe-ycscs1-compilers)
- [ ] [Structure and Interpretation of Computer Programs](https://sarabander.github.io/sicp/)
- [ ] 💲[Crafting Interpreters](https://craftinginterpreters.com/)
- [ ] 💲[Build Your Own Compiler from Scratch](https://build-your-own.org/compiler/)
- [ ] 💲[Writing a C Compiler](https://nostarch.com/writing-c-compiler)
- [ ] 💲[Engineering a Compiler](https://shop.elsevier.com/books/engineering-a-compiler/cooper/978-0-12-815412-0)
- [ ] 💲[Writing an Interpreter in Go](https://interpreterbook.com/)
- [ ] 💲[Writing a Compiler in Go](https://compilerbook.com/)

## Math / logic

- [ ] 💲[Logic for Programmers](https://leanpub.com/logic)
- [ ] 💲[Math for Programming](https://nostarch.com/math-programming)
- [ ] 💲[Concrete Mathematics: A Foundation for Computer Science](https://www.pearson.com/en-us/subject-catalog/p/concrete-mathematics-a-foundation-for-computer-science/P200000000288/9780201558029)
- [ ] 💲[Coding The Matrix: Linear Algebra Through Computer Science Applications](https://codingthematrix.com/)

## Data structures and algorithms

### Textbooks / courses

- [x] 💲[Data Structures and Algorithms in Java](https://www.amazon.com/Data-Structures-Algorithms-Java-2nd/dp/0672324539) along with [VisuAlgo](https://visualgo.net/en)
  - [ ] Maybe this instead: 💲[A Common-Sense Guide to Data Structures and Algorithms](https://pragprog.com/titles/jwdsal2/a-common-sense-guide-to-data-structures-and-algorithms-second-edition/)
  - [ ] Or: 💲[Algorithms Unlocked](https://mitpress.mit.edu/9780262518802/algorithms-unlocked/)
- [ ] [Algorithmic Thinking](https://nostarch.com/algorithmic-thinking-2nd-edition) (examples in C)
- [ ] [Data Structures and Algorithm Analysis in C](https://www.amazon.com/dp/0201498405)
- [ ] [Codeintuition](https://www.codeintuition.io/)
- [ ] 💲[Practical Analysis of Algorithms](https://link.springer.com/book/10.1007/978-3-319-09888-3)
- [ ] 💲[The Algorithm Design Manual](https://www.algorist.com/) plus [lecture videos](https://www3.cs.stonybrook.edu/~skiena/373/videos/)
- [ ] 💲[Algorithm Design](https://www.cs.princeton.edu/~wayne/kleinberg-tardos/)
  - [ ] Maybe this instead: 💲[Algorithms](https://algs4.cs.princeton.edu/home/)
  - [ ] Or: 💲[Introduction to Algorithms](http://mitpress.mit.edu/9780262046305/introduction-to-algorithms/)
- [ ] [Start Doing Graph Theory](https://vertex.degree/)

### Interview guides

- [ ] [Tech Interview Handbook](https://www.techinterviewhandbook.org/algorithms/study-cheatsheet/)
- [ ] 💲[Beyond Cracking the Coding Interview](https://www.beyondctci.com/) (preview csolutions for free at [interviewing.io](https://start.interviewing.io))
- [ ] 💲[Elements of Programming Interviews](https://elementsofprogramminginterviews.com/)

### LeetCode

- [ ] Ruby solutions: [1](https://github.com/ACEMerlin/leetcode-ruby), [2](https://github.com/remy727/leetcode), [3](https://github.com/ganeshskudva/Leetcode-Ruby), [4](https://github.com/acearth/LeetCodePractice), [5](https://github.com/catluri/Leetcode-Ruby)
- [ ] [Algorithms Ruby gem](https://github.com/kanwei/algorithms) that is [included in the LeetCode environment](https://support.leetcode.com/hc/en-us/articles/360011833974-What-are-the-environments-for-the-programming-languages).
- [ ] [NeetCode 250](https://neetcode.io/practice?tab=neetcode250)
- [ ] [Grind75](https://www.techinterviewhandbook.org/grind75)
- [ ] [14 Patterns to Ace Any Coding Interview Question](https://hackernoon.com/14-patterns-to-ace-any-coding-interview-question-c5bb3357f6ed)
- [ ] [20 Essential Coding Patterns to Ace Your Next Coding Interview](https://dev.to/arslan_ah/20-essential-coding-patterns-to-ace-your-next-coding-interview-32a3)
- [ ] [Coding Interview Patterns](https://dvpr.gitbook.io/coding-interview-patterns)
- [ ] [AlgoMonster - Patterns](https://algo.monster/problems/stats)
- [ ] [LeetCode Patterns](https://seanprashad.com/leetcode-patterns/)
- [ ] 💲[Grokking the Coding Interview: Patterns for Coding Questions](https://www.designgurus.io/course/grokking-the-coding-interview)
- [ ] [An interview algorithms tier list](https://www.reddit.com/r/leetcode/comments/u7452n/technical_interview_algorithms_the_tier_list/)
- [ ] [Another algorithms tier list](https://www.reddit.com/r/cscareerquestions/comments/v1unyi/tier_list_for_patterns_encountered_in/)
- [ ] Other resource lists: [1](https://github.com/jwasham/coding-interview-university), [2](https://github.com/armankhondker/best-leetcode-resources), [3](https://github.com/mxssl/sre-interview-prep-guide#big-o-notation-algorithms-and-data-structures)

## Software architecture

- [ ] [Fundamentals of Software Architecture](https://www.oreilly.com/library/view/fundamentals-of-software/9781098175504)
- [ ] [The Architecture of Open Source Applications](https://aosabook.org/)

## Performance

- [ ] [Mature Optimization Handbook](https://carlos.bueno.org/optimization/)
- [ ] 💲[Systems Performance](https://www.brendangregg.com/systems-performance-2nd-edition-book.html)

## Low-level programming

### C

See my list [Learn C](https://github.com/fpsvogel/learn-c).

### Zig

- [x] [Ziglings](https://codeberg.org/ziglings/exercises#ziglings)
- [ ] [Zen of Zig](https://zenofzig.com/)
- [ ] [zig.guide](https://zig.guide)
- [x] [Learning Zig](https://www.openmymind.net/learning_zig/)
- [ ] [Introduction to Zig: a project-based book](https://pedropark99.github.io/zig-book)
- [ ] [Zig Cookbook](https://github.com/zigcc/zig-cookbook)
- [ ] 💲[Systems Programming with Zig](https://www.manning.com/books/systems-programming-with-zig)
- [ ] [Working with Strings in Zig](https://pmbanugo.me/blog/zig-working-with-strings)
- [ ] [Karl Seguin's blog](https://www.openmymind.net/)
- [ ] Look into other "better C" languages besides Zig: [Odin](https://odin-lang.org/), [Beef](https://www.beeflang.org/), [V](https://vlang.io/), [Jai](https://github.com/Jai-Community/Jai-Community-Library/wiki), [C3](https://c3-lang.org/), [MiniLang](https://github.com/NICUP14/MiniLang), and [others](https://github.com/robertmuth/awesome-low-level-programming-languages) (minus the C++ replacements like Rust, which are too complex for my purposes)

### Implement a Forth

- [ ] [Starting FORTH](https://www.forth.com/starting-forth/) or [Easy Forth](https://skilldrick.github.io/easyforth/)
- [ ] [Thinking Forth](https://thinking-forth.sourceforge.net/)
- [ ] [Implementing a Forth](https://ratfactor.com/forth/implementing)
- [ ] Minimal FORTH interpreters: [1](https://news.ycombinator.com/item?id=44193519), [2](https://www.reddit.com/r/Forth/comments/229sl5/comment/cgt6i5p/)
- [ ] [Fitting a Forth in 512 bytes](https://compilercrim.es/bootstrap/miniforth/)
- [ ] [Design Decisions in the Forth Kernel](https://www.bradrodriguez.com/papers/moving1.htm)
- [ ] [Threaded Interpretive Languages: Their Design and Implementation](https://archive.org/details/R.G.LoeligerThreadedInterpretiveLanguagesTheirDesignAndImplementationByteBooks1981)
- [ ] [Factor](https://factorcode.org/) if I want to explore a "high-level FORTH"
