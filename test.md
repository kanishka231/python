1.Why Python its called dynamically ececuted language?

Python is dynamically executed language it execute the code at runtine unlike other programing languagesa like C,C++, and Java python execute the code at runtime for example we dont need to declare the type of the variable becuse python determine that at runtime 
so we can write
```
   x="kanishka"  \\string
   x=10   \\ int
```
 So in short we dont need to decalre the variable type it will determine at run time


 the deeper reason behind is how pythin store the variable in memory python do not store the data dirctly in memory of varibale instead it store that in object which crries it type with it 

 ```
    <class type=int,5>

```
So the variable name are just lable they does not carrie that type inof they just point to that meomory object having type info and value

```
  x= Kanishka


```
It will point to another object which is having type string and carrinet the value of that string .Wbefore exce can check the type before execution using mypy and pyright which will tell us nay type error we have before execution but they ust extention

we use the mypy with type hints 

```
  x :string = "kanishka"
```
So what happens is we provide myspy what type we expect for safety then do mypy main.py this will provide all the type error we encounters



 Q2. How python execute the code
 Ans.


