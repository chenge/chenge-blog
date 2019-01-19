---
title: 有趣地寻找Ruby方法
date: '2019-01-20'
---

通常我们会从文档找，但这个比较低效和无聊。

suggest gem提供了一个新颖的方式。

```ruby
require 'suggest'

# Object#what_returns? tells you which method returns the value
[1,2,3].what_returns? 1
=> [:first, :min]
```

怎么样，不错吧。