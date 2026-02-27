# Reflection on Working with AI

At first, I underestimated how hard scraping and cleaning unstructured HTML could be. While the BCIT website looks organized visually, the underlying HTML structure required careful inspection. I had to learn how to identify patterns in course codes, locate prerequisite text sections, and extract only the relevant content  at the same time ignoring navigation and formatting elements.

Chapgpt (AI) was helpful in suggesting a logical pipeline: download HTML → parse content → structure into a DataFrame → visualize relationships. On the other side,  its not just copy and paste process. I had to debug errors, adjust regular expressions for course code extraction, and verify that the prerequisite relationships were correctly interpreted.

One challenge that I was realizing that scraped content is messy by default. Sections are inconsistent, text formatting varies, and some expected data is embedded in longer paragraphs. This makes me to think critically about how to transform free text into structured variables.

Another thought was understanding how graph modeling can represent learning progession. Showing prerequisites as arrows between courses made the structure easier to understand than just listing it in a table.

Overall, using Chaptgpt (AI) did not stop my by thinking and doing the action. Instead, it accelerated the workflow while requiring me to verify logic, correct mistakes, and understand each step of the process. I learned that AI is effective when used as a collaborator rather than an answer generator.


In this project I understanding and learn that: 
- Web scraping fundamentals
- Cleaning unstructured text
- Transforming HTML into structured datasets
- Data visualization of relationships
