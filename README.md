Download Link: https://assignmentchef.com/product/solved-cs202-homework-4-an-oo-framework
<br>
With both programs #4 and #5 you will be implementing your solutions using Java. Your goal must be to develop an object-oriented solution but this time implement it in Java. Make sure that your OO Design is not centered around your data structures – your data structures support the design but shouldn’t be the primary emphasis of your design. You may use Eclipse or IntelliJ to develop your software. Your Java programs must follow these rules:

For each of the above that you experiment with, write up information about it in your efficiency write-up

You are required to turn in a paper on how this solution is object oriented (your design). There is ONLY ONE design writeup for the combined programs 4-5. But, with EACH program, you are required to write 400 words about the efficiency and IDE (rather than the debugger).

<h1>Data Structures</h1>

In these last two programs, you must implement two data structures:

<ol>

 <li>Program 4:

  <ol>

   <li>If you have already implemented a balanced tree in a previous assignment: A Binary Search tree, implementing insert, display, retrieve, retrieve all related items, remove an individual item, and remove all; the algorithms must be implemented recursively.</li>

   <li>If you have not yet implemented a balanced tree, then:</li>

  </ol></li>

</ol>

A red-black tree, implementing insert, display, retrieve, retrieve all related items (no remove individual items).

<ol>

 <li>Each node needs to have a root pointer to a binary search tree for all items where the key matches. This means there can be duplicate data – but will only appear in one node’s data structure.</li>

 <li>Program 5: A linear linked list of arrays.</li>

</ol>

The required data structures specified in the assignment must be your own implementation: as in BST (or balanced tree) and linear linked lists. Once you meet the basic requirements of the assignment, you are allowed to use libraries for any subsequent data structures.

<table width="0">

 <tbody>

  <tr>

   <td colspan="2" width="576">As you go around Portland, it is amazing to see all of the delivery services. There are services which will pick up food that you order and others that will deliver meal plans, recipe cards, and perfectly portioned ingredients.  Soon we won’t have to leave home at all! The problem is that there are over 14 different food planning services and a wide variety of food delivery services (such as Grubhub, Doordash, Caviar, Postmates, UberEATS, etc.). There are just too many to know who to select from and whether or not you will enjoy your dining experience (is</td>

  </tr>

  <tr>

   <td width="140">the food fresh, etc.).</td>

   <td width="437"> </td>

  </tr>

 </tbody>

</table>




<table width="0">

 <tbody>

  <tr>

   <td colspan="2" width="576">Your job is to create a program of what will ultimately be an App to assist people in ordering meal plans and food delivery all through one application. Before the program can be used to order food, we need to first set up the meal plans and food available to be ordered. This will be the first step with Program #4. Then, once the data exists, with Program #5 we can have users (like me) put together meal plans and order food! When we order, we want to know what the ingredients are (in case we have allergies), the price of the meal, and any special</td>

  </tr>

  <tr>

   <td width="88">instructions.</td>

   <td width="488"> </td>

  </tr>

 </tbody>

</table>




Start by looking up how to use Grubhub, and get an idea of what information it contains. Here is a brief list of what I came up with:  Location (city, state/region,

<table width="0">

 <tbody>

  <tr>

   <td colspan="2" width="576">country), Food categories (Cuisine), Restaurants available for pickup or delivery,</td>

  </tr>

  <tr>

   <td width="226">the most popular dishes (a list).</td>

   <td width="350"> </td>

  </tr>

 </tbody>

</table>




Here are some suggestions on where to use the data structures assigned. These are JUST suggestions; you may adjust how the data structures are used: <em>  </em>

<ol>

 <li>Program #4 – A tree of restaurants (or cuisines) supported by our program, where each node is a tree of the most popular foods available for delivery or pickup.</li>

 <li>Program #5 – A linear linked list of my order, where each array holds the details of the order (ingredients as appropriate, prices, special instructions, etc.).</li>

</ol>

Your job is to come up with a design of an OO framework that will support an meal plan and food ordering type of application.  Although you all have the ability to write this using procedural abstraction, the key is to make sure to solve this problem using Object Oriented methodologies <strong>with dynamic binding</strong> and function overloading. <em>The use of external data file(s) are necessary!  </em>





