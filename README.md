# 8-puzzle-heuristic1
![struct](https://user-images.githubusercontent.com/56763570/78756259-5bdf3500-792f-11ea-81ef-c616c77c76c8.PNG)<br/>
Diatas adalah struct node yang berisi vector orientation, nilai g, f, dan parent.
Penyelesaian 8 puzzle dengan menggunakan heuristic 1 yang berarti mencari banyaknya kotak yang salah penempatannya. Berikut fungsi heuristicnya.
<br/>![h1](https://user-images.githubusercontent.com/56763570/78756621-ef186a80-792f-11ea-864c-75438c482b20.PNG)<br/>
Jadi setiap blankspace bergerak akan dihitung nilai heuristic 1 dan nilainya yang paling kecil maka perpindahan tersebut dipilih menjadi parentnya.
