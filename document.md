# A document.

This is a Markdown document.

* It
* Has
* A
* List

#### Python

```python

stuff = {i:i**2 for i in range(10) if i % 2}
print(stuff)
```
---
#### SQL

```sql

SELECT foo.x,
       bar.y
  FROM foo
  JOIN bar
    ON foo.bar_id = bar.id
 WHERE bar.y>10
```

---
#### Coffeescript


```coffeescript
class View extends Backbone.View
  render:=>
      @$el.html @template
          something:something
          ...
```
