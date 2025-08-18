# 🎓 CS-499 ePortfolio
### Carter Williams | Computer Science Capstone

---

## 📝 Professional Self-Assessment

### My Journey and What I've Learned

Finishing the Computer Science program at SNHU has been quite a ride. When I transferred in three years ago, I could write basic code but honestly had no idea how all the pieces of software development actually fit together. Now, putting together this portfolio, I can see how much my thinking has changed—not just about programming, but about building systems that actually work in the real world.

The biggest thing I've discovered about myself is that I really enjoy the architectural side of development. I like figuring out how to break complex problems down into manageable pieces and then building something that other people can actually understand and maintain. Combined with my background in industrial automation, this gives me a perspective that I think sets me apart - I understand both the software side and how it connects to physical systems.

### What the Program Really Taught Me

**Working with Teams**  
Between my coursework and my day job as a controls specialist, I've learned that good software isn't built in isolation. The real learning came from my daily work coordinating with maintenance techs, engineers, production staff, etc. Everyone sees problems differently, and that's actually valuable. I've gotten pretty good at being the translator between the technical folks and management - explaining why we need to refactor something in terms of reduced downtime costs, for example.

**Talking to Stakeholders**  
This was probably my biggest growth area. Early on, I'd get excited about technical details and lose my audience completely. My current role forced me to get better at this fast - when you're presenting an automation upgrade to plant management, they don't care about your elegant algorithm; they care about ROI and reliability. Courses like CS-340 helped with documentation skills, but the best improvements came from practice. I've learned to lead with business value and support it with just enough technical detail to build confidence.

**Data Structures and Algorithms**  
When I started, I feel I was the type who just wanted code to work and didn't think much about efficiency. But working through algorithmic analysis changed how I approach problems. Now, especially in my industrial work where processing delays can shut down production lines, I think about performance first. It's become second nature to consider what data structure makes sense before I start coding.

**Software Engineering and Databases**  
The progression from "make it work" to "make it work well" has been huge for me. CS-320 introduced systematic testing, which was eye-opening - I realized how much time I'd been wasting on debugging that proper testing could have prevented. Database work through DAD-220 and the course's projects taught me that data organization is just as important as code organization. In automation systems, data integrity isn't just nice to have; it's critical for safety and operations.

**Security Thinking**  
Security-focused coursework made me realize that security can't be something that's "bolted on later". Working with industrial control systems reinforced this - operational technology security is becoming crucial as more systems connect to networks. I now start every project by thinking about what could go wrong and how to prevent it. It's become part of my design process, rather than an afterthought.

### How My Portfolio Tells a Story

Instead of showing three different projects, I decided to take one project - my CS-320 contact management system - and enhance it across all three required areas. This approach shows something important: real software development isn't about isolated skills; it's about how different competencies work together.

**The Starting Point**  
The original project was pretty basic - a Java application with simple CRUD operations, hash map storage, and some unit tests. It worked, but it was definitely beginner-level code. Looking back at it now, I can see all the things I didn't know I didn't know.

**The Enhancement Journey**  
Each improvement builds on the previous work:

- **Software Design Enhancement**: Transformed it into a proper REST API using Spring Boot, with real architectural patterns and authentication. This shows I can design systems that other developers can work with and extend.

- **Algorithms and Data Structures Enhancement**: Replaced the inefficient searches with binary search trees and proper sorting algorithms. Performance went from decent for small datasets to scalable for real-world use. This demonstrates I understand computational complexity beyond just theory.

- **Database Enhancement**: Moved from in-memory storage to a normalized MySQL database with stored procedures and analytics capabilities. This adds real business value - turning a simple contact manager into something that could provide insights.

**Why This Approach Makes Sense**  
The final system can handle thousands of users instead of just one, retrieves data logarithmically instead of linearly, and implements best security practices. But more importantly, it shows I can take something basic and evolve it into something professional. That's exactly what happens in real jobs—you inherit code and need to make it better.

### What's Next for Carter?

This portfolio demonstrates I'm ready to contribute to development teams immediately. My combination of software skills and industrial automation experience positions me well for the kind of work I want to do - building systems where software meets physical processes. And it brings me excitement to say that I've been offered a controls engineer position at my current employer.

Manufacturing is increasingly about data analytics, predictive maintenance, and connected systems. So, having professionals who understand both the manufacturing side and the software side is becoming more valuable. I can speak both languages, which I think gives me an edge.

The technical artifacts that follow show the details of what I've built and learned. But the real story is about growth - from someone who could write code that worked to someone who can design systems that solve real problems efficiently and securely.

