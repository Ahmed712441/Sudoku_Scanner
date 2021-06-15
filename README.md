# Sudoku
This program solves scanned sudoku images examples of this images is provided<br/>
if the program detects a wrong number it will put zeros in all empty places<br/>
sudoko_detector.py is the file which detect the sudoku table and squares and fill the empty places<br/>
solver.py is given 9x9 array and solve it<br/>
inside Data folder you will find:<br/>
  collector.py the algorithm that i used to collect data<br/>
  digits2.ipynb the jupyter notebook in which i created the CNN <br/>
  and aslo you will find the data that i have collected<br>
# if you to want run the program you need to install the dependencies and give it the image path as input
# dependencies :
opencv<br/>
tensorflow <br/>
numpy<br/>

# Correct detection Example :
input:<br/>
![alt text](https://github.com/Ahmed712441/Sudoku_Scanner/blob/master/h1.png?raw=true)<br/>
output:<br/>
![alt text](https://github.com/Ahmed712441/Sudoku_Scanner/blob/master/solved.jpg?raw=true)<br/>

# False detection Example :
input:<br/>
![alt text](https://github.com/Ahmed712441/Sudoku_Scanner/blob/master/false%20detection.jpg?raw=true)<br/>
output:<br/>
![alt text](https://github.com/Ahmed712441/Sudoku_Scanner/blob/master/missed.jpg?raw=true)
