#Javascript Concepts

let vs var:

var is scoped to the nearest function block whereas let is scoped to the nearest enclosing block and both are global if outside any block.

Here's a scenario where `let` is used

```javascript
function HelloWorld() {
  //div is not available here
  for (let div = 0; div < 5; div++) {
    //Insert some loop action on each div
    //div is only available within this enclosing block
  };
};
```

Here's an example where `var` is used:
```javascript
function changeShoeLaces() {
  //shoes is available here, within the function block.
  for (var shoes = 0; shoes < 10; shoes++) {
    //Do something to each shoe
    //shoes is available here
  }
}
```


Source: http://stackoverflow.com/questions/762011/let-keyword-vs-var-keyword
