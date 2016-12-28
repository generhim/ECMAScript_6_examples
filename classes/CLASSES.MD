#CLASSES NOTES

Classes actually exist in ECMAScript 6, whereas before Classes were actually mimicked in ECMAScript 1 - 5.

##ECMAScript 1 - 5:
<li>ECMAScript 1 - 5 does not have classes.</li>
<li>Instead of using classes, people relied on creating a function object -- the "constructor" function -- and then assigning properties to this object and adding functionality to the that object's prototype for later use.</li>
<li>Terminology like "class" where not used. Rather the object was created and then its properties and its prototype were extended to provide the desired results.</li>
<li>CAVEAT: While the term, "class" was not used, we would still create a new instance of this "class-like" function by using the "var NameOfInstance = new NameOfClass()" format.</li>

##ECMAScript 6:
<li>Version 6 DOES use classes. We are no longer bound by functions and prototypes.</li>
<li>In the case of version 6, we are creating a new class, "ClassName" {} which has methods that do NOT require the function keyword in front of them, and do NOT need to reference an object's prototype.</li>
<li>Instead the var MyNewPerson = new MyPerson("NameGoesHere") and MyNewPerson.whatIsMyName() are equivalent to the function-based logic created with earlier versions of ECMAScript 5, etc.</li>
        