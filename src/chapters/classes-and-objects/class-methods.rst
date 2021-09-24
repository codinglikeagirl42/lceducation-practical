Adding Methods to Our Class
===========================

What are Methods?
^^^^^^^^^^^^^^^^^

TODO: 

Methods are functions defined in the class and used by the objects(instances) of the class.

Lets create a **Purr** method for our Cat class.

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

      let cat1 = new Cat('Fluffy', 10);
      cat1.purr();
   
   **Console Output**

   ::

      Fluffy is happy, purrrrrrrrrrrrr


.. admonition:: Try It!

   #. Add another method to our Cat class and call it.
   
   `Try it at repl.it <https://repl.it/>`_
   TODO: Add link to starter code

Methods Outside Constructor
^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO


Methods Inside Constructor
^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO




Check Your Understanding
------------------------

.. admonition:: Question

   ToDo