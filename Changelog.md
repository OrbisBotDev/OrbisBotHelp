# Changelog

## Version: 1.4.2  
 *2019-11-26--0239*
- changed the thing to be the thing

## Version: 1.4.1  
 *2019-11-17--2016*
- Catspam now has a config defined max ID and URL list length.
- Bot login message now includes a timestamp.
- Bot now has a 'playing' status which can be changed with the `status` command
- Admin functions moved to cogs.
- OrbisRoller now removes request message after responding.
- OrbisRoller session vars now loaded from a seperate config.

## Version: 1.4.0  
 *2019-11-04--2005*
- Cogs can now be reloaded without restarting the entire bot.
- CatSpam cog posts cats!

## Version: 1.3.1 
 *2019-09-27--0838*
- Numbered multirolls now parse more than the first digit.
- No longer able to have negative explosion dice or negative crits (excepting -1 for unlimited crits).
- Rolls with both explosions and crits have had greater limitations imposed to keep processing for any individual roll under 5 sesconds.
- Most other limits lowered to 99 to keep with the 5 sec target

## Version: 1.3.0 
 *2019-09-26--0613*
- Updated packages, minor cog inheritance fixes for updated discord package.
- Choose command added, seperate options with `|`.
- Multiple rolls in a single command, individual rolls within `[` and `]`. To roll the same roll multiple times use `[ xDy ] @n` where `n` is the number of rolls to make.

## Version: 1.2.0 
 *2019-02-03--2028*
- Explode dice can be set using `Ex` where **x** is the number of additional dice to add to the next roll for each crit dice. basically bountyhunter sneak attack crit dice.

## Version: 1.1.2  
 *2018-11-07--0000*
- whitespace, commas, and full stops in roll arguments are ignored.
- Comments are no longer parsed as roll argument input.
- `+/- X` for roll function arguments is no longer used as a total addition/subtraction as well.

## Version: 1.1.1  
 *2018-11-06--0231*
- Can roll a cantrip by not including a dice in the roll.
- Dynamically adds command_prefix into help posts.
- Can now `-` from a roll instead of only adding.
- Changelog now has push date.
- Converts data paths to absolute system paths to get them working on linux.

## Version: 1.1.0 
 *2018-11-03--0045*
 - Added a changelog.
- `changelog` command added to show most recent version changelog.
- Session variables are now loaded from a json config instead of being hard-coded.
- Added cogs to enable easy loading of new packages without changing anything other than the config.
- Bot loading is modular and extensible now.
- Requirements file added to note packages that need to be imported.

## Version: 1.0.0  
 *2018-10-22--0300*
- Basic bot functional