---

## 🚀 PROJECT OVERVIEW

This project started as a milestone assignment I finished last year in my **CS-320 course**. I made a simple contact management system in Java. The original solution had a Contact class with methods for validation, a ContactService class that uses a hash map for in-memory storage to maintain contacts, and test classes (ContactTest and ContactServiceTest) to make sure everything works and handles the errors. 

> 💡 **This project shows some basic software engineering design and input validation techniques.**

---

## 🛠️ ENHANCEMENT CONCEPTS

### 🔧 **ENHANCEMENT ONE CONCEPT**
[![Software Design](https://img.shields.io/badge/ENHANCEMENT-SOFTWARE%20DESIGN%20%26%20ENGINEERING-brightgreen?style=for-the-badge&logo=code)](https://github.com/carterdwill3/CS-499/tree/EnhancementOne)

My enhancement plan transforms the basic contact service into a **REST API with database persistence**. This involves:

**Key Features:**
- ⚡ Replacing the hash map with database storage
- 🏗️ Implementing a repository pattern for data access  
- 🌐 Creating REST endpoints for contact operations

> *This enhancement demonstrates the best methods of architecture while maintaining important core functionality.*

---

### ⚙️ **ENHANCEMENT TWO CONCEPT**
[![Algorithms](https://img.shields.io/badge/ENHANCEMENT-ALGORITHMS%20%26%20DATA%20STRUCTURES-orange?style=for-the-badge&logo=algorithm)](https://github.com/carterdwill3/CS-499/tree/EnhancementTwo)

My algorithms and data structure-like enhancement plan will also transform the basic contact storage into a **higher-level data management system** with multiple advanced data structures and efficient algorithms. 

**Key Features:**
- 🔍 Implementing custom search algorithms
- 📊 Sorting mechanisms  
- ⚡ Optimized data structures
- 📈 Various contact management operations that improve the code's performance

> *This includes: implementing custom search algorithms, sorting mechanisms, and optimized data structures; this will give various contact management operations that improve the code's performance.*

---

### 🗄️ **ENHANCEMENT THREE CONCEPT**
[![Database](https://img.shields.io/badge/ENHANCEMENT-DATABASE%20DESIGN-purple?style=for-the-badge&logo=database)](https://github.com/carterdwill3/CS-499/tree/EnhancementThree)

My database enhancement plan turns the in-memory contact storage into a **comprehensive database solution** with MySQL integration, advanced querying capabilities, and data analytics features.

**Key Features:**
- 🗃️ Implementing relational database design with multiple related tables
- ⚙️ Creating stored procedures for complex operations
- 📊 Adding data mining capabilities for contact insights

> *This includes: implementing relational database design with multiple related tables, creating stored procedures for complex operations, and adding data mining capabilities for contact insights.*

---

###### 📁 **Original CS-320 Project**

[![REPO](https://img.shields.io/badge/REPO-CS--320-lightgrey?style=for-the-badge&logo=github)](https://github.com/carterdwill3/CS-320)

---

## 🎯 Portfolio Navigation

[![Code Review](https://img.shields.io/badge/🎥%20WATCH-CODE%20REVIEW-red?style=for-the-badge)](https://snhu-my.sharepoint.com/:u:/g/personal/carter_williams_snhu_edu/ESMFtUZwLRtBk-mPhNo57WgB0nXOLukuOM0bAAvT6TwRWw?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=rY7VjI)

[![Enhancement 1](https://img.shields.io/badge/🔧%20SOFTWARE-DESIGN%20ENGINEERING-brightgreen?style=for-the-badge)](https://github.com/carterdwill3/CS-499/tree/EnhancementOne)

[![Enhancement 2](https://img.shields.io/badge/⚙️%20ALGORITHMS-DATA%20STRUCTURES-orange?style=for-the-badge)](https://github.com/carterdwill3/CS-499/tree/EnhancementTwo)

[![Enhancement 3](https://img.shields.io/badge/🗄️%20DATABASE-DESIGN%20INTEGRATION-purple?style=for-the-badge)](https://github.com/carterdwill3/CS-499/tree/EnhancementThree)

---

**🎓 SNHU Computer Science Capstone Project**  
*Find the links to my GitHub and LinkedIn profiles below :)*

[![GitHub Profile](https://img.shields.io/badge/GitHub-carterdwill3-black?style=flat&logo=github)](https://github.com/carterdwill3)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Carter_Williams-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/carter-williams-1ab6b61a6/)
