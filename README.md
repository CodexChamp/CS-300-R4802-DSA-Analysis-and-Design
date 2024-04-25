# CS-300-R4802-DSA-Analysis-and-Design
This is the final project of my CS-300 class where we spent the time studing basics on data structures like hash tables, trees, and linked lists.

To share the progress that i made and what challenges i faced i will be using some questions provided by my professor to explain.

What was the problem you were solving in the projects for this course?
In this course we were approached by the school its self to update a part of their systems ability to store information about its rovided courses.
We were asked to create a program that could load all data about the provided course, data such as Course ID and its name, along with prerequisite courses 
needed before you can take that course. We had to choose from the best data structure for the job which i chose hash tables. Using the stored data the
script then should have the ability to sort then in alphanumeric order and as well as search for a specific class in the data structure and print out its specific data.

How did you approach the problem? Consider why data structures are important to understand. 
We started by learning about each data structure and eachs individual speed complexity.  Each data structure is different and has uses that could be better opt for the
task at hand than another data structure. In this project, using a hash table allows for quick access to course information using the Course ID as the key. 
This is particularly useful when sorting the courses alphabetically or searching for specific courses, as hash tables provide average-case O(1) time complexity
for insertion, deletion, and retrieval operations.

Understanding different data structures is crucial because each structure has its strengths and weaknesses depending on the problem at hand. For example, arrays
are efficient for random access but less flexible with dynamic resizing, while linked lists excel in insertion and deletion operations but can be slower for access.
Hash tables strike a balance by providing fast access and dynamic resizing capabilities, making them suitable for scenarios where quick lookups are essential, such
as in this course information system.

How did you overcome any roadblocks you encountered while going through the activities or project? 
By googling it. if i came across any problem or misunderstanding i woul search for more resources on how to understand it.

How has your work on this project expanded your approach to designing software and developing programs?
Through this experience, I've learned to carefully evaluate the requirements of a problem before diving into implementation.
Understanding the trade-offs between different data structures has enabled me to make informed decisions that optimize program
efficiency and scalability. This expanded approach encourages a more thoughtful and strategic design process, considering not 
only the immediate functionalities but also the long-term implications of the chosen design.

How has your work on this project evolved the way you write programs that are maintainable, readable, and adaptable?
By focusing on clear and modular design principles, I strive to create code that is easier to understand and modify. This 
includes using descriptive variable names, organizing code into logical functions or classes, and implementing comments 
and documentation to clarify complex sections. Additionally, incorporating best practices such as separation of concerns 
and adherence to coding standards ensures that the codebase remains maintainable and adaptable over time.
