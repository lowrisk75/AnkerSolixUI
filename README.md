# AnkerSolixUI

For the actual integration, you need to see the outstanding work from @thomluther here: https://github.com/thomluther/hacs-anker-solix (don't forget to star his work! (top right corner))

For this Picture Elements to work, you need to copy the background picture "home.png" inside Home Assistant: /www/anker/home.png.

In Home Assistant, when you modify your dashboard, click 'Add Card', choose 'Picture Elements Card', remove everything inside the default code, and replace it with the code below.

There are some extra entities that you will need to remove or replace. I'm using a Shelly EM to get the live electricity usage of the house.


If you want the extra sensor that provides live electricity reports, you need the Shelly EM and the ampermetric clamps (or another model).


Amazon FR:
https://amzn.to/4cLyvDP
https://amzn.to/3VN8E8x
