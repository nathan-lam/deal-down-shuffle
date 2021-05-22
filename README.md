# deal-down-shuffle
This small personal project exploring the property of the deal down shuffle.

The deal down shuffle is a "shuffle" but it is more like a mathematical shuffle used by magicians to reveal a card.
This is related to the [Josephus problem](https://en.wikipedia.org/wiki/Josephus_problem), but I did not do any reseach while exploring this shuffle.  


Starting with a small pack of cards (face down) do these steps:
1. Deal the top card onto a single pile on a table.
2. Deal the next top card to the bottom of the pack youre dealing from.
3. Repeat steps 1 and 2 until all the cards go into the single pile

[This page goes more in depth about the shuffle.](https://www.maa.org/external_archive/columns/colm/cardcolm200504.html)

Magicians will use this shuffle by positioning a card such that it will end up as the last card dealt when doing the shuffle. Though this use, knowing which position goes to the first position is usually the desired effect. 

My exploration finds an (approximate) formula to find the ending position is given the numbers of cards in the packet and the starting position. I also looked at fixed points and closed loops upon repeating this deal multiple times.


A few observations  
Let N = number of cards in the packed
    x = inital position before the shuffle (relative to the cards face down)
    y = ending position after the shuffle (relative to the cards face down)
 
 if N=10, x = 7
 then y = 7 (the card never moves)
