# die roll quiz answers

Create a die when the BBC micro:bit is shaken 

These are the answers to the [die roll quiz](/microbit/lessons/die-roll/quiz).

## 1. Create a variable named 'roll' that will be randomly assigned to a number between 0 and 5.

<br/>

```
let roll = Math.random(6)
```

## 2. If the variable "roll" equals 5, write the code that will plot the image below

![](/static/mb/lessons/die-roll-0.png)

<br/>

```
if (roll == 5) {
    basic.plotImage(`
. # . # .
. . . . .
. # . # .
. . . . .
. # . # .
`)
}
```

## 3. You will use an `else if` condition if "roll" is equal 4. Write the `else if` statement that will display the plot image below

![](/static/mb/lessons/die-roll-1.png)

<br />

```
if (roll == 5) {
    basic.plotImage(`
. # . # .
. . . . .
. # . # .
. . . . .
. # . # .
`)
} else if (roll == 4) {
    basic.plotImage(`
. . . . .
. # . # .
. . # . .
. # . # .
. . . . .
`)
}
```

Note: students are only required to write the bottom half of this answer, starting with "else if".

## 4. You will use an `else if` condition if "roll" is equal 3. Write the `else if` statement that will display the plot image below

![](/static/mb/lessons/die-roll-2.png)

<br />

```
if (roll == 4) {
    basic.plotImage(`
. . . . .
. # . # .
. . # . .
. # . # .
. . . . .
`)
} else if (roll == 3) {
    basic.plotImage(`
. . . . .
. # . # .
. . . . .
. # . # .
. . . . .
`)
}
```

Note: students are only required to write the bottom half of this answer, starting with "else if".

## 5. You will use an `else if` condition if "roll" is equal 2. Write the `else if` that will display the image below

![](/static/mb/lessons/die-roll-3.png)

<br />

```
if (roll == 3) {
    basic.plotImage(`
. . . . .
. # . # .
. . . . .
. # . # .
. . . . .
`)
} else if (roll == 2) {
    basic.plotImage(`
# . . . .
. . . . .
. . # . .
. . . . .
. . . . #
`)
}
```

Note: students are only required to write the bottom half of this answer, starting with "else if".
