# Ruby Debugger Documentation

## Description

The following documentation outlines how to use a Ruby Debugger.

## Debug Ruby with Byebug

The following outlines how to debug Ruby with Byebug, see Byebug Github repo for more information https://github.com/deivid-rodriguez/byebug.

First, we need to install `byebug` in our terminal with:

```
sudo gem install byebug
```

To use this debugger in say a Fastlane plugin, we will need to add the following to a `Gemfile`.

```ruby
gem "byebug"
```

Then add the following to any Ruby file, where we want to use `byebug` to debug.

```ruby
require 'byebug'
```

Simply include byebug wherever we want to start debugging and the execution will stop there.

```ruby
byebug
```

Here are some `byebug` commands:

- type `s` for `step`

- type `sk` for `skip`

- type `v all` for `var all`

- type `v local` for `var local`

-  type `c` or `cont` for `continue`

Let's say we have a variable `num` when we type `num`, it will display the current value of that variable in the Ruby script.