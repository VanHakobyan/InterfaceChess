# Interface Chess Inheritance


<p align="center">
<img src="https://media.giphy.com/media/13bNeFeyPnCycM/giphy.gif">
</p>
<br>
<br>

![IBishop](https://encrypted-tbn3.gstatic.com/images?q=tbn:ANd9GcT-8kQpkbN4UxlHwVUw7GzYlNOI2QYTxf82Ij_fWSD-qq1ofs69) +
![IRook](https://encrypted-tbn3.gstatic.com/images?q=tbn:ANd9GcRlqj5kdHhS85kHMOBcJQfbsVCHCf26g5qLlvJPEhF8J6E7eXAb) =
![IQueen](https://encrypted-tbn2.gstatic.com/images?q=tbn:ANd9GcTgnwszCgX3Crsd6d6ve1IjExwOvnn4KEZP8DCVuL1HkLEVHPby)
###  Description
<br>


* The combination of motility of the bishop and the rook in Chess is an ideal example of interface's inheritence.



```c#
interface IQueen:IBishop,IRook
{
    //distanceuUlimited
    //Queen moves horizontal, vertical and diagonally
    //IQueen=IBishop+IRook

}
```
<p>The <b>rook and bishop versus rook endgame</b> is a <a href="https://en.wikipedia.org/wiki/Chess" title="Chess">chess</a> <a href="https://en.wikipedia.org/wiki/Chess_endgame" title="Chess endgame">endgame</a> where one player has just a <a href="https://en.wikipedia.org/wiki/Rook_(chess)" title="Rook (chess)">rook</a>, <a href="https://en.wikipedia.org/wiki/Bishop_(chess)" title="Bishop (chess)">bishop</a> and king, and the other player has only a rook and king. It has been studied many times through the years. This combination of <a href="https://en.wikipedia.org/wiki/List_of_chess_terms#Material" class="mw-redirect" title="List of chess terms">material</a> is one of the most common <a href="https://en.wikipedia.org/wiki/Pawnless_chess_endgame" title="Pawnless chess endgame">pawnless chess endgames</a>. It is generally a <a href="https://en.wikipedia.org/wiki/Theoretical_draw" class="mw-redirect" title="Theoretical draw">theoretical draw</a>, but the rook and bishop have good winning chances in practice because the defense is difficult. 
