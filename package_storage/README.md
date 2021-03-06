# stack_ops package     #
### Author: Suyog K Sethia    ###     
     
I have created documented package 'pkg_stack' which provides feature 'stack' general functionality, with exception handling. I also threw in unittest, which is runnable after installing package, and it checks sanity of package 'pkg_stack'.      
     
## Install Package 'pkg_stack' via pip:             ##
```
pip install pkg-stack-skscodes
```         
      
## To Import Package 'pkg_stack':           ##
```
import pkg_stack
```     
    
## Find Attributes:      ##
```
>>>from pkg_stack.mystack import Stack
>>>dir(Stack)
>>>dir(Stack())
```     

## Find Help:  ##
```
>>>help(Stack.from_values)        
Help on method from_values in module pkg_stack.mystack:    
    
 from_values(*args) method of builtins.type instance    
     Construct a Stack from given values.    
    
    Params:    
    *args: Integer values to be pushed onto the stack being created.    
     
    Returns: The newly created Stack object
```    

```
>>>help(Stack.pop)
Help on function pop in module pkg_stack.mystack:

pop(self)
    Pop a value from the stack.
    
    Returns: The integer value popped from the stack.
    
    Raises:
    StackEmptyError: When trying to pop from empty stack.
```

### Example: ###   
```
>>>from pkg_stack.mystack import Stack                   
>>>s = Stack.from_values(1,2,3,4)           
>>>print(s)     
[1, 2, 3, 4]    
``` 
    
## Exception Handling:    ##           
### sample case-1:     ###
```
>>>from pkg_stack.mystack import Stack                    
>>>s = Stack()               
>>>s.pop()      
stack is empty.       
```

### sample case-2:  ###       
```
>>>s =Stack.from_values(1,2,3,4,5)            
>>>s.push(5)      
stack is full.     
```

### To see full demo of Package 'pkg_stack' operations in video-like manner:    ###
```
>>>import pkg_stack.mystack     
>>>pkg_stack.mystack.main()         
demo begins..
..  
.. 
```

### Enjoy! ###   