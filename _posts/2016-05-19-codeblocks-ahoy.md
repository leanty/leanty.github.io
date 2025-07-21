---
layout: post
---

一篇包含各种高亮代码片段的文章。

```ruby
=begin
  嵌套在一个虚拟模块中的虚拟类
  私有API
=end
```
```diff
- 这一行已被删除
- 这一行已被删除
+ 这一行可见
+ 这一行已被插入
这一行没有被更改
```
```sass
@import "base"

.card
  display: inline-block
  margin: 0
  padding: 0

  &:hover
    color: #ab45ef;
```
```ruby
21 + 54 = 0
foo ||= bar
foo / bar

24
45.75
0x2C716
\x0A
01010

/ya?ml/
"yaml"
```
```ruby
include Enumerable

module Foo
  class Bar
    LIPSUM = "lorem ipsum dolor sit"

    attr_reader :layout

    def initialize
      @layout = Layout.new
    end

    # 实例方法
    def profile
      measure_time do
        compile layout
        layout.render_with Bar::LIPSUM
      end
    rescue ArgumentError
      false
    end
  end
end

# 执行代码
Foo::Bar.new.profile
```

{% raw %}
```liquid
{% assign foo = page.foo | bar: 'baz' %}
{{ foo }}
```
{% endraw %}

```yaml
author:
  admin: true
  name: John Doe
  email: johndoe@example.com
  id: 75636474
```

{% highlight html %}
<html>
  <head>
    <meta charset="utf-8" />
    <title>你好，世界</title>
  </head>
  <body>
    <p>你好，世界！</p>
  </body>
</html>
{% endhighlight %}

{% highlight html mark_lines="1 4 7" %}
<html>
  <head>
    <meta charset="utf-8" />
    <title>你好，世界</title>
  </head>
  <body>
    <p>你好，世界！</p>
  </body>
</html>
{% endhighlight %}

{% highlight html linenos %}
<html>
  <head>
    <meta charset="utf-8" />
    <title>你好，世界</title>
  </head>
  <body>
    <p>你好，世界！</p>
  </body>
</html>
{% endhighlight %}

{% highlight html linenos mark_lines="1 4 7" %}
<html>
  <head>
    <meta charset="utf-8" />
    <title>你好，世界</title>
  </head>
  <body>
    <p>你好，世界！</p>
  </body>
</html>
{% endhighlight %}

{% highlight python linenos%}
def greet()
  print("fku")
greet()
{% endhighlight %}