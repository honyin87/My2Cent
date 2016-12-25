# jCalculator

:white_check_mark: jQuery plugin for calculator inputs

![Image of jCalculator](http://i.imgur.com/VODhXOc.png)


###```bower install jCalculator```

### To install follow the steps:
  
  - Include ```jQuery```
  - Include ```jcalculator.js``` and ```jcalculator.css```
  - Call ```$(selector).jCalculator({ /* your options here */ })```


### Options and methods


| Options  |  Type    |                                      Description                                      |
|----------|----------|---------------------------------------------------------------------------------------|
| theme    | string   | Available ```material```, ```light```, ```dark```. Default ```material```.                                    |
| onInput  | function | Callback function triggered when a button is clicked, send as parameter the ```$element```. |
| onResult | function | Callback function triggered when a calculation was made, send as parameter the ```result```.  |

# Changelog

  - Added callback methods
  - Added new themes
