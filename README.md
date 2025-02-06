# Little Barbie Purchasing Problem

You are the manager of the retail store “Toys and Co” and you are concerned with the inventory
management of your star product “Little Barbie”. The demand for this product is mainly
concentrated during the selling period before Christmas, i.e. November and December. This demand
is not known exactly in advance but could be estimated thanks to last year sales.

Little Barbie is Manufactured is in a low cost and far away country. As a consequence, you have only
one opportunity to replenish in March. So, you have to order the right quantity in March which is
delivered to you just before the selling season in November.
The production cost for each item is denoted by c and is equal to c = 10 euros. During the selling
season, you earn a comfortable margin by setting the selling price denoted by r equal to r = 50 euros.
At the end of December, unsold and remaining items in your stock should be discounted during the
sales period of January. The discount price denoted by s is given by s = 5 euros.
Your aim in this decision making process is to find the best quantity to order, denoted by Q, which
maximise your expected profit.

## The Centralized case:
We consider in this centralized case that the manufacturing site in the low cost country belongs to
your retail store and we assume that there is no margin applied between the production and the
retailing site.
1. Calculate the unit penalty incurred when a shortage occurs during the selling season as well
as the unit penalty associated with an unsold item.
2. From an intuitive point of view, do you have to order a quantity lower or higher than the
demand average?
3. For a given vector (Demand D, ordered quantity Q), express the profit you make during the
selling period. Apply for the different demand values to calculate the expected profit.
4. Using python basics (list, function), derive the optimal ordering quantity
## The decentralized case with a Take-it-Or-leave-it contract
We consider now that your supplier is an independent firm and makes a margin when producing and
selling “Little Barbie” to your retail store. His unit production cost is c = 10 euros and his wholesale
price is denoted as w.
He is aware of the market facing you, so he has an information about your demand, and he proposes
to you a take it or leave it contract where he fixes the wholesale price w. You, based on the price w,
you optimize your inventory strategy and your order a quantity Q maximizing your profit.
When proposing you the wholesale price w, the aim of your supplier is naturally to maximize his own
expected profit.
1. If you were the supplier, what would be your optimal proposed wholesale price w.
2. Calculate the total profit of the decentralized case (you + your supplier) and compare it with
the centralized profit
## The decentralized case with a coordination contract
The aim is to build a coordination contract permitting to increase the total supply chain profit to let it
equal to the centralized case.
1. What type of coordination contract do you recommend to achieve this target?
