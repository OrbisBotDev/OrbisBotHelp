
# How To Roll With OrbisBot

## Prefixes
A prefix is a character or characters that must be inluded immediately before a command for the bot to notice it. There should not be any whitespace  between the prefix and the command unless it is part of the prefix.

For OrbisBot you can use any of the following:
> `/`, `?`, `Please      `, `Please `

For example `/roll 1d6` or `Please Roll 1d6` would both call the `Roll` command.

## Basic Rolls
* Dice rolls should be prefaced with `/Roll` or `/r`. 
* Not including a command causes the default values to be used 
* Not including a dice will automaticaly roll `1D6` as your dice. 
* Including Additions without a dice will instead count as a cantrip and not make a roll

### Dice
>Standard `XdY` format, with `X` being the number of dice to roll and `Y` being the number of faces on those dice

### Comments
>Anything after a `~` symbol will be treated as a comment

### Crits
>`cX` with `X` being the crit depth, **-1** will cause unlimited crits, Not including this causes crits to default to **0**

### Crit Threshold
>To cause your dice to crit on a number other than the hightest face number use `cX(Y)`, with `Y` being your new crit face.

### Leverage
>`lX`, with `X` being your leverage

### Addition
>`+X` or `-X`, with `X` being a number to add/subtract from your final roll, you can add multiple numbers

### Explosion
>`eX` where `X` is the number of dice to add when you crit. 
>*Each of these dice can crit and will also explode with `X` additional dice.*


### _Example_

```
Please Roll 2D6 C2(5) L-1 E1 +3 ~ Example roll
```

This will roll 2 dice with 6 faces and 1 additional die as negative leverage, with a possible 2 crits that can occur on a 5 or 6 and adds an additional dice on each, finally adding 3 when the rolls are completed


## Complex Rolls

## Other Roll Commands

### Choose
