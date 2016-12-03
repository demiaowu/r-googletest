## r-googletest 

## What r-googletest is

Demiao WU's comments on googletest. Note that googlemock is not included.

## Dependencies

[googletest-1.8.0](https://github.com/google/googletest) (But see note below)  

## Quickstart

First, using `$ git clone git@github.com:demiaowu/r-googletest.git` clone the codes, Then, import it to your editors. Much more details about gtest's usages and implementations can be got from References.But some terms shoud be wise to know beforehand, which is as follows:  

`单元测试`（UnitTest类)  

`测试用例`（TestCase类）  

`测试特例`（Test类，一个TEST宏）——这里理解为测试特例，更加容易理解UnitTest，TestCase，Test之间的相互包含关系  

单元测试（UnitTest）是一个最大概念，它会包含很多测试用例（TestCase），而每一个测试用例又会包含很多的测试特例（Test）；在实际的使用表现为，你运行的一个单元测试就是一个UnitTest整体，这个UnitTest一般情况会包含对很多类的测试，每个类又有很多需要测试的地方，那么我们可以采用如下的方式区分和安排测试（可以，但不仅限）:  

一个TestCase对应一个类，每个类需要不同测试的地方（如方法），对应测试特例（Test）

## References

[Googletest官方文档](https://github.com/google/googletest/blob/master/googletest/docs/Documentation.md),  

[玩转Google开源C++单元测试框架Google Test系列(gtest)](http://www.cnblogs.com/coderzh/archive/2009/04/06/1426755.html),  

[Google Test(GTest)使用方法和源码解析](http://blog.csdn.net/breaksoftware/article/category/6172527)  


## Maintainer

Demiao WU <[demiaowu@163.com](demiaowu@163.com)>
