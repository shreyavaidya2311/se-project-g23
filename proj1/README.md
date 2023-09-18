## Part 1: Grading five projects based on the given rubrics
- <a href="https://github.com/shreyavaidya2311/se-project-g23/blob/main/proj1/Slash_f_Grading.csv">Slash (f) Grading Sheet</a>
- <a href="https://github.com/shreyavaidya2311/se-project-g23/blob/main/proj1/Dollar_Bot%20Grading.csv">Dollar Bot (D) Grading Sheet</a>
- <a href="https://github.com/shreyavaidya2311/se-project-g23/blob/main/proj1/WolfTrack3.0%20Grading.csv">Wolf Track 3.0 (p) Grading Sheet</a>
- <a href="https://github.com/shreyavaidya2311/se-project-g23/blob/main/proj1/Slash_c_Grading.csv">Slash (c) Grading Sheet</a>
- <a href="https://github.com/shreyavaidya2311/se-project-g23/blob/main/proj1/86NoMore_A_Grading.csv">86 no more (A) Grading Sheet</a>

## Part 2: YouTube Video showing the Running Application (Wolf Track 3.0)
<a href="https://www.youtube.com/watch?v=4dyQ-rKDXP8">YouTube Link</a>

## Part 3: An Essay on the Analysis of Wolf Track 3.0 
<div align="justify">In this essay, our aim has been to rigorously analyze a software engineering project, namely ‘Wolf Track 3.0’, an application built for networking and resume analysis. We have attempted to critique and suggest improvements in various verticals, ranging from documentation, to code readability and support. Throughout the essay, we identify aspects of the project which deviate from industry standards or best practices, and subsequently suggest improvements. We implicitly commit to implementing these suggestions in the next phase of this project.
</div>
<br/>
<div align="justify">
During the installation process of the project WolfTrack 3.0, we encountered several challenges that made the experience notably challenging. Firstly, we faced difficulties related to dependency management. Managing dependencies within a virtual environment was unfamiliar terrain, and we often encountered errors such as "ModuleNotFoundError" when trying to import essential libraries like Flask and Flask-RESTful. These issues resulted from not having all the required packages installed in my virtual environment, which could have been avoided by maintaining a comprehensive requirements.txt file from the start. This file would have listed all project dependencies, making it easier to install them collectively and avoid version conflicts. Furthermore, we ran into problems with compatibility, particularly when trying to use specific versions of libraries like scikit-learn. It was frustrating to encounter "No matching distribution found" errors, emphasizing the need to thoroughly research compatibility between Python versions and package versions. Clear documentation, community forums, or consulting project README files for compatibility notes would have been helpful in avoiding these roadblocks. Lastly, we faced an unexpected issue when dealing with SSL certificate errors during NLTK stopwords download. Although this was documented in the README file but could have been made more clear. </div>

<br/>
<div align="justify">
The documentation could benefit from more detailed information on configuring the application. For example, it should include instructions on setting up database connections, AWS integration, and other essential configurations. Clear examples and code snippets can be invaluable for developers trying to configure the system correctly. While the documentation briefly mentions the application's features, it lacks detailed usage examples. Providing examples of how to use various features, such as resume parsing and job recommendation, can help developers understand how to leverage the functionality effectively. The section on running the application in Docker is present, but it could be more comprehensive. Clearer steps, explanations of the Dockerfile, and guidance on image deployment and tagging would be beneficial for developers interested in containerization. While there is a link to contributing guidelines, it would be helpful to provide clear information on how to contribute, submit bug reports, and engage with the project's development community. </div>

<br/>
<div align="justify">
Regarding the demo video, while it was well-produced and provided a good overview of the project's functionalities, it missed an opportunity to engage potential contributors. To make the video more enticing for individuals interested in contributing to the project, it could include segments highlighting the project's impact, its potential for growth, and the exciting challenges that contributors could tackle. </div>

<br/>
<div align="justify">
The code of this project appears to be fairly modular. However, what we noticed was that each function was used only for the singular purpose for which it was coded. This causes inflation of code. We can improve upon this by writing small, generic scripts (such as a generic database write scripts for instance), which can be called by multiple functions throughout the code simply by passing varying values. Furthermore, the code appears to be well formatted, and standard code formatters have been used. However, the source code files are heavily lacking in meaningful comments and in some places, any comments at all.. The docs folder of this project, on the other hand, is quite thoroughly written. It contains descriptions of all functionalities and use cases. </div>

<br/>
<div align="justify">
This project has included a folder for unit tests which contain tests that cover most of the modules. The project, however, has not included any deployment instructions, and therefore does not have any code written for load testing etc. This is one aspect in which improvements may be possible, since scalability is one of the most important aspects of a product. Also, there does not appear to be an automated test suite for this project. This is another feature that can be added which will substantially improve the contributing experience and make the code that much more reliable.</div>

<br/>
<div align="justify">
Additionally, in the next phase of this project, we plan to incorporate the following practices.
We will create a more descriptive video with various examples of how users can leverage all the features in the application. Our aim will be to have shorter release cycles over a longer duration, which will include in depth discussions of issues that are raised along with meaningful comments on how it can be resolved before closing the issue. We will comprehensively document each class/function. Our goal will be to create a simpler and more open communication flow between users, owners and contributors. For this, we will create a chat channel. We will also enact a ticketing system to raise issues / report bugs to manage and deal with issues effectively.</div>

<br/>
<div align="justify">
In conclusion, the evaluation of the WolfTrack 3.0 project reveals areas for enhancement. The installation process faced dependency and compatibility challenges, highlighting the need for better documentation and comprehensive requirements management. Documentation should include configuration details, usage examples, and Docker deployment guidance, with clearer contribution instructions. While the codebase is modular, it lacks adequate comments, crucial for code understanding and collaboration. Front-end improvements, such as user authentication and interface simplification, are recommended. Back-end development is proportional to the project's scale. Testing could be enhanced with deployment instructions and automated testing. Addressing these issues will make WolfTrack 3.0 more robust and user-friendly, encouraging collaboration and reliability.</div>
