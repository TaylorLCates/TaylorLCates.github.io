---
layout: post
title: Boolean Operators
--- 

Bootcamp today was all over the place! In a good way, mind you. 

We started off with our kihones drill and it was definitely easier to complete than yesterday. I think understanding how the unit tests wanted the answers helped a lot. After that, we did our trust huddle with an Improver from the marketing department that Tim snagged (I totally forgot her name, please don't hold it against me! I'll be sure to get it tomorrow!!) After that we did some directed work on our adventure game we're building and then broke for lunch. After lunch we returned for another kihones drill and it's starting to flow for most of us. Then we proceeded to more directed work and then at the end of the day Alex, our co-instructor for this week and on-hand Java expert went over different boolean types. Which brings us to today's homework: 

# Boolean Truth Tables 

| a     | b     | &     | &&    |   |   |  ||   | Xor   |
|-------|-------|-------|-------|-------|-------|-------|
| TRUE  | TRUE  | TRUE  | TRUE  | TRUE  | TRUE  | FALSE |
| FALSE | TRUE  | FALSE | FALSE | TRUE  | TRUE  | TRUE  |
| TRUE  | FALSE | FALSE | FALSE | TRUE  | TRUE  | TRUE  |
| FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | 

|       !       |
|-------|-------|
| TRUE  | FALSE |
| FALSE | TRUE  | 



I think these are correct. I understand that & and | are bitwise and look at the binary of what the variables are (1 being true, 0 being false) and that they really shine when you start comparing things with more than one digit place in binary. Example would be cmparing 0010 & 0110, only the second digit would show as true. But this subject is, as Tim and Alex were both saying today, very under the hood in regards to what we're being trained to do. Almost all modern languages keep you separated from the binary aspect for the most part, but it's still interesting to learn about. 

Definitely looking forward to tomorrow!
