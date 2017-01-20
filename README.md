# Interface Chess Inheritance


<p align="center">
<img src="https://media.giphy.com/media/13bNeFeyPnCycM/giphy.gif">
</p>
<br>
<br>

![IBishop](https://encrypted-tbn3.gstatic.com/images?q=tbn:ANd9GcT-8kQpkbN4UxlHwVUw7GzYlNOI2QYTxf82Ij_fWSD-qq1ofs69) +
![IRook](https://encrypted-tbn3.gstatic.com/images?q=tbn:ANd9GcRlqj5kdHhS85kHMOBcJQfbsVCHCf26g5qLlvJPEhF8J6E7eXAb) =
![IQueen](https://encrypted-tbn2.gstatic.com/images?q=tbn:ANd9GcTgnwszCgX3Crsd6d6ve1IjExwOvnn4KEZP8DCVuL1HkLEVHPby)
##  Description
<br>


### The combination of motility of the bishop and the rook in Chess is an ideal example of interface's inheritence.



```c#
interface IQueen:IBishop,IRook
{
    //distanceuUlimited
    //Queen moves horizontal, vertical and diagonally
    //IQueen=IBishop+IRook

}
```
<p>While there are many examples of "random" password generator programs available on the Internet, generating randomness can be tricky and many programs do not generate random characters in a way that ensures strong security. A common recommendation is to use <a href="/wiki/Open_source" class="mw-redirect" title="Open source">open source</a> security tools where possible, since they allow independent checks on the quality of the methods used. Note that simply generating a password at random does not ensure the password is a strong password, because it is possible, although highly unlikely, to generate an easily guessed or cracked password. In fact there is no need at all for a password to have been produced by a perfectly random process: it just needs to be sufficiently difficult to guess.</p>
