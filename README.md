
# Intro
Dark Discord theme originally created by SolFi#0001
Hue based off a color wheel, Saturation for a shade gray (0%) to the full color(100%) from hue, and Lightness is the amount of light the color has 0% for black, 100% for white.
This theme is a rewite of the original to provide the user with a lot of more variables to change the difference in colours or to keep a monotone of a particular color.
A [guide](https://github.com/Asteria5675/BetterDiscordThemes/blob/master/null/README.md/#Visual-Guides) on editing the variables of null.

## Dark Discord Preview
![Dark Discord](https://github.com/SkyeX9/Dark-Discord/blob/main/Screenshots/Discord_5JgBkb6tqg.png)

### Main Variables
Main Variables - variables in theme file
```css
  --hue: 217 ;
  --saturation: 0% ;
  --lightness: 15% ;
  --alpha: 1 ;
```
`--hue` is the hue, `--saturation` is saturation(%), `--lightness` is the amount of light(%)
  Hue values are based off a degree of the color wheel so 0 is red, 120 is green, 240 is blue (Note: RGB and Hex can be converted in to hsl)
  Saturation is the shade of gray so 0% is gray while 100% is the full color
  Lightness is the light of the color 0% is black while 100% is white
  
  Saturation should remain under a value of 40% to avoid any visual problems especially lightness being under 20%.
  `--alpha` is the alpha/opacity of the color, only change the value as decimal (ex. 0.25) if you desire a change of transparency

If you desire a brighter colour and or brighter image when using transparency then its adivsed you copy all of `.theme-dark` and the variables (EXCEPT `--text-normal` and `--text-muted`) and paste it at the bottom of the file and rename `.theme-dark` to `.theme-light`. If you do not understand this part then you are better off with another theme

## Addition Variables
these variables are the addition / multiplication to mimic the style of the colour palette of discord original dark theme.
`--hue-addition` is initially set at `0` changing this value will change the hue/color on certain elements, `--saturation-addition` alters certain elements' saturation, `--lightness-addition`  alters certain elements' lightness, `--alpha-addition` used to addon certain element opacity only if altering null for a transparent theme. `--multiplier` is also tied to these variables in certain area if you want to remove the multiplier then set its value to `1`

addition variables can also be a negative intergers (ex `--saturation-addition: -6%;`) to give a darker contrast.

## Accents
accents, tooltips, mentions, etc.
`--accent` is the accent colout that applies to many regions such as pings, notification dots, blurple elements( discord blue). Users may revert the changes back as in file provide defaults to revert all are variables; however, it may be better to alter Dark Null if you desire the least changes of accents.

`--tooltip-background`,  `--blurple`,`--is-mention`, `--is-mention-bg`, `--unread`, and `--guild-selected` all use the variable `--accent` 

```css
--channel-selected: linear-gradient(6deg, var(--channel-gradient-prim),  var(--channel-gradient-sec),  var(--channel-gradient-tri));
```
was setup as background image gradient user may delete the whole gradient and replace it if they desire back to the normal channel modifier ex: 
```css
--channel-selected: var(--background-modifier-selected);
```

## Final Notes
please read this readme to fully understand the countless possibilities of altering this theme.

Speaking of making these themes for free if you really wanted to donate to me so I can live off another energy drink or two, then request the donate link enough on my server and I might make one who knows. I prefer not to advertise such though :)

## Readme
once again, it's called a `readme` for a reason. If you cannot understand anything from here, then you are better off with another theme.
