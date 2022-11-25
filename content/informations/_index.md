# Informations

## Elevator

Base Coins earned by delivering bits in Your tower: `F * (1 + G) * Y + 50`  
Coins earned by delivering bits in Your tower with completed tech tree research: `Base Coins * (1 + E * F + LBT)`

Coins earned by visiting Friend towers: `F * T + 50`

`F = floor reached`, `G = total GT's`, `Y = your elevator speed` (incl Lubed Tube bonus), `T = their base elevator speed`, `E = Exponential Growth`, `LBT = Lift Boy Tips`.

`Max speed base elevator = 10 FPS` (floors per second)  
`Max Lubed Tube bonus = 1.25 FPS`

Example:  
`Elevator speed including Lubed Tube = 10.5`  
`Gold Tickets = 25`  
`Exponential Growth = 0.02`  
`Lift Boy Tips = 0.15`  
`Floor Reached = 10`  
`Base Coins = 10 * (1 + 25) * 10.5 + 50 = 2780 coins`  
`Total Coins earned = 2780 * (1 + 0.02 * 10 + 0.15) = 3753 coins`

## Fireworks

Capped at 300 bux for non-VIP, or 900 bux for VIP  
`Fireworks Bux = (days + 2) * 3 (and * 3 if VIP)` so at 98 days you have reached max fireworks.  
Fireworks days do not reset if you miss a day, they will pick up where you left them.

## Dream Jobs vs Gold Bits

Dream Jobs:

* Placing bits, even with low skills, in their dream jobs is better than placing highly skilled bits in a different job.
* Each bit in its dream job doubles the stock quantity for its product
* Each bit in its dream job pays triple their base rent

Gold Bits:

* Gold bits (skills of 99999) pay maximum base rent.
* The formula for calculating rent per bitizen is as follows: add up all its stats (for e.g. `5 + 5 + 5 + 5 + 5 = 25`), then multiply by 20 (triple if VIP, triple if Dream Worker) and you'll have the rent

Even a dream worker with skills that add up to 16 will pay more rent than a gold bit that isn't working in their dream job.

The best of all is to have Gold Bits working in their Dream Jobs.  
You can upskill existing bits through a [gfarm](TODO/online#gfarm) and/or request bits for your existing stores through requests.
All the bits sent out from requests are already Gold Bits.

## Tech Tree

* The Tech Tree is visible after reaching 20 floors, or after a previous rebuild.
* One tech point can be collected every 4 hours from the top of the tech tree.
There will be a collect point button or a countdown to when you can collect the next one if already collected.
* Tech points can be spent on research items within the tech tree.
* Some research items are dependent on the previous one being researched to the same or higher level.
* Research costs tech points and coins.  There is no way to rush research.
You can speed up research time up to 50% by purchasing a Gold Pass or Silver Pass from the Buy More menu.
* Some research items are better than others but depends on your game style and personal preference.
* Note you cannot rebuild while researching

## Rent

* The base formula for calculating rent per bitizen is as follows: First add up all its stats, for e.g. `5 + 5 + 5 + 5 + 5 = 25`. Then take that sum, multiply by 20 (triple if VIP, triple if Dream Worker) and you'll have the rent.
* A gold bit with skills of 99999 will pay at least 900 coins per day rent (\*3 if VIP, \*3 if Dream Worker)
* Bonus rent can be earned through the boosts, tech tree research and by applying GTs to apartments

Example (base rent):  
Bit's Skills: `6+5+8+9+2 = 30A`  
`30 * 20 = 600`  
If Dream Worker (not VIP): `600 * 3 = 1800 coins`, or  
If VIP (not Dream Worker): `600 * 3 = 1800 coins`, or  
If Dream Worker & VIP: `600 * 3 * 3 = 5400 coins`

Gold Bit: `9+9+9+9+9 = 45`  
`45 * 20 = 900`  
If Dream Worker (not VIP): `900 * 3 = 2700 coins`, or  
If VIP (not Dream Worker): `900 * 3 = 2700 coins`, or  
If Dream Worker & VIP: `900 * 3 * 3 = 8100 coins`

## Other

* Pending visits stay approx 1-2 days with a maximum of 2 visits per friend.
If you rebuild, your visitors will return after the tutorial.
* Gifted bitizens and raffle prizes do not expire. If you rebuild, they will return after the tutorial.
* Elevator appearance is no longer related to speed.
* If you tap the top or bottom blue bars, you can scroll to the top or bottom of your tower quickly.
* Delivering a bit to a floor under construction/restocking will take `1 + #GT` off remaining time.
* Double tapping the Job tab sorts Bitizens alphabetically by their Dream Job.
