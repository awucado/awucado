# Learning Rust
[Getting Started + Installation](https://www.rust-lang.org/learn/get-started) | [Cheat Sheet](https://cheats.rs/)

## Table of Contents
1. [How Do I Start Learning Rust?!](https://gist.github.com/noxasaxon/7bf5ebf930e281529161e51cd221cf8a#how-do-i-start-learning-rust)
2. [Ok, I Think I Know The Basics But How Do I Get Better?!](https://gist.github.com/noxasaxon/7bf5ebf930e281529161e51cd221cf8a#ok-i-think-i-know-the-basics-but-how-do-i-get-better)
3. [Rustlang Tooling](https://gist.github.com/noxasaxon/7bf5ebf930e281529161e51cd221cf8a#rustlang-tooling)
4. [Helpful References Throughout Your Journey](https://gist.github.com/noxasaxon/7bf5ebf930e281529161e51cd221cf8a#helpful-references-throughout-your-journey)
5. [The Rust Community](https://gist.github.com/noxasaxon/7bf5ebf930e281529161e51cd221cf8a#the-rust-community)
6. [Recommended (but not free) Books & Courses](https://gist.github.com/noxasaxon/7bf5ebf930e281529161e51cd221cf8a#recommended-but-not-free-books--courses)

## How Do I Start Learning Rust?!
### by Reading
 - [**The Book**](https://doc.rust-lang.org/book/): start reading now, read it whenever you can, and don't worry if it takes a long time to get through. You will reference it for most of your time using Rust. or try the [Rust Book with Quizzes](https://rust-book.cs.brown.edu/experiment-intro.html)
   > Affectionately nicknamed “the book,” The Rust Programming Language will give you an overview of the language from first principles. You’ll build a few projects along the way, and by the end, you’ll have a solid grasp of the language.
 - [**Rust By Example**](https://doc.rust-lang.org/stable/rust-by-example/index.html): like 'The Book', with less docs and more sample code
   > If reading multiple hundreds of pages about a language isn’t your style, then Rust By Example has you covered. While the book talks about code with a lot of words, RBE shows off a bunch of code, and keeps the talking to a minimum. It also includes exercises!"
 - (Blog) [Mental Models for Learning Rust. (`kerkour`)](https://kerkour.com/rust-mental-models)
 - (Blog) [A Half Hour to Learn Rust. (`fasterthanlime`)](https://fasterthanli.me/articles/a-half-hour-to-learn-rust)
 - (Blog Series) [Learn Rust the Dangerous Way (`cliffle`)](http://cliffle.com/p/dangerust/) "Rust features in context for low-level C programmers"
   > Existing Rust tutorials are great, but they focus on safe features. This companion tutorial takes an unsafe-first approach that may be more appealing for low-level systems programmers like me.
 

### by Watching
 - ["Learn Rust in One Video"](https://www.youtube.com/watch?v=ygL_xcavzQ4&t=2s) : highly rated video for learning rust concepts from scratch.
 - ["Going through the Rust Programming Book Live!"](https://www.youtube.com/watch?v=5QsEuoIt7JQ)

### by Doing
- [Tour of Rust](https://tourofrust.com/): Step-by-step interactive walkthrough of Rust, all in your browser.
- [**Rustlings**](https://github.com/rust-lang/rustlings): Rust by Example -style exercises you complete via your own local environment
  > Alternatively, Rustlings guides you through downloading and setting up the Rust toolchain, and teaches you the basics of reading and writing Rust syntax, on the command line. It's an alternative to Rust by Example that works with your own environment.
- [**Exercism.org**](https://exercism.org): Work through examples in order from "hello world!" to advanced concepts like Doubly-linked lists. Do work in the browser or via your local environment using the exercism CLI, with progress reflected in the web app. Get mentorship and guidance from real people.
  > We’re building a place where anyone can learn and master programming for free, without ever feeling lost or stupid. We're here to help everyone get really good at programming, regardless of their background. We want to share our love of programming, and help people upskill as part of their upward social mobility.
 - [Comprehensive Rust](https://google.github.io/comprehensive-rust/): From the Google Android team
   > This is a four day Rust course developed by the Android team. The course covers the full spectrum of Rust, from basic syntax to advanced topics like generics and error handling. It also includes Android-specific content on the last day.
The goal of the course is to teach you Rust. We assume you don’t know anything about Rust and hope to:
Give you a comprehensive understanding of the Rust syntax and language.
Enable you to modify existing programs and write new programs in Rust.
Show you common Rust idioms.


## Ok, I Think I Know The Basics But How Do I Get Better?!
### by Reading
- [The 'Typestate Pattern' in Rust (`cliffle`)](http://cliffle.com/blog/rust-typestate/)
- [Rust Design Patterns](https://rust-unofficial.github.io/patterns/)
- Design Patterns, in Rust (`refactoring.guru`)[Website](https://refactoring.guru/design-patterns/rust) | [Repo](https://github.com/fadeevab/design-patterns-rust)
- [Rust Types Trivia (`jonhoo`)](https://www.reddit.com/r/rust/comments/v4dnaj/twitter_thread_with_trivia_about_rust_types/)
- [Safely Writing Code That Isn't Thread Safe (`cliffle`)](http://cliffle.com/blog/not-thread-safe/)
- [Futures Concurrency III: (avoiding) `Select!` in Async Code](https://blog.yoshuawuyts.com/futures-concurrency-3/)

### by Watching
- [Crust of Rust (series) `jonhoo`](https://www.youtube.com/watch?v=rAl-9HwD858&list=PLqbS7AVVErFiWDOAVrPt7aYmnuuOLYvOa)

### by Doing
- [`whorl`](https://github.com/mgattozzi/whorl)
  > whorl was created to teach you how async executors work in Rust. It is not the fastest executor nor is it's API perfect, but it will teach you about them and how they work and where to get started if you wanted to make your own.
- [TP-201: Practical Networked Applications in Rust](https://github.com/pingcap/talent-plan/#series-2-rust-programming)
  > A series of projects that incrementally develop a single Rust project from the ground up into a high-performance, 
- https://github.com/dpc/sniper
  > Educational Rust implemenation of Auction Sniper from Growing Object-Oriented Software, Guided By Tests
networked, parallel and asynchronous key/value store. Along the way various real-world Rust development subject matter are explored and discussed.
- [Learn Video Codecs by Implementing one in 100 lines of Rust](https://blog.tempus-ex.com/hello-video-codec/)


## Rustlang Tooling
- **[Rust-Analyzer](https://rust-analyzer.github.io/manual.html#installation)**: An incredible IDE plugin for the rust language. plugin links: [vscode](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer), [vim](https://github.com/rust-lang/rust.vim)
- [The Rust Playground: run and share rust snippets in the browser](https://play.rust-lang.org/?version=stable&mode=debug&edition=2021)


## Helpful References Throughout Your Journey 
- [**The Book**](https://doc.rust-lang.org/book/)
- [Rust Design Patterns](https://rust-unofficial.github.io/patterns/)
- [Rust Cheat Sheet](https://cheats.rs)


## The Rust Community
- [Rust subreddit](https://www.reddit.com/r/rust/)
- [Rust community forum](https://users.rust-lang.org/)
- [Rust Community Discord](https://discord.gg/rust-lang)


## Recommended (but not free) Books & Courses
### Beginner
- 📘 [Beginning Rust From Novice to Professional (O'Reilly)](https://www.oreilly.com/library/view/beginning-rust-from/9781484234686/)
- 👩‍🎓 [Rust Adventure `chrisbiscardi`](https://www.rustadventure.dev/)
- 📘/👩‍🎓 [Learn Rust in a Month of Lunches (Manning, Macleod)](https://www.manning.com/books/learn-rust-in-a-month-of-lunches)
- 📘 [Zero to Production in Rust `luca palmieri`](https://www.zero2prod.com/)
- 📘/👩‍🎓 ~$30 - [Rust In Motion (Manning)](https://www.manning.com/livevideo/rust-in-motion): From creators of The Book, a video walkthrough  + interactive transcript for BRAND NEW Rustaceans that goes over critical concepts
- 👩‍🎓 $129 - [Rust for Javascript Developers](https://rustforjs.dev/)

### Intermediate
- 📘 [Programming Rust (O'Reilly)](https://www.oreilly.com/library/view/programming-rust-2nd/9781492052586/)
- 📘 ~$35 - [Rust In Action](https://www.manning.com/books/rust-in-action)
- 📘 ~$30 - [Rust for Rustaceans (nostarch press)](https://nostarch.com/rust-rustaceans)
