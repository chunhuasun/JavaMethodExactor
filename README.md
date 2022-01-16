# JavaExtractor

## About the project

The project is a code extractor, whose function is to input the path of a java project and output the method information in the project.
The method information includes the class name, method name, method body code, return value, parameter, etc. it is very convenient to use. 
I have packaged the project code into a jar package, which can be run according to the command to quickly extract the Java method information

## Environmental 

```
jDK 1.8
Maven
```
## How to use
```
# The first parameter is the project path, and the second parameter is the specific file to output to
# example
java -jar JavaMethodExactor.jar /home/javaproject ./ouput.txt
```


## 使用教程：后面的两个参数分别是输入的项目路径、输出到的文件的路径
```
java -jar JavaMethodExactor.jar /home/javaproject ./ouput.txt
```
## 输出格式
```
类名@方法名@参数名@返回值@方法体
```
