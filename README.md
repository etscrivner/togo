# togo

Safe control flow as a service.

## Usage

```ruby
frame_start

label(:a) { print "hello"; goto :b }
label(:b) { print "world"; goto :c }

label(:c)

frame_end
```
