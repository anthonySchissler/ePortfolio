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
