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
