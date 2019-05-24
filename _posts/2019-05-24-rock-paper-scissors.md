---
layout: post
title:  "Rock Paper Scissors"
date:   2014-05-24
categories: general
---

Following a tutorial, made this little "Rock Paper Scissors" watch game.

![whatisthis](/images/2019-05-24-rock-paper-scissors.png)

Few things I learned:
* Syntax different for same things between iOS and watchOS (example below)
* watchOS syntax seems slightly cleaner
* Basic timers are super easy in watchOS!
* How to use "Groups" to nest objects next to eachother
* How to use "relative to screen" sizes effectively for flexible layout


One example of syntax difference...

iOS:
```
myElement.isHidden = true
```

watchOS:
```
myElement.isHidden(true)
```

(minor difference; but watchOS exposes functions instead of attributes -- seems better this way)