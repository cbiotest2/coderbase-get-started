---
title: Classes in Ruby
languages: ruby, rails
draft: false
summary: Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore, dicta ipsum facere quibusdam laudantium quod neque fugiat vitae illum iste.
---

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore, dicta ipsum facere quibusdam laudantium quod neque fugiat vitae illum iste.

> Lorem ipsum dolor sit amet, consectetur adipisicing elit. Fugiat, quidem.

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quis, in, distinctio, aliquid, incidunt ad soluta ut commodi recusandae corrupti dolor sint numquam consequatur a nobis et repellat sunt placeat quisquam ex eos dolore unde animi beatae nemo tempora fugiat aperiam debitis eaque iure id cumque enim ducimus itaque.

```ruby
require "English"
require "safe_yaml"
class Post < ActiveRecord::Base

  attr_accessor :tags_string

  belongs_to :user, :inverse_of => :posts

  belongs_to :repository

  before_save :set_datetime
  before_save :convert_markdown

end
```

Velit, neque aliquam commodi provident necessitatibus amet accusamus ab nostrum eum quod.

