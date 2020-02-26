# cppjsdeferred 
![C/C++ CI](https://github.com/eeiaao/jspromisefactory/workflows/C/C++%20CI/badge.svg?branch=master)

A library simplifying asynchronous interaction between Qt and QML.  
Provides a bridge between asynchronous operations in C++ backend and user interface written in QML.  
Create a promise on C++ side, return it to QML, tune on a reaction, then resolve or reject the promise with necessary arguments when appropriate. That's it.

[See tests for futher details](tests)

Known issues:
  * Exceptions handling was broken until Qt 5.13.2 due to https://bugreports.qt.io/browse/QTBUG-78554 so you have to use Qt >= 5.13.2 if exceptions are needed
