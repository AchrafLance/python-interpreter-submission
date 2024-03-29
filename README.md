# Java / SpringBoot NoteBook Server Project
software used: 
- IDE: IntelliJ IDEA
- [Postman](https://www.getpostman.com/) Platforme to perform requests
- [Jython](https://www.jython.org/download.html) standalone API as a python interpreter

**Prerequisite:**
--
 - Download Jython standalone .jar file from [here](https://www.jython.org/download.html) and add it to your IDE libraries.

Sample Input: 
--
![input](https://github.com/AchrafLance/interpreter/blob/master/sample_input.png)

Sample Output:
--
![output](https://github.com/AchrafLance/interpreter/blob/master/sample_output.png)


Description:
--
>**Task1**: 
used spring web dependency to setup my spring boot environment

>**Task2**: 
used Jython interpreter to execute the parsed JSON entry and an outputStream to capture the result 

>**Challenge1**: 
just made sure only one instance of the python interpreter is handling all the subsequente requests 

>**Challenge2**: 
created a hashmap that stores an instance of the python interpreter and a sessionID, so that each 
request either creates a new python interpreter instance ( if the sessionID is new ) or call an existing one.
