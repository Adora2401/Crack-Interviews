# 小红书-龙猫的大耳朵的OOD教程

## 解题方法 -- 以Coffee Maker为例
1. Clarification --> 问面试官问题, clarify细节  
    eg. input: Coffee Packs  
        output: different types of coffee
2. Use cases --> 对应的key functions  
    eg. Coffee maker: brew coffee

3. Core objects --> 题目中涉及的所有class  
* CoffeePack
* CoffeeMaker
* Expresso
4. Class diagram --> 写每个class和他们的member variables, member functions, 要以有inheritance的方式表达出来  
* Challenge: different types of coffee & add-in ingredients, different prices  
    * Use ***Decorator Design Pattern***:  
        Allow users to add functionality to an existing object without altering its structure  
        Acts as a wrapper to existing class

![这是图片](/img/CoffeeMaker.png "Magic Gardens")
