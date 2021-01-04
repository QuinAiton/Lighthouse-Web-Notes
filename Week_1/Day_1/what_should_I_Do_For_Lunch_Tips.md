### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

``` javascript
const whatToDoForLunch = (hungry, availableTime) => {
  if (hungry) {
    if (availableTime < 20) {
      return 'Pick up something and eat it back in the lab or kitchen, so you can meet fellow classmates';
    } else if (availableTime >= 20 && availableTime < 30) {
      return 'you deserve a break. Maybe try something in gas town';
    } else {
      return 'you should reconsider, this is a bootcamp after all';
    }
  }
  return 'Wait untill your hungry';
};
```