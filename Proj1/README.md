# [Slash working video](https://youtu.be/o-og4ENrjwc)

# Project Troubleshooting 

The project finalized was Slash, a tool that scrapes the most popular e-commerce websites to get the best deals on the searched items. As students with a tight budget, the project's use cases appealed to us. Also, we identified multiple avenues through which the project could be improved, prompting us to choose this project.

Before attempting to run the project, we thought how hard it could be to run a 2-year-old piece of software. Our 2-hour group meeting turned into a 6-hour scramble to get the project running. Phew! At least we were able to get it running. While working, we identified areas where improvements and better practices can be implemented. We hope to reflect on these challenges and carry forward these experiences to ensure a smooth development process.

Some of the hurdles faced and our approach to them are:

## 1. **Dependency Management and Versioning:**

Installing dependencies and managing their versions proved challenging. The specific issue was when installing Pandas due to an older version causing C++ recognition errors, highlighting the importance of precise version management. This pain could have been mitigated by maintaining a support section where errors like this can be listed along with their solution approach. 

This semester, we plan on creating a well-documented and version-controlled requirements file listing the latest versions of dependencies. Also, make a FAQ.md(or some support file) listing possible errors and feasible solutions. 

## 2. **Module Import and Path Configuration:**

We encountered the "no module named src" error while running `main.py` which exposed a need for better path configuration. Managing imports and ensuring the correct paths are utilized is crucial for a project's smooth execution. Appending the source path to `sys.path` was a viable solution to address this issue. We aim to proactively establish a standardized approach to handle module imports and path configuration.

We will maintain a clear folder structure and follow Python's best practices for module organization. Additionally, we will set up environment variables or use configuration files to manage paths dynamically, ensuring a more streamlined development experience.

## 3. **Runtime Errors and Package Compatibility:**

The runtime TypeError encountered with Streamlit due to incompatible protobuf package versions underscored the same issue as 1. 
Similar to the approach in problem 1, the project documentation will include information to guide developers and streamline the setup process.

## 4. **Error Logging and Debugging:**

One significant challenge was the need for error logging, making it difficult to identify and troubleshoot issues effectively. Proper error handling and logging are crucial for identifying and resolving errors promptly.

We aim to implement comprehensive error-logging mechanisms. We will utilize Python's logging framework to log errors and relevant information, aiding in quick diagnosis and resolution of issues during development and production.

## 5. **Module Functionality and Reliability:**

The partial functioning of specific modules, such as eBay, Costco, and Amazon, shed light on the need for rigorous testing and validation of third-party integrations. Ensuring all modules work as expected and consistently fetch the required data is vital.

For this phase, we will invest additional effort into comprehensive testing of all modules, simulating various scenarios to ensure their reliability and effectiveness. We will establish clear acceptance criteria and conduct thorough testing against these criteria, addressing any issues or inconsistencies promptly.

## 6. **Additional improvements:**

We plan to add an analysis graph that shows an illustrated comparison of the price of a product across the platforms where the product is listed. We also want to add a mechanism to filter/sort the results. 
 
In conclusion, the challenges encountered during this project have provided valuable insights and learnings. We are committed to implementing these identified improvements in this phase. These proactive measures will contribute to a more efficient and successful execution of Slash.
