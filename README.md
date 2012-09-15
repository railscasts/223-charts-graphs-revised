# RailsCasts Episode #223: Charts & Graphs (revised)

http://railscasts.com/episodes/223-charts-graphs-revised

Requires Ruby 1.9.2 or higher.


### Commands used in console

```ruby
Order.group("date(purchased_at)").select("purchased_at, sum(price) as total_price")
o = _
o.purchased_at
o.total_price
```
