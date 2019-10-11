This blog would compare python and blog under the basic grammar including data type, function, loop and if.

data type:

    Python: int, string, NA, None, boolean, list, turple, dictionary.

    Lua: number, string, nil, table


In fact, table in Lua is similary to the list in python . This concept is used to buid the array in the code. The example is displayed below

    Lua: 
         
         local tbl2 = {"apple", "pear", "orange", "grape"}
    
    python: 
    
        tbl2 = ["apple", "pear", "orange", "grape"]
 
 As a result, Lua is more complicated in teh grammar as we have to delare if we need create new array.
 
 Function:
 
Let us to achieve print functionality and know the differnece between python and Lua when we create fucntion.

Lua:
    
    function joke()
    c = 5           -- global varaible
    local d = 6     -- local varaible
    end

    joke()
    print(c,d) 
    
 python:
 
    def joke():
        
        global c= 5 -- global varoiable
        
        d = 5    -- local variable
     
     joke()
     print(c,d)
 
 
 For loop:
 
 if we would print the number from 1 to 10
 
Lua: 

    #!/usr/local/bin/lua  
    function f(x)  
        print("function")  
        return x*2  
    end  
    for i=1,f(5) do print(i)  
    end
    
 what ever we yse function or for loop, once we start to use this process and we have to delare the key word, end.
 
 
 python: 
 
    for i in range(1,11):
        print(i)
  
  if:
  
    --[ declare variable --]
a = 100;
--[ check condition --]
if( a < 20 )
then
   
   print("a > 20" )
else
   
   print("a > 20" )
end
print("a = :", a)


Python:
a = 100
if a<20:
    print("a < 20")
 esle:
    print("a> 20")
