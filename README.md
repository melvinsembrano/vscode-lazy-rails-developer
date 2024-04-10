# Lazy Rails Developer

The Lazy Rails Developer extension is a collection of useful snippets specifically designed for Ruby on Rails developers. With this extension, you can quickly and easily insert commonly used code snippets into your projects, saving you time and effort.

## Snippets binding

### Ruby

`class`, `cla` - New Ruby class.
```ruby
class $1
  def initialize
    $0
  end
end
```

`begin`, `beg` - New Ruby begin block.
```ruby
begin
  $0
end
```

`begin`, `begr` - New Ruby begin block with rescue.
```ruby
begin
  $0
rescue $1
end
```

`begin`, `begrn` - New Ruby begin block with rescue and ensure.
```ruby
begin
  $0
rescue $1
ensure
end
```

`module`, `mod` - New Ruby module.
```ruby
module $1
  def $2
    $0
  end
end
```

`while`, `wh` - New Ruby while loop
```ruby
while $1
  $0
end
```