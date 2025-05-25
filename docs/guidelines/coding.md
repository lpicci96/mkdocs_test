---
tags:
    - guidelines
---

# ONE Coding Principles

We code our analysis for transparency and reproducibility. We prioritise clarity and code in a way 
that makes it easy for others to use our work.

1. __Readability Counts__: Your code should be written and formatted to be easy to read. 
Others will be reading your code, and you'll be reading it yourself in the future.

2. __KISS (Keep It Simple, Stupid)__: Try to keep your code as simple and straightforward as possible. The less complex your code is, the fewer chances there are for bugs to appear.

3. __DRY (Don't Repeat Yourself)__: If you see that you're writing the same code in more than one place, consider making a function or class out of it. Reuse your code to make it more efficient and maintainable.

4. __YAGNI (You Aren't Gonna Need It)__: Don't add functionality until it's absolutely necessary. Keep your code lean and only add what you need right now, not what you think you might need in the future.

5. __SOLID principles__: These are a set of principles aimed at making software design more understandable, flexible, and maintainable. They are adapted to our more more function-driven style:

   a. __Single Responsibility Principle__: Each function (or class) should have one job. If a function or class is doing more than one job, consider breaking it down into more functions (or classes).

   b. __Open-Closed Principle__: Your code should be open for extension (meaning that you can make the behaviour more specific or sophisticated) but closed for modification (you shouldn't have to change the existing code to do it).

   c. __Liskov Substitution Principle__: In the context of functions, this means that any function you write should be able to be replaced with another without breaking the code. In practice, this encourages us to write functions that are predictable and consistent in their behaviour. For example, if you have a function that calculates a percentage of GDP, it should always return a number (and not, say, sometimes a string or a list).

   d. __Interface Segregation Principle__: This principle encourages us to write functions that do one thing and do it well. Rather than having one function that tries to do many things (for example, a function that loads data, cleans it, and calculates some statistics), it's better to have separate, smaller functions for each of these tasks. This makes your code easier to understand, test, and maintain.

   e. __Dependency Inversion Principle__: When working with functions, this principle means that you should depend on arguments, not on global variables or complex concrete data structures. For example, if you have a function that operates on a list of numbers, the function should take the list as an argument rather than depending on a specific list that exists somewhere else in your code. This makes your function more flexible and easier to reuse in different contexts.

6. __Explicit is better than Implicit__: This principle from the Zen of Python emphasizes the importance of being explicit in your code, as it leads to code that's easier to understand and debug.

7. __Error handling and testing__: Expect errors and handle them gracefully. Always validate your inputs, and write tests to make sure your code works as intended.

8. __Modular Programming__: Split your code into smaller, independent sections (modules) which can be easily managed, debugged, and understood.

9. __Code Documentation__: This is one of the key aspects of software development, and we apply it meticulously to our analysis. It makes the code easy to understand and maintain. Use comments and docstrings wisely to provide context and explanation for what your code is doing.

10. __Iterative Development__: Coding is a process, not a one-time event. Write a little, test a little, and then refine your code based on the results. This incremental approach allows you to spot and fix issues early in the process.

11. __Code Reviews__: We peer review our code. This is not just for catching bugs, but also for sharing knowledge and promoting best practices among the team.

12. __Data Validation__: Always clean and validate the data you work with. Don't assume the data comes clean, or is always well formatted and consistent.

13. __Consistency__: Be consistent in your coding style and conventions. This makes your code easier to read and understand. We use Black to format our code, and we aim to follow Google's Python Style Guide in terms of overall approach and for Docstrings.

14. __Avoid Premature Optimisation__: Don't try to make your code super efficient at the expense of readability and simplicity, unless you have a clear reason to do so.

__All of the above are guidelines and principles, not strict rules.__