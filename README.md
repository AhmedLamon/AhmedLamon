print('Hllo Lemon, Welcome to 60 days of python') #string means set of cherecter
print('Hllo Lemon', 'Welcome to 60 days of python')  #for details shift+tab
print('Hllo Lemon', 'Welcome to 60 days of python', sep='&')
print('Hllo Lemon', 'Welcome to 60 days of python', sep='&', end='*')
# Variable
var='Hello Lemon'
print(var)
print('My sentense is ' +var)
id(var)
import sys
sys.getsizeof(var)
# Valid & Invalid variable
#valid: _asif, my_name, XYZ9; Invalid: 9sakil, My name, x-Y
xyz9='Football'
xyz9
9sakil='stop it'
9sakil='stop it'
y='100'
id(y)
x='10000'
id(x)
y='10000'
id(y)
# Multiple variable
x,y,z=100,200,300
x
# Standard maintain
studentID=100
student_ID=100
studentID
student_ID  #better standard
# Local vs Global Variable
x=1000        #global
def func1():
x=500           #local
print('My name is:',x)
func1()
