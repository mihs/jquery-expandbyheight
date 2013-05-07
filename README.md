jquery-expandbyheight
=====================

jQuery plugin that expands or collapses an element by looking at its HEIGHT, not number of characters.

# Usage #

```javascript
$(".text").expandByHeight({
  expandText: "read more",
  collapseText: "read less",
  maxHeight: 500,
  afterExpand: function() {
    console.log("Expanded!")
  },
  afterCollapse: function() {
    console.log("Collapsed!")
  }
})
```

# Credits #

* http://stackoverflow.com/questions/11408311/use-jquery-to-expand-collapse-text
* https://github.com/kswedberg/jquery-expander
