# Encrypt
In this Project, we will convert a .py file to .pyd file using cython to encrypt our code or to increase the speed of our algorithm.  
In this Project, we will convert a .py file to .pyd or .c file, where .pyd is kind
of a .dll file for python which can be called in any python script but its not readable
and .c file contains our algorithm in ``c`` programing language. The 
conversion of file is done by cython package which is  designed to give
C-like performance with code that is written mostly in Python with
optional additional C-inspired syntax. Cython is a compiled language 
that is typically used to generate CPython extension modules.

## About project  

### Encrypt
.pyd file is kind of .dll file which is vary hard to read. So we are going to convert our python script to .pyd to secure our code while sharing.
### Increase the speed
Cython is a superset of the Python language, which allows you to add typing information and class attributes that can then be translated to C code and to C-Extensions for Python.  
I find myself frequently defending Python by explaining that, while pure Python is indeed quite slow, Python in practice is not. Libraries like Numpy, Pandas, and Scikit-learn all are C Optimized. When you use them, you're actually making use of C/C++ power, you're just able to use Python syntax. In fact, Numpy, Pandas, and Scikit-learn all make use of Cython! Chances are, the Python+C-optimized code in these popular libraries and/or using Cython is going to be far faster than the C code you might write yourself, and that's if you manage to write it without any bugs.  
just by following this simple rules we can increase the speed of our code by 10 to 100 time faster.

for more info refer to [this](https://pythonprogramming.net/introduction-and-basics-cython-tutorial)

## Dependency 
Cython: pip install cython

## How to Use
Open terminal in the Pran_Pyencrypt Directory and run following commands:
```commandline
$ python Pyencrypter.py -f "YOUR FIlE PATH"
```
It will create a .pyd file which has all you python code and can be imported in any python file just by using 
```python
import YOUR_FILE_NAME
```
Reading .pyd file is difficult but not impossible so if you want more 
security for your code try C++ programming and convert it in .dll or
.exe file.  
It will also create an ``.c`` file which contain the python algorithm in
c programing language.


## License
This project is licensed under the MIT License - see the 
[LICENSE](.github/LICENSE) file for details.
