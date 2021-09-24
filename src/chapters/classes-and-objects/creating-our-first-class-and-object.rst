Creating Our First Class and Object
===================================

Where it Begins
^^^^^^^^^^^^^^^

The syntax to declare a Class is:

.. admonition:: Example

   .. sourcecode:: js
      :linenos:

      class Cat {
         // The body of class  
      }

The **class** keyword is followed by the **class name**.  So the above code creates the **Cat class**.

   #. Convention states to start class names with a capital letter, and to use PascalCase.

   #. Class names are case sensitive(both lower and uppercase letters are permitted). 

   #. They can contain letters, numbers and underscores. 

Add Some Properties to Our Class
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

We can use the **constructor()** method to add the properties(parameters) we want our class to include. When we create a new object(instance) of our class, the constructor is called and will pass these properties to it.

.. admonition:: Example

   .. sourcecode:: js
      :linenos:

      class Cat {
         constructor(name, age){
            this.name = name;
            this.age = age;
         } 
      }

Our **Cat class** now has two properties: 'name' (line 3) and 'age' (line 4). The **this** keyword references the current object being created.

.. admonition:: Note

   Only one constructor per class. If you do not define a constructor method, JavaScript will add an empty one. The constructor is also only called once when the object is first created.

Create a New Object
^^^^^^^^^^^^^^^^^^^^
We've got our Cat class and now we can use the **new** keyword to create a new Cat object, line 8 in the code below. This calls on the **constructor** to create a new object Cat1 based on Cat class.  Cat1's initial name is Fluffy and initial age is 10.

.. admonition:: Example

   .. sourcecode:: js
      :linenos:

      class Cat {
         constructor(name, age, color){
            this.name = name;
            this.age = age;
         } 
      }

      let cat1 = new Cat('Fluffy', 10);
   
      console.log(typeof cat1);
      console.log(cat1);

   **Console Output**

   ::

      object
      Cat { name: 'Fluffy', age: 10 }

.. admonition:: Try It!

   #. Add another property to our Cat class.
   #. Create at least two more Cat objects.

   `Try it at repl.it <https://repl.it/>`_
   TODO: Add link to starter code


Check Your Understanding
------------------------

.. admonition:: Question

  TODO
  
   

  