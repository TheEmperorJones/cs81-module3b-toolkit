# Reflections on *math.js*

- What patterns did I notice?
    - Momemtum occurs once you get going in such a project.  Similar structure increases speed across functions.
    - Care must be taken to avoid excessive speed, i.e. speed at the cost of correctness and intention.
    - This happens at the code level within the *math.js* file, but also at the console level when adding, committing and pushing code; precision is required or you get hung up.  This is also fortunate, because imagine if it accepted nearly correct commands and tried to guess at what you intended (like generative A.I. can)--it would result in chaos.

- What logic challenged my thinking?
    - The biggest challenge was chunking bite size operations.  I had wanted to take the opportunity to do statistical operations like finding measures of central tendency, but this was too challenging at this stage.
    - I also struggled to understand how to conveniently test the code.  After struggling to test via console and CLI, I eventually recalled the indx.html approach from Module 1, and created such a file in my VSCode explorer, modifying it to fit the use case, including renaming the reference *math.js* file and adjusting displayed text to aid a tester as to context.  This helped a lot--this is not logic per se, but process; but a process built on what came earlier in the course.  I feel this is a valuable referent as we proceed.

- How might this kind of toolkit be used in the real world?
    - This type of toolkit would be valuable in any ongoing project.
    - Specific use cases include staging upcoming releases in a kind of library of future functionality.
    - I could imagine data scientists coding very specific approaches to acquiring, utilizing, shaping, analyzing and outputting data, handcrafted to meet their immediate needs, but also equipped to handle expected adjustments in the future.
    - It allows a coder to batch a lot of processes and keep them central; not unlike CSS files being centralized to handle formatting concerns, such a toolkit could be the repository of all the necessary muscular stuff, the doing.