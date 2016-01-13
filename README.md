# Sailor's Design
Documents and discussions about the design of Sailor

##FAQ

### What is the purpose of this repository?

We wish for Sailor not only to have open source but open development. The participation of the community and its contribution on deciding the future of Sailor is essential to us. This repository will be useful to store documents (markdown files) and discussions (issues) about Sailor's design process.

### What is the ultimate goal of Sailor?

Get Lua in the scene of web developments, through Sailor or not. We believe Lua is a better quality alternative to current popular languages used in web development such as PHP, Ruby, Python and Javascript. Lua should at least come to mind when discussing options. We intend to do that by fixing the single most important drawback of Lua, the small ecosystem, by providing more tools to enable fast and easy web development. This is why we support the use of [LuaRocks](http://luarocks.org), the Lua package manager.

### What is the future goal of Sailor?

Have a solid and extensible product, allowing community members to upload & install their plugins and extensions, a fruitful community, and make the development of a web application in Sailor very easy and fast.

### What is the very-near-future goal of Sailor?

Have a minimum viable product that is production ready, specially on its use within Nginx, release a version 1.0 and get users within the Lua community.

### Why use Lua in web development?

* The Lua programming language is a high-quality programming language on its design and semantics. It is very concise, consistent and predictable. It is very readable. It has great mechanisms such as metatable and hybrid implementation of tables. It's a wonderful piece of well-maintained tech. It's really worth the time to read some of the papers about it and we believe it is a better alternative than other popular interpreted languages currently being frequently used for web developments

* Performance. Lua is faster than other cousin languages of the same family. It's the fastest interpreted language i've heard of. The JIT implementation of Lua is faster than JS v8.

* Good technology such as openresty. Openresty is a bundle of nginx modules. Nginx implementation uses LuaJIT, which is super fast, and it has this interesting thing which is dealing with asynchronous I/O internally. So you can write seemingly procedural code that will be non-blocking and the events will all be handled inside nginx. That means **no callback hell**.

* I particularly find it a very pleasant language to work with and it ranks my top 1 in this "category" at the moment. People often underestimate the importance of this for work. This is specially good considering it's high quality tech. I used to find PHP more pleasant to work with than Java despite Java being a more well-put language, but then I needed to give excuses and it was awkward because it seemed like I didn't understand its drawbacks... Most of the time we don't need technical reasons to just enjoy a tool and it feels nice for me in the Lua world and like something I can defend technically. This also pushed me to learn more about prog lang design, which was nice.

* It's not new or weird to use Lua for web dev, despite what we think, websites like taobao.com, which is something like the chinese ebay, which is world's 11th most visited website, according to alexa, uses Lua in critical chunks of their code base. Lua is top 1 on the west for game dev scripting, but it is used for web dev more extensively on china. I guess they really need the performance?

* I'd go as far as to say it is the future of webdev, but that's my "big dream". We need more developers building tools in Lua for that first, and Lua's community is not very big, so I'm not sure how that'll go! x)

* Lua's community has bunchs of nice, helpful and incredibly smart people despite being small. It is a friendly environment that cares about people and I often appreciate the high level technical discussions that emerge at the Lua email list. If you'd like to build tools for development, it's an easy way to get the community's heart without being redundant and gain prominency on your career. Nobody needs another MVC PHP framework. But the Lua community does not have the same abundance of tools. So you can build whatever you want that Lua does not have many of and lots of people will be happy. Of course this is a drawback at the same time. This is discussed in the next section. My point is that it might be better for career to be a prominent member of the Lua community and build tools that will be relevant not only for the Lua people, but at a broader scale since Lua itself can be the positive differential from similar tools.


### Why not use Lua in web development?

* The small & scattered ecosystem will often force you to develop libraries from scratch. I'd say this is the single most important drawback. However, this is changing a lot with the recent improvements to LuaRocks and this is also what we aim to change with Sailor. So I'd say this is a good time to get started and get the community's love first and then build a product ;) Or you can do like Leaf, the person who develops MoonScript (a language that compiles to Lua like coffeescript to JS) and do both, he has a big indie game shop which he developed using the tools he made!

* The community is small and you might not always find the help you look for. However, Lua is easy and clair enough for you not to need help all the time, though. And we are very nice helpful folks. :)
