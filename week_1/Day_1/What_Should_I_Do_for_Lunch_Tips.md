### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
const whatToDoForLunch = function(hungry, availableTime) {

  if (hungry === true) {

    if (availableTime < 20) {

      console.log("grab some lunch and eat it with your cohort pals");

    } else if (20 <= availableTime && availableTime <= 30) {

      console.log("You deserve a break! Go out and try a place in Gastown");

    } else if (availableTime > 30) {

      console.log("you should probably spend that time doing bootcamp things!");

    }

  } else  {

    console.log("You should probably wait until you're hungry!");

  }
};

```