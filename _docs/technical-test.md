---
title: Technical Test
prev_section: new-starter.html
next_section: technical-test.html
layout: default
---

Technical Test
============
**Questions**
```

1. Which code do you use to declare a property with a set accessors inaccessible to code outside the current type, while keeping the get accessors accessible?
a. private int Value{
	public get;
	set;
}

b. int Value{
	public get;
}

c. public int Value{
	get;
	private set;
}  

d. public int Value{
	get;
}


2. You are creating a new class named "Car" which contains a property named "Engine"
Which modifier do you use in a base class to require any non-abstract class to implement a class member?
a. virtual
b. protected
c. abstract
d. mustoverride
e. sealed


3. What are the difference between Promise and Observable in Javascript?








4. Based on the sample code below, which declaration do you use for "Terminate" in the class Manager so no class deriving 
from Manager will override it?
a. public final override void Terminate()
b. public static void Terminate()
c. public virtual void Terminate()
d. public volatile void Terminate()
e. public sealed override void Terminate()

public class Employee
{
	public virtual void Hire() { /* implementation */}
	public virtual void Terminate() { /* implementation */}
}

public class Manager : Employee
{
	public override void Hire() { base.Hire(); /* more implementation */}
	
	// TODO: implement Terminate
}


5. Which statement requires boxing?
a. int i = 12;
b. object o = 12
c. double d = 12;
d. byte b = 12;
e. string s = "12"


6. One of our junior developer is trying to implement a James Bond car using explicit interface implementation so that once the code compiles and run he can have the below output - 
    Start Driving...
    Start Flying...
    Speeding up....
Could you please help him to complete the code below so that this compiles and he can have the desired output?

using System;

namespace JamesBond
{
    interface IBasicCar
    {
        void Drive();
    }

    interface IFlyingCar
    {
        void Fly();
    }

    interface IJamesBondCar : IBasicCar, IFlyingCar
    {
        void TurboBoost();
    }

    public class JamesBondCar : IJamesBondCar
    {
        // TODO - complete the implementation 
		
		
		
		
		
		
		
		
		
		
		
		
    }

    class Solution
    {
       static void Main(string[] args)
        {
            /* Enter your code here to have the desired output */
			
			
			
			
        }
    }

}


7. How do you safely execute SQL queries in SQL Management Studio without impacting the database?





8. How does the routing works for ASP.Net Core 3.1?





9. Which security object contains both the user's identity and their security roles?
a. Role
b. Identity Relationship
c. Client Group
d. Service Principal
e. IUser


10. Write a method in Javascript which given two integers, returns the integer that is closest to 10000.
```
