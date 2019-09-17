### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces.

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```const whatToDoForLunch = function(hungry, availableTime) {
  if (hungry !== true) {
    console.log("Let`s get back to work!");
  } else if (availableTime < 20) {
    console.log("Let`s pick something up and eat it in the lab.");
  } else if (availableTime >= 20 && availableTime <= 30) {
    console.log("Let's try a place nearby.");
  } else if (availableTime > 30) {
    console.log("I'm in a bootcamp and be carefull about the time spare!");
  }
};
```
