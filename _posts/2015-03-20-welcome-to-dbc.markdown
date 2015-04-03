---
layout: post
title:  "Welcome to DBC"
date:   2015-03-20
categories: dbc
---

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

{% highlight ruby %}
class GroceryList
  def initialize
    @list = Hash.new
  end
  
  def add_item(item, quantity=1)
    @list[item] = quantity
  end
  
  def remove_item(item)
        @list.delete(item)
        puts "Item Removed!"
  end
    
     def print_list
         @list.each  {|key, value| puts "we need #{value} #{key}" }
     end
end
{% endhighlight %}