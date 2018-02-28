Gives you the ability to easily watch the movement of certain players. Use this tool as you wish as it could be quite handy in certain situations

## Notes
- There may be momentary lag when starting the visuals for a players locations depending on your settings.

## Permissions
- `playertracker.admin` -- can use the features of this plugin.

## Chat Commands
- **/track <start | stop | show> \<playername | id\> \<length\>** -- using start will start tracking the player. using stop will stop tracking a player. using show will give a graphical display of the players travels.

## Configuration File
```
{
  "Arrow Settings": {
    "Arrow Head Size": 0.5,
    "Default Display Length": 120.0 - the default length of the draw if no length is defined
  },
  "Settings": {
    "Position Interval Time": 2.0, - Record the players position every x seconds (increase this to reduce lag)
    "Remove Entries after x seconds": 600.0, - Remove old positions after x seconds (decrease this to reduce lag when using /track)
    "Track All Players": false - if this is set  to true, this plugin will track every player on the server without having to manually /starttrack on certain players (this can increase lag)
  }
}
```
