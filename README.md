Let's make a game!
name:Cake factorium
 
Buttons
 
*SB
name:Oven
desc:Bake cake
on click:yield 1 C
class:bigButton
 
Resources
 
*C
name:Cake
desc:Yummy yum yum
 
*GC
name:Golden Cake
desc:The cake with gold filling
hidden when 0
 
 
Buildings
 
*b1
name:Toy oven
desc:AKA kindergarden nostalgia <.> multiplies yield from the oven by 0.1
passive:multiply yield of SB by 0.1
cost:15 C
tag:oven
 
*ba1
name:BB
desc:Baby baker
on tick:yield 1 C
cost:100 C
tag:baker
on earn:hide ba1
 
*ba2
name:Teen baker
desc:shy and akward bakers
on tick:yield 10 C
cost:1000 C
tag:baker
on earn:hide ba2
req:10 bal1
 
*ba3
name:Adult baker
desc:Look grandma i can bake
on tick:yield 50 C
cost:10000
tag:baker
on earn:hide ba3
req:10 bal2
 
*ba4
name:amatuer baker
desc:YOU F*****G DONUT
on tick:yield 100 C
cost:100000
tag:baker
on earn:hide ba4
req:10 bal3
 
*bal1
name:BB levelup
desc:level up Baby baker to get upgrades
passive:multiply yield of ba1 by 2000000000000000009090909090695096095065069059605960596059605906950690596596059605969509
cost:10 C
tag:baker
req:ba1
 
*bal2
name:Teen baker levelup
desc:level up Teen baker to get upgrades
passive:multiply yield of ba2 by 2
cost:100 C
tag:baker
req:ba2
 
*bal3
name:Adult baker levelup
desc:level up adult baker to get upgrades
passive:multiply yield of ba3 by 2
cost:1000 C
tag:baker
req:ba3
 
*bal4
name:Amatuer baker levelup
desc:levelup amatuer maker to unlock upgrades
passive:multiply yield of ba4 by 2
cost:10000
tag:baker
req:ba4
 
 
Upgrades
 
*c1
name:Regular clicking
desc:Wait when do you click while baking
cost:100 C
	passive:multiply yield of SB by 2
 
*c2
name:Blueberry cakes
desc:Yum
cost:500 C
passive:multiply yield of SB by 2
 
*c3
name:Strawberry cakes
desc:The berry that isnt a berry
passive:multiply yield of SB by 2
cost:10000 C
 
*c4
name:Gloves
desc:To keep your hands all nice and tidy
passive:multiply yield of SB by 2
cost:100000 C
 
*c5
name:Strawberry frosting
desc:Im addicted to strawberries
passive:multiply yield of SB by 4
cost:10000000 C
 
*c6
name:Chocolate frosting
desc:Nice and original
passive:multiply yield of SB by random(2,4)
cost:100000000 C
 
*c7
name:Glowing jam cakes
desc:Not made from glowsticks <b>I promise</b>
passive:multiply yield of SB by 1+bal1
cost:1000000000 C
 
*c8
name:Random cakes
desc:It tastes like strawberries, bananas, chocalate, cherry, lemon, lime, cheese, cucumber, sour cream, soap?, peppers.
passive:multiply yield of SB by 1+bal2
cost:10000000000 C
 
*c9
name:Noir cakes
desc:Cakes right from the 50s
passive:multiply yield of SB by 1+bal3
cost:100000000000 C
 
*c10
name:rEVERSE CAKES
desc:sekac desreveR
passive:multiply yield of SB by 1+bal4
cost:1000000000000 C
