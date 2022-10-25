# Kotlin Fundamentals Cheat Sheet
## Kotlin Fundamentals cheat sheet

### Variables

|             | Desc                |
| ----------- | ------------------- |
| Val         | Immuable variable   | 
| var         | Muable variable     |
| ${vari­able} | Calling a variable  |

### Output and Input

|               | Desc                                       | Example                         |
| ------------- | ------------------------------------------ | ------------------------------- |
| print()       | Print on the line                          | print(­"­Hello World !")          |
| println()     | Print on the line and go back to the line  | printl­n("Hello World !")        |
| readLine()    | Function to read the enter of the user     | var hello: String = readLine()  |

### Functions

|               | Desc                                             | 
| ------------- | ------------------------------------------------ | 
| fun           | Keyword for initia­lizing a function              |                                            
| hello         | Name of the function                             |                                            
| ()            | Parameters (varia­bles)                           |                                            
| {}            | Content of the function                          | 
| return        | Return the value of the function (not required)  |  
| function()    | call the function                                |  

```java
    fun hello () { 
    printl­n("hello world")
}
```

### Data Types

|                            | Desc                                       | Type Spescification                          |
| -------------------------- |------------------------------------------  | -------------------------------------------- |
| var foo: String = "­hel­lo"  | Variable with data type specif­ication      |                                              |
| : Int                      | Int (Integer)                              | -32 768 to 32 767                            |
| : Byte                     | Byte (Integer)                             | -128 to 127                                  |
| : Short                    | Short (Integer)                            | -32 768 to 32 767                            |
| : Long                     | Long                                       | -92233­720­368­547­75808 to 922337­203­685­4775808  |
| : Double                   | Double                                     | 1.7e−308 to 1.7e+038                         |
| : Char                     | Character                                  | /                                            |
| : Boolean                  | Boolean                                    | true or false                                |
| : String                   | String                                     | /                                            |
| : Float                    | Float                                      | 3.4e−038 to 3.4e+038                         |

_In Kotlin, variables can detect automa­tically the data type of the value in the variable but if you want to specify a data type (i.g. editing the variable)_

> For the float you should add a F behind the value of the float variable