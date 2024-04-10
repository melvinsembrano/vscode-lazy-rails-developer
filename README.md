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

`def` - New Ruby method.
```ruby
def $1
  $0
end
```

`def`, `sdef` - New Ruby singleton method
```ruby
def self.$1
  $0
end
```

`each`, `ea` - New Ruby inline each loop.
```ruby
each { |$1| $0 }
```

`each`, `eachb`, `eab` - New Ruby each loop block.
```ruby
each do |$1|
  $0
end
```

`flat_map`, `fmap` - New Ruby inline flat_map loop.
```ruby
flat_map { |$1| $0 }
```

`flat_map`, `fmapb` - New Ruby flat_map loop block.
```ruby
flat_map do |$1|
  $0
end
```

`find` - New Ruby inline find loop.
```ruby
find { |$1| $0 }
```

`findb` - New Ruby find loop block.
```ruby
find do |$1
  $0
end
```

`find`, `rfind`, `rf` - New ActiveRecord find.
```ruby
find($1)
```

`find_by`, `rfb` - New ActiveRecord find_by.
```ruby
find_by($1)
```

`for` - New Ruby for loop.
```ruby
for $1 in $2
  $0
end
```

`map` - New Ruby inline map loop.
```ruby
map { |$1| $0 }
```

`mapb` - New Ruby map loop block.
```ruby
map do |$1|
  $0
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

`select`, `sl` - New Ruby inline select loop.
```ruby
select { |$1| $0 }
```

`select`, `slb` - New Ruby select loop block.
```ruby
select do |$1|
  $0
end
```

`until`, `unt` - New Ruby until loop.
```ruby
until $1
  $0
end
```

`while`, `wh` - New Ruby while loop.
```ruby
while $1
  $0
end
```