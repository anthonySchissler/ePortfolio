# **Artifiact / Enhancement Two: Algorithms**

The initial artifact for this enhancement came from the culminating project of CS-360, which involved creating an android application that functioned as a database-integrated 
warehouse item inventory system. Written in Java’s Maven framework, this artifact was created using a complex system of event handlers, XML layouts, and database interface 
code. Originally this artifact allowed for users to create accounts, login, add or remove items from the tracker, and set alerts to send texts when the items meet a certain 
threshold. 

I actually selected this item because of its intense complexity mixed with the desire to improve certain user functionality within the home page. Users weren’t able to sort 
these items at all, and even more egregious, users wouldn’t be able to search for items to manipulate, which meant more time scrolling to find them. To meet the demands of a 
search, I decided to use a binary search to reduce the search times down logarithmically to help reduce performance cost. My initial binary search only would produce an output 
whether or not a singular item existed, and this honestly isn’t too helpful. What if there were a series of items that had similar names, like eggsSmall, eggsMedium, or 
eggsLarge? To find all potential occurrences I would have to try and search for both a starting index as well as an ending index, and return those items back to the user. To 
do this, I created two binary searches, one that searches for the first occurrence in the item list, and one that searches for the last occurrence in the item list. By 
utilizing this algorithm on a sorted list of items, I was able to implement a simple and extremely fast searching component to my application. In addition, I modified my 
database driver to return the items in a certain order depending on whether the user chooses ascending or descending by item name or item quantity, and the created the UI 
element to make sure this functioned cleanly. 

I did meet my course outcome with this enhancement, by again demonstrating my ability to utilize data structures and algorithms to solve problems within computer science, and 
specifically solve problems that deliver value and accomplish industry-specific goals.

Modifying this artifact was much more challenging than my first, partly because I decided to perform my intended modifications for both the 2nd and 3rd enhancement together. 
After not touching Android Studio for a few months, I had to remind myself on how the flow of operations occurs for Android Apps, build responsive UI elements, and also 
integrate new and improved functionality to perform the intended enhancements. Android development heavily relies on Object Oriented principles, and this can be immensely 
confusing and off putting when starting or returning to a project, as a ton of research might need to be conducted to learn how to implement intended changes. My largest 
challenge didn’t come from implementing the sorting and search functions, but came from ensuring that UI elements were built correctly to update based off of the user’s 
actions. Through this process, I again learned how to integrate logical solutions onto a potentially daunting framework. I believe the development process for this 
demonstrates my ability 
to overcome challenges from a variety of sources, while implementing sound solutions. 
