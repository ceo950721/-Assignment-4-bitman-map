# Reflection on Working with AI

This project was my first experience using AI assistance in a structured data wrangling workflow.

At first, I underestimated how complex scraping and cleaning unstructured HTML could be. While the BCIT website looks organized visually, the underlying HTML structure required careful inspection. I had to learn how to identify patterns in course codes, locate prerequisite text sections, and extract only the relevant content while ignoring navigation and formatting elements.

AI was helpful in suggesting a logical pipeline: download HTML → parse content → structure into a DataFrame → visualize relationships. However, it was not a simple copy-paste process. I had to debug errors, adjust regular expressions for course code extraction, and verify that the prerequisite relationships were correctly interpreted.

One challenge was realizing that scraped content is messy by default. Sections are inconsistent, text formatting varies, and some expected data is embedded in longer paragraphs. This forced me to think critically about how to transform free text into structured variables.

Another insight was understanding how graph modeling (using NetworkX) can represent academic dependencies. Visualizing prerequisites as directed edges made the data more meaningful than simply storing it in a table.

Overall, using AI did not replace my thinking. Instead, it accelerated the workflow while requiring me to verify logic, correct mistakes, and understand each step of the process. I learned that AI is most effective when used as a collaborator rather than an answer generator.

If I extended this project further, I would scale it to scrape multiple course outlines automatically and build a full Bitman program prerequisite network.

This project strengthened my understanding of:
- Web scraping fundamentals
- Cleaning unstructured text
- Transforming HTML into structured datasets
- Data visualization of relationships
