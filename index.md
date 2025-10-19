
# **Artifiact / Enhancement One: Software Engineering**

This artifact is the improvement of a project that I created for CS-300: Data Structures and Algorithms. Originally, the project was the culmination of the course, where the 
class was given a problem, and the students had to choose a specific data structure to use to solve the problem. Written in C++, I wrote my solution using a hashtable. 
Essentially, it reads in a CSV that holds a series of course identifiers, names, and pre-requisites that the class has, and stores them for viewing. The user can load a dataset 
in, view all items in the dataset, and search for a specific item. This improved artifact is written in C#, utilizing a Red-Black Tree variant known as the “Left-Leaning Red-
Black Tree” devised by famed computer scientist Robert Sedgewick. 

Using inspiration from the suggestions for the capstone, I decided to do two things with this past project. I wanted to redo this assignment in another language, and C# to
me has always been interesting because of its use in .NET and my extensive experience using PowerShell at work as a Systems Administrator. Additionally, I wanted to explore 
binary trees because I haven’t explored that data structure much in my computer science career, often opting for a hashmap or arrays. Specifically, this showcased my ability 
to implement a performant solution to meet the requirements of a problem. I was able to not only implement a simple Binary Search Tree, but also implement the balancing and 
enhanced characteristics to make it a Left-Leaning Red-Black Tree. 

I did meet the course outcomes that I had set out to accomplish. I believe this project demonstrated a few outcomes as well, including:

    1.	Design and evaluate computing solutions that solve a given problem using 
    algorithmic principles and computer science practices and standards 
    appropriate to its solution, while managing the trade-offs involved in design choices
    
    2.	Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in 
    computing practices for the purpose of implementing computer solutions that 
    deliver value and accomplish industry-specific goals

I have a habit of using recursion and then forgetting how to utilize it, or how it fundamentally works, over time. With a recursive BST solution, I picked up and gained a more 
fundamental understanding of how recursion was used to traverse over the data structure. Some challenges I encountered involved stack overflows and null pointer exceptions, 
where I had to adjust the algorithm to account for areas where the LLRB Tree design seemed to leave out some error handling. In addition, I did utilize ChatGPT to generate a 
massive, random dataset that matched the format given for the original project. The original dataset only contained about 7 entries, but I was able to generate a set that had 
twenty-thousand entries, showcasing the solution’s performance. In addition, I learned how to implement metric gathering to observe how many comparisons are made when 
searching for items, and how to utilize C# to create a “custom” data structure without the use of pointers like I had in my C++ implementation. Overall this project reinforced 
my fascination with performance and speed; when loading and searching for data using this artifact, it takes milliseconds to perform the required calculations to load and read 
through the stored data. This will help reinforce my next improvements, which involve adding in a search capability to my other application. 

### **Enhancement Directory:**
- [Software Engineering Enhancement Repository](https://github.com/anthonySchissler/CS-499-Enhancement-One-Software-Design-and-Engineering)

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

### **Enhancement Directory:**
- [Algorithms/Databases Enhancement Repository](https://github.com/anthonySchissler/CS-499-Enhancement-Two-Three-Algorithms-Databases)

# **Artifiact / Enhancement Three: Databases**

The initial artifact for this enhancement came from the culminating project of CS-360, which involved creating an android application that functioned as a database-integrated 
warehouse item inventory system. Written in Java’s Maven framework, this artifact was created using a complex system of event handlers, XML layouts, and database interface 
code. Originally this artifact allowed for users to create accounts, login, add or remove items from the tracker, and set alerts to send texts when the items meet a certain 
threshold.

I selected this artifact due to the challenges in working with the framework, in addition to some missing functionality that I wanted to incorporate into my original 
submission for that class. For this enhancement, I decided to tackle security enhancements with my artifact in addition to enhanced database functionality. This artifact in 
particular demonstrated my ability to implement role based access into my user database, and then utilize these protection levels throughout my application. As a 
demonstration, I created three roles that  user can have in the database: Administrator, Manager, and Employee from least to most restrictive. Administrators have the full 
suite of tools to manage and create items, but they also have the added benefit of having access to a page that can manage users and their accesses as well, including removal 
of access. Managers are able to manage and create items, but cannot administrate users in any capacity. Employees are only able to manage items – they aren’t able to add new 
items into the warehouse stock, only change the accounting for items that are already in the warehouse. By implementing these roles I am able to demonstrate my competency 
utilizing databases to meaningfully improve the application’s security posture. 

I did meet the course outcomes I planned to meet with this enhancement. I implemented security based controls utilizing database integration, and I did so partially to meet an 
end goal of building a collaborative environment as well

This modification was particularly satisfying because I was able to tie in a few more concepts to my application together. Least privilege and user assignment was something I 
wanted to implement in my original submission, but I wasn’t able to due to time constraints. I learned how to utilize security roles established within a database from my 
application, and then guardrail features off based on the access the user had. In addition, I was able to implement a feature from my second enhancement into this as well, 
with a binary search that can be utilized for User accounts. The largest challenge I faced was creating the UI elements and making sure they displayed and updated properly 
when adjusted. Thinking of the roles the users have and building the infrastructure in the database interface to support that was also slightly challenging. Overall I’m 
satisfied that I was able to implement these features, and I think they work quite well for what I was trying to implement. 

### **Enhancement Directory:**
- [Algorithms/Databases Enhancement Repository](https://github.com/anthonySchissler/CS-499-Enhancement-Two-Three-Algorithms-Databases)
