# Prototypal Inheritance

Unlike classical languages like C# and Java, JavaScript does not have a true class. It utilizes linking objects together in order to inherit properties. Every single object that you create, unless specified not to, is automatically linked to the corresponding global object prototype.

We also have the ability through utility functions and other methods to link objects together to share functionality. This lesson walks through a simple implementation of this inheritance paradigm and attempts to show how prototypes are used.

[OG JS Object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/proto)