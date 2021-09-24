Understanding Inheritance
=========================

What is Inheritance?
^^^^^^^^^^^^^^^^^^^^

TODO

ADD figure Cat class - HouseCat class - JungleCat class

Extends?
^^^^^^^^

TODO

By using the **extends** keyword the new class inherits all of the element of the existing class.

.. admonition:: Example

   .. sourcecode:: js
      :linenos:

      class Cat {
         constructor(name, age, color){
            this.name = name;
            this.age = age;
         }
         purr() {
            console.log(`${this.name} is happy, purrrrrrrrrrrrr`);
      }

      class JungleCat extends Cat {
         bite() {
            console.log(`${this.name} is hungry, gggrrrrrr chomp chomp`);
      }






      let cat1 = new JungleCat('Fluffy', 10);
      cat1.bite();
      cat1.purr();
      
   **Console Output**

   ::

      Fluffy is hungry, gggrrrrrr chomp chomp
      Fluffy is happy, purrrrrrrrrrrrr

.. admonition:: Try It!

   #. TODO
   
      Create a class HouseCat that extends from another class.
      ? Can you extend a class that itself extends another class ?

   `Try it at repl.it <https://repl.it/>`_
   TODO: Add link to starter code


Super?
^^^^^^

TODO

**constructor** function must use the **super** keyword, parent/child?
If your new class in extends has constructor must use super?

.. admonition:: Example

   .. sourcecode:: js
      :linenos:

.. admonition:: Try It!

   #. TODO

   `Try it at repl.it <https://repl.it/>`_
   TODO: Add link to starter code


Check Your Understanding
------------------------

.. admonition:: Question

   ToDo