---
tags: readme, concatenation
language: ruby
resources: 0
track: web development
topic: ruby
unit: string manipulation
lesson: interpolation
---

# String Concatenation

## Introduction

In Ruby, you can connect strings using a `+` sign. For instance, if you add "Hello" and " world!", you will get "Hello world!". Take a look at the example below:

```ruby
"Blink-" + "182"
# => "Blink-182"
```

## Incorporating a Variable

This also works for variables of strings. For instance, if `rapper` has a value of `"Lil' Romeo"`, then `rapper + " released an album called 'Romeoland' in 2004"` will return "Lil' Romeo released an album called 'Romeoland' in 2004". Take a look at the examples below:

Example 1
```ruby
artist = "Lou Bega"
artist + " is most famous for 'Mambo No. 5'"
# => "Lou Bega is most famous for 'Mambo No. 5'"
```
Example 2
```ruby
fact = "has sold 10 million albums worldwide"
"Hoobastank " + fact
# => "Hoobastank has sold 10 million albums worldwide"
```
Example 3
```ruby
artist = "t.A.T.u."
artist + " was a was a Russian music duo"
# => "t.A.T.u. was a Russian music duo"
```

## Incorporating Multiple Variables

Example 1
```ruby
given_name = "DeAndre Cortez Way"
stage_name = "Soulja Boy"
"Ice-T has criticized " + given_name + ", better known as " + stage_name + ", for killing hip-hop."
# => "Ice-T has criticized DeAndre Cortez Way, better known as Soulja Boy, for killing hip-hop."
```
Example 2
```ruby
band_name = "Crazy Town"
song_name = "Butterfly"
month = "November"
year = "2000"
band_name + " released their song " + song_name + " in " + month + " of " + year + "."
# => "Crazy Town released their song Butterfly in November of 2000."
```
