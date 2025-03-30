This project implements an intelligent Recruiter Agent designed to automate the recruitment process for Python Developer positions. The agent utilizes advanced Natural Language Processing (NLP) techniques to analyze and summarize candidate resumes in PDF format, assess their experience level (Senior, Mid-Level, Entry-Level), and determine their suitability for the position. Based on the analysis, it automatically sends an email to candidates with either a Rejection or an HR Interview invitation.

Features
Resume Analysis: The agent processes resumes submitted in PDF format, extracting relevant information such as skills, experience, and educational background.

Experience Categorization: The agent categorizes candidates into three levels based on their experience:

Senior: Highly experienced candidates with extensive skills and expertise.

Mid-Level: Candidates with moderate experience and relevant skills.

Entry-Level: Candidates who are relatively new to the field or have limited experience.

Fit for Position: The agent evaluates whether a candidate's profile aligns with the requirements of the Python Developer position, considering factors such as skill sets, experience, and job expectations.

Automated Email Notifications: Based on the analysis, the agent sends automated emails:

Rejection Email: For candidates who do not meet the criteria.

HR Interview Invitation: For candidates deemed suitable for the role and ready for the next stage in the hiring process.

Technologies Used
Langchain: A powerful framework used to facilitate language model integration for analyzing and processing candidate resumes.

Langgraph: A library used for graph-based processing of information, which helps in understanding and structuring the data for decision-making.

PDF Parsing: Extracting information from PDF resumes for processing.

Email Automation: Sending personalized emails to candidates based on the evaluation results.

How It Works
Resume Submission: Candidates submit their resumes in PDF format.

Resume Parsing: The agent extracts key information from the resumes (skills, experience, education, etc.) using advanced parsing techniques.

Analysis and Categorization: The agent categorizes the candidate as Senior, Mid-Level, or Entry-Level based on the extracted data and compares their profile against the job description.

Decision Making: The agent determines whether the candidate is a good fit for the position.

Email Notification: The agent automatically sends out emails based on the decision:

Rejection for candidates who do not meet the criteria.

HR Interview invitation for candidates who are a good match for the position.

