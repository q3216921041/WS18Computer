
JavaSE教学文档

面向对象(上)

    1.什么是面向对象
    
         1) 面向对象思想是一种更符合我们思考习惯的思想，它可以将复杂的事情简单化，并将我们从执行者变成了指挥者。 
         2) 面向对象的语言中，包含了三大基本特征，即 封装、继承和多态 。
    
    2.明确类与对象的关系
    	    
    	    1)什么是类？
    	                 类：是一组相关属性和行为的集合。可以看成是一类事物的模板，使用事物的属性特征和行为特征来描述该 类事物。
                            现实中，描述一类事物：
                            属性：就是该事物的状态信息。 行为：就是该事物能够做什么。
                            举例：小猫。属性：名字、体重、年龄、颜色。 行为：走、跑、叫。
        2)什么是对象？
                            对象：是一类事物的具体体现。对象是类的一个实例（对象并不是找个女朋友），必然具备该类事物的属性 和行为。
                            现实中，一类事物的一个实例：一只小猫。
                            举例：一只小猫。属性：tom、5kg、2 years、yellow。 行为：溜墙根走、蹦跶的跑、喵喵叫。              
        3)类与对象的关系（三句话总结）
                           类是对一类事物的描述，是抽象的。 
                           对象是一类事物的实例，是具体的。 
                           类是对象的模板，对象是类的实体。
    3.类的定义
        1)现实事物与类的对比
                           现实世界的一类事物：属性：事物的状态信息。 行为：事物能够做什么。
           Java中用class描述事物也是如此：成员变量：对应事物的属性     成员方法：对应事物的行为
        2)定义类：就是定义类的成员，包括成员变量和成员方法。
                           成员变量：和以前定义变量几乎是一样的。只不过位置发生了改变。在类中，方法外。
                           成员方法：和以前定义方法几乎是一样的。只不过把static去掉，static的作用在面向对象后面课程中再详细 讲解。
                           
         
    
         
         
           
    	    
    
   
     
类中的成员之属性(成员变量)

     1.属性的定义格式
     	修饰符	数据类型	属性名 = 初始化值 ;
     	
     2.成员变量的访问控制符
         public private 默认  protected
         
     3.成员变量  VS 局部变量(重点)
          1). 定义的位置不一样【重点】
                              局部变量：在方法的内部
                              成员变量：在方法的外部，直接写在类当中

          2). 作用范围不一样【重点】
                                   局部变量：只有方法当中才可以使用，出了方法就不能再用
                                    成员变量：整个类全都可以通用。

          3). 默认值不一样【重点】
                                   局部变量：没有默认值，如果要想使用，必须手动进行赋值
                                   成员变量：如果没有赋值，会有默认值，规则和数组一样

          4). 内存的位置不一样（了解）
                                   局部变量：位于栈内存
                                   成员变量：位于堆内存

          5). 生命周期不一样（了解）
                                  局部变量：随着方法进栈而诞生，随着方法出栈而消失
                                  成员变量：随着对象创建而诞生，随着对象被垃圾回收而消失



