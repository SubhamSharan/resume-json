# Resume in JSON Format

## Task Description

You are given a resume in plain text format. Your task is to parse the resume and extract the relevant information into a structured JSON format. The JSON should contain the following fields:

- Name
- Contact Information (Email, Phone, LinkedIn, GitHub)
- Education (Degree, University, Graduation Year)
- Experience (Job Title, Company, Start Date, End Date, Description)
- Projects (Title, Description, Tools and Technologies)
- Skills
- Certifications

## Provided Resume

Subham Sharan
Roll No: RA2111003010511
B.Tech in Computer Science and Engineering
SRM Institute of Science and Technology, Kattankulathur

+91-8880446545
subham278119@gmail.com
sb2156@srmist.edu.in
https://github.com/SubhamSharan
https://www.linkedin.com/in/subham-sharan-5a3816a0/

Education:
SRM Institute of Science and Technology, Kattankulathur (2021 - 2025)

B.Tech in Computer Science and Engineering, Current CGPA: 8.3
Navy Children School, Mumbai (2019 - 2021)
XII High School - CBSE, Percentage: 91
Navy Children School, Mumbai (2019)
X High School - CBSE, Percentage: 92.4
Experience:
Machine Learning Research Intern, IIT Bombay (01 Feb 2024 - Present)

Contributing to the development of a General Clinical Survey Tool, applying ML expertise for comprehensive analysis and improvement.
Web Development Intern, Elcome Integrated Systems Pvt. Ltd. (28 Nov 2023 - 27 Nov 2024)

Collaborated with the design team to create visually appealing websites, ensuring a consistent and cohesive brand image. Developed a full-stack project, a clone of Netflix.
Projects:
Anemia Detection

Developed a system to detect anemia based on the color of the conjunctiva.
Tools and technologies: Python, Machine Learning, Django Rest API
Netflix Clone

Replicated the core functionalities of Netflix.
Tools and technologies: HTML, CSS, JavaScript
Wine Quality Predictor

Predicted wine quality using machine learning.
Tools and technologies: Python, Matplotlib, NumPy, Pandas, Neural Networks
Skills:
C, C++, Python, HTML, CSS, JavaScript, Java, GitHub, Machine Learning, REST API, Django, Neural Networks, SQL, Scikit-learn, TensorFlow, Keras, OpenCV, SciPy, PyTorch, Selenium, Web Scraping, Data Analysis

Certifications:
Oracle Certified Foundations Associate - ORACLE (24 June 2024)
AIML Virtual Internship - AICTE (18 Mar 2024)
Machine Learning in Production - Deeplearning.ai (5 May 2024)
AWS Academy Machine Learning Foundations [5635J] - Amazon Web Services (16 Oct 2023)
Networking Basics - CISCO (29 April 2023)


## Output JSON

```json
{
  "Name": "Subham Sharan",
  "Contact Information": {
    "Email": ["subham278119@gmail.com", "sb2156@srmist.edu.in"],
    "Phone": "+91-8880446545",
    "LinkedIn": "https://www.linkedin.com/in/subham-sharan-5a3816a0/",
    "GitHub": "https://github.com/SubhamSharan"
  },
  "Education": [
    {
      "Degree": "B.Tech in Computer Science and Engineering",
      "University": "SRM Institute of Science and Technology, Kattankulathur",
      "Graduation Year": "2025",
      "Details": "Current CGPA: 8.3"
    },
    {
      "Degree": "XII High School - CBSE",
      "University": "Navy Children School, Mumbai",
      "Graduation Year": "2021",
      "Details": "Percentage: 91"
    },
    {
      "Degree": "X High School - CBSE",
      "University": "Navy Children School, Mumbai",
      "Graduation Year": "2019",
      "Details": "Percentage: 92.4"
    }
  ],
  "Experience": [
    {
      "Job Title": "Machine Learning Research Intern",
      "Company": "IIT Bombay",
      "Start Date": "01 Feb 2024",
      "End Date": "Present",
      "Description": "Contributing to the development of a General Clinical Survey Tool, applying ML expertise for comprehensive analysis and improvement."
    },
    {
      "Job Title": "Web Development Intern",
      "Company": "Elcome Integrated Systems Pvt. Ltd.",
      "Start Date": "28 Nov 2023",
      "End Date": "27 Nov 2024",
      "Description": "Collaborated with the design team to create visually appealing websites, ensuring a consistent and cohesive brand image. Developed a full-stack project, a clone of Netflix."
    }
  ],
  "Projects": [
    {
      "Title": "Anemia Detection",
      "Description": "Developed a system to detect anemia based on the color of the conjunctiva.",
      "Tools and Technologies": ["Python", "Machine Learning", "Django Rest API"]
    },
    {
      "Title": "Netflix Clone",
      "Description": "Replicated the core functionalities of Netflix.",
      "Tools and Technologies": ["HTML", "CSS", "JavaScript"]
    },
    {
      "Title": "Wine Quality Predictor",
      "Description": "Predicted wine quality using machine learning.",
      "Tools and Technologies": ["Python", "Matplotlib", "NumPy", "Pandas", "Neural Networks"]
    }
  ],
  "Skills": [
    "C", "C++", "Python", "HTML", "CSS", "JavaScript", "Java", "GitHub", "Machine Learning", 
    "REST API", "Django", "Neural Networks", "SQL", "Scikit-learn", "TensorFlow", "Keras", 
    "OpenCV", "SciPy", "PyTorch", "Selenium", "Web Scraping", "Data Analysis"
  ],
  "Certifications": [
    {
      "Title": "Oracle Certified Foundations Associate",
      "Issuer": "ORACLE",
      "Date": "24 June 2024"
    },
    {
      "Title": "AIML Virtual Internship",
      "Issuer": "AICTE",
      "Date": "18 Mar 2024"
    },
    {
      "Title": "Machine Learning in Production",
      "Issuer": "Deeplearning.ai",
      "Date": "5 May 2024"
    },
    {
      "Title": "AWS Academy Machine Learning Foundations",
      "Issuer": "Amazon Web Services",
      "Date": "16 Oct 2023",
      "ID": "[5635J]"
    },
    {
      "Title": "Networking Basics",
      "Issuer": "CISCO",
      "Date": "29 April 2023"
    }
  ]
}


You are given a resume in plain text format. Your task is to parse the resume and extract the relevant information into a structured JSON format. The JSON should contain the following fields:

- Name
- Contact Information (Email, Phone, LinkedIn, GitHub)
- Education (Degree, University, Graduation Year)
- Experience (Job Title, Company, Start Date, End Date, Description)
- Projects (Title, Description, Tools and Technologies)
- Skills
- Certifications

Here is the resume text:
Subham Sharan
Roll No: RA2111003010511
B.Tech in Computer Science and Engineering
SRM Institute of Science and Technology, Kattankulathur

+91-8880446545
subham278119@gmail.com
sb2156@srmist.edu.in
https://github.com/SubhamSharan
https://www.linkedin.com/in/subham-sharan-5a3816a0/

Education:
SRM Institute of Science and Technology, Kattankulathur (2021 - 2025)
- B.Tech in Computer Science and Engineering, Current CGPA: 8.3
Navy Children School, Mumbai (2019 - 2021)
- XII High School - CBSE, Percentage: 91
Navy Children School, Mumbai (2019)
- X High School - CBSE, Percentage: 92.4

Experience:
Machine Learning Research Intern, IIT Bombay (01 Feb 2024 - Present)
- Contributing to the development of a General Clinical Survey Tool, applying ML expertise for comprehensive analysis and improvement.

Web Development Intern, Elcome Integrated Systems Pvt. Ltd. (28 Nov 2023 - 27 Nov 2024)
- Collaborated with the design team to create visually appealing websites, ensuring a consistent and cohesive brand image. Developed a full-stack project, a clone of Netflix.

Projects:
Anemia Detection
- Developed a system to detect anemia based on the color of the conjunctiva.
- Tools and technologies: Python, Machine Learning, Django Rest API

Netflix Clone
- Replicated the core functionalities of Netflix.
- Tools and technologies: HTML, CSS, JavaScript

Wine Quality Predictor
- Predicted wine quality using machine learning.
- Tools and technologies: Python, Matplotlib, NumPy, Pandas, Neural Networks

Skills:
C, C++, Python, HTML, CSS, JavaScript, Java, GitHub, Machine Learning, REST API, Django, Neural Networks, SQL, Scikit-learn, TensorFlow, Keras, OpenCV, SciPy, PyTorch, Selenium, Web Scraping, Data Analysis

Certifications:
Oracle Certified Foundations Associate - ORACLE (24 June 2024)
AIML Virtual Internship - AICTE (18 Mar 2024)
Machine Learning in Production - Deeplearning.ai (5 May 2024)
AWS Academy Machine Learning Foundations [5635J] - Amazon Web Services (16 Oct 2023)
Networking Basics - CISCO (29 April 2023)
ChatGPT
Here is the structured JSON format based on the provided resume text:

json
Copy code
{
  "Name": "Subham Sharan",
  "Contact Information": {
    "Email": ["subham278119@gmail.com", "sb2156@srmist.edu.in"],
    "Phone": "+91-8880446545",
    "LinkedIn": "https://www.linkedin.com/in/subham-sharan-5a3816a0/",
    "GitHub": "https://github.com/SubhamSharan"
  },
  "Education": [
    {
      "Degree": "B.Tech in Computer Science and Engineering",
      "University": "SRM Institute of Science and Technology, Kattankulathur",
      "Graduation Year": "2025",
      "Details": "Current CGPA: 8.3"
    },
    {
      "Degree": "XII High School - CBSE",
      "University": "Navy Children School, Mumbai",
      "Graduation Year": "2021",
      "Details": "Percentage: 91"
    },
    {
      "Degree": "X High School - CBSE",
      "University": "Navy Children School, Mumbai",
      "Graduation Year": "2019",
      "Details": "Percentage: 92.4"
    }
  ],
  "Experience": [
    {
      "Job Title": "Machine Learning Research Intern",
      "Company": "IIT Bombay",
      "Start Date": "01 Feb 2024",
      "End Date": "Present",
      "Description": "Contributing to the development of a General Clinical Survey Tool, applying ML expertise for comprehensive analysis and improvement."
    },
    {
      "Job Title": "Web Development Intern",
      "Company": "Elcome Integrated Systems Pvt. Ltd.",
      "Start Date": "28 Nov 2023",
      "End Date": "27 Nov 2024",
      "Description": "Collaborated with the design team to create visually appealing websites, ensuring a consistent and cohesive brand image. Developed a full-stack project, a clone of Netflix."
    }
  ],
  "Projects": [
    {
      "Title": "Anemia Detection",
      "Description": "Developed a system to detect anemia based on the color of the conjunctiva.",
      "Tools and Technologies": ["Python", "Machine Learning", "Django Rest API"]
    },
    {
      "Title": "Netflix Clone",
      "Description": "Replicated the core functionalities of Netflix.",
      "Tools and Technologies": ["HTML", "CSS", "JavaScript"]
    },
    {
      "Title": "Wine Quality Predictor",
      "Description": "Predicted wine quality using machine learning.",
      "Tools and Technologies": ["Python", "Matplotlib", "NumPy", "Pandas", "Neural Networks"]
    }
  ],
  "Skills": [
    "C", "C++", "Python", "HTML", "CSS", "JavaScript", "Java", "GitHub", "Machine Learning", 
    "REST API", "Django", "Neural Networks", "SQL", "Scikit-learn", "TensorFlow", "Keras", 
    "OpenCV", "SciPy", "PyTorch", "Selenium", "Web Scraping", "Data Analysis"
  ],
  "Certifications": [
    {
      "Title": "Oracle Certified Foundations Associate",
      "Issuer": "ORACLE",
      "Date": "24 June 2024"
    },
    {
      "Title": "AIML Virtual Internship",
      "Issuer": "AICTE",
      "Date": "18 Mar 2024"
    },
    {
      "Title": "Machine Learning in Production",
      "Issuer": "Deeplearning.ai",
      "Date": "5 May 2024"
    },
    {
      "Title": "AWS Academy Machine Learning Foundations",
      "Issuer": "Amazon Web Services",
      "Date": "16 Oct 2023",
      "ID": "[5635J]"
    },
    {
      "Title": "Networking Basics",
      "Issuer": "CISCO",
      "Date": "29 April 2023"
    }
  ]
}
This JSON format captures all the relevant information from the resume text in a structured and organized way.

make a  github repo out of this
ChatGPT
To create a GitHub repository for this JSON-formatted resume, follow these steps:

Create a GitHub Repository:

Go to GitHub and log in to your account.
Click on the "+" icon in the top right corner and select "New repository".
Name the repository (e.g., resume-json), add a description (optional), and choose the repository visibility (public or private).
Click "Create repository".
Clone the Repository Locally:
Open your terminal or command prompt and clone the repository to your local machine:

sh
Copy code
git clone https://github.com/YOUR_USERNAME/resume-json.git
cd resume-json
Add the JSON File:

Create a new file named resume.json in the repository directory.
Copy and paste the JSON content into this file and save it.
sh
Copy code
echo '{
  "Name": "Subham Sharan",
  "Contact Information": {
    "Email": ["subham278119@gmail.com", "sb2156@srmist.edu.in"],
    "Phone": "+91-8880446545",
    "LinkedIn": "https://www.linkedin.com/in/subham-sharan-5a3816a0/",
    "GitHub": "https://github.com/SubhamSharan"
  },
  "Education": [
    {
      "Degree": "B.Tech in Computer Science and Engineering",
      "University": "SRM Institute of Science and Technology, Kattankulathur",
      "Graduation Year": "2025",
      "Details": "Current CGPA: 8.3"
    },
    {
      "Degree": "XII High School - CBSE",
      "University": "Navy Children School, Mumbai",
      "Graduation Year": "2021",
      "Details": "Percentage: 91"
    },
    {
      "Degree": "X High School - CBSE",
      "University": "Navy Children School, Mumbai",
      "Graduation Year": "2019",
      "Details": "Percentage: 92.4"
    }
  ],
  "Experience": [
    {
      "Job Title": "Machine Learning Research Intern",
      "Company": "IIT Bombay",
      "Start Date": "01 Feb 2024",
      "End Date": "Present",
      "Description": "Contributing to the development of a General Clinical Survey Tool, applying ML expertise for comprehensive analysis and improvement."
    },
    {
      "Job Title": "Web Development Intern",
      "Company": "Elcome Integrated Systems Pvt. Ltd.",
      "Start Date": "28 Nov 2023",
      "End Date": "27 Nov 2024",
      "Description": "Collaborated with the design team to create visually appealing websites, ensuring a consistent and cohesive brand image. Developed a full-stack project, a clone of Netflix."
    }
  ],
  "Projects": [
    {
      "Title": "Anemia Detection",
      "Description": "Developed a system to detect anemia based on the color of the conjunctiva.",
      "Tools and Technologies": ["Python", "Machine Learning", "Django Rest API"]
    },
    {
      "Title": "Netflix Clone",
      "Description": "Replicated the core functionalities of Netflix.",
      "Tools and Technologies": ["HTML", "CSS", "JavaScript"]
    },
    {
      "Title": "Wine Quality Predictor",
      "Description": "Predicted wine quality using machine learning.",
      "Tools and Technologies": ["Python", "Matplotlib", "NumPy", "Pandas", "Neural Networks"]
    }
  ],
  "Skills": [
    "C", "C++", "Python", "HTML", "CSS", "JavaScript", "Java", "GitHub", "Machine Learning",
    "REST API", "Django", "Neural Networks", "SQL", "Scikit-learn", "TensorFlow", "Keras",
    "OpenCV", "SciPy", "PyTorch", "Selenium", "Web Scraping", "Data Analysis"
  ],
  "Certifications": [
    {
      "Title": "Oracle Certified Foundations Associate",
      "Issuer": "ORACLE",
      "Date": "24 June 2024"
    },
    {
      "Title": "AIML Virtual Internship",
      "Issuer": "AICTE",
      "Date": "18 Mar 2024"
    },
    {
      "Title": "Machine Learning in Production",
      "Issuer": "Deeplearning.ai",
      "Date": "5 May 2024"
    },
    {
      "Title": "AWS Academy Machine Learning Foundations",
      "Issuer": "Amazon Web Services",
      "Date": "16 Oct 2023",
      "ID": "[5635J]"
    },
    {
      "Title": "Networking Basics",
      "Issuer": "CISCO",
      "Date": "29 April 2023"
    }
  ]
}' > resume.json
Commit and Push the Changes:

Add the file to the staging area, commit the changes, and push to the repository:
sh
Copy code
git add resume.json
git commit -m "Add resume in JSON format"
git push origin main
Now, your JSON resume is available in your GitHub repository. You can share the link to the repository or collaborate with others by giving them access to this repository.

In the readme file give me the prompt I gave to you and explain the task
ChatGPT
Sure! Here's a README.md file that includes the prompt you provided and an explanation of the task:

markdown
Copy code
# Resume in JSON Format

## Task Description

You are given a resume in plain text format. Your task is to parse the resume and extract the relevant information into a structured JSON format. The JSON should contain the following fields:

- Name
- Contact Information (Email, Phone, LinkedIn, GitHub)
- Education (Degree, University, Graduation Year)
- Experience (Job Title, Company, Start Date, End Date, Description)
- Projects (Title, Description, Tools and Technologies)
- Skills
- Certifications

## Provided Resume

Subham Sharan
Roll No: RA2111003010511
B.Tech in Computer Science and Engineering
SRM Institute of Science and Technology, Kattankulathur

+91-8880446545
subham278119@gmail.com
sb2156@srmist.edu.in
https://github.com/SubhamSharan
https://www.linkedin.com/in/subham-sharan-5a3816a0/

Education:
SRM Institute of Science and Technology, Kattankulathur (2021 - 2025)

B.Tech in Computer Science and Engineering, Current CGPA: 8.3
Navy Children School, Mumbai (2019 - 2021)
XII High School - CBSE, Percentage: 91
Navy Children School, Mumbai (2019)
X High School - CBSE, Percentage: 92.4
Experience:
Machine Learning Research Intern, IIT Bombay (01 Feb 2024 - Present)

Contributing to the development of a General Clinical Survey Tool, applying ML expertise for comprehensive analysis and improvement.
Web Development Intern, Elcome Integrated Systems Pvt. Ltd. (28 Nov 2023 - 27 Nov 2024)

Collaborated with the design team to create visually appealing websites, ensuring a consistent and cohesive brand image. Developed a full-stack project, a clone of Netflix.
Projects:
Anemia Detection

Developed a system to detect anemia based on the color of the conjunctiva.
Tools and technologies: Python, Machine Learning, Django Rest API
Netflix Clone

Replicated the core functionalities of Netflix.
Tools and technologies: HTML, CSS, JavaScript
Wine Quality Predictor

Predicted wine quality using machine learning.
Tools and technologies: Python, Matplotlib, NumPy, Pandas, Neural Networks
Skills:
C, C++, Python, HTML, CSS, JavaScript, Java, GitHub, Machine Learning, REST API, Django, Neural Networks, SQL, Scikit-learn, TensorFlow, Keras, OpenCV, SciPy, PyTorch, Selenium, Web Scraping, Data Analysis

Certifications:
Oracle Certified Foundations Associate - ORACLE (24 June 2024)
AIML Virtual Internship - AICTE (18 Mar 2024)
Machine Learning in Production - Deeplearning.ai (5 May 2024)
AWS Academy Machine Learning Foundations [5635J] - Amazon Web Services (16 Oct 2023)
Networking Basics - CISCO (29 April 2023)

bash
Copy code

## Output JSON

```json
{
  "Name": "Subham Sharan",
  "Contact Information": {
    "Email": ["subham278119@gmail.com", "sb2156@srmist.edu.in"],
    "Phone": "+91-8880446545",
    "LinkedIn": "https://www.linkedin.com/in/subham-sharan-5a3816a0/",
    "GitHub": "https://github.com/SubhamSharan"
  },
  "Education": [
    {
      "Degree": "B.Tech in Computer Science and Engineering",
      "University": "SRM Institute of Science and Technology, Kattankulathur",
      "Graduation Year": "2025",
      "Details": "Current CGPA: 8.3"
    },
    {
      "Degree": "XII High School - CBSE",
      "University": "Navy Children School, Mumbai",
      "Graduation Year": "2021",
      "Details": "Percentage: 91"
    },
    {
      "Degree": "X High School - CBSE",
      "University": "Navy Children School, Mumbai",
      "Graduation Year": "2019",
      "Details": "Percentage: 92.4"
    }
  ],
  "Experience": [
    {
      "Job Title": "Machine Learning Research Intern",
      "Company": "IIT Bombay",
      "Start Date": "01 Feb 2024",
      "End Date": "Present",
      "Description": "Contributing to the development of a General Clinical Survey Tool, applying ML expertise for comprehensive analysis and improvement."
    },
    {
      "Job Title": "Web Development Intern",
      "Company": "Elcome Integrated Systems Pvt. Ltd.",
      "Start Date": "28 Nov 2023",
      "End Date": "27 Nov 2024",
      "Description": "Collaborated with the design team to create visually appealing websites, ensuring a consistent and cohesive brand image. Developed a full-stack project, a clone of Netflix."
    }
  ],
  "Projects": [
    {
      "Title": "Anemia Detection",
      "Description": "Developed a system to detect anemia based on the color of the conjunctiva.",
      "Tools and Technologies": ["Python", "Machine Learning", "Django Rest API"]
    },
    {
      "Title": "Netflix Clone",
      "Description": "Replicated the core functionalities of Netflix.",
      "Tools and Technologies": ["HTML", "CSS", "JavaScript"]
    },
    {
      "Title": "Wine Quality Predictor",
      "Description": "Predicted wine quality using machine learning.",
      "Tools and Technologies": ["Python", "Matplotlib", "NumPy", "Pandas", "Neural Networks"]
    }
  ],
  "Skills": [
    "C", "C++", "Python", "HTML", "CSS", "JavaScript", "Java", "GitHub", "Machine Learning", 
    "REST API", "Django", "Neural Networks", "SQL", "Scikit-learn", "TensorFlow", "Keras", 
    "OpenCV", "SciPy", "PyTorch", "Selenium", "Web Scraping", "Data Analysis"
  ],
  "Certifications": [
    {
      "Title": "Oracle Certified Foundations Associate",
      "Issuer": "ORACLE",
      "Date": "24 June 2024"
    },
    {
      "Title": "AIML Virtual Internship",
      "Issuer": "AICTE",
      "Date": "18 Mar 2024"
    },
    {
      "Title": "Machine Learning in Production",
      "Issuer": "Deeplearning.ai",
      "Date": "5 May 2024"
    },
    {
      "Title": "AWS Academy Machine Learning Foundations",
      "Issuer": "Amazon Web Services",
      "Date": "16 Oct 2023",
      "ID": "[5635J]"
    },
    {
      "Title": "Networking Basics",
      "Issuer": "CISCO",
      "Date": "29 April 2023"
    }
  ]
}

##How to Use
Clone this repository:

git clone https://github.com/YOUR_USERNAME/resume-json.git
cd resume-json
View the JSON file:

Open resume.json in any text editor or JSON viewer to see the structured resume information.
Feel free to fork this repository and make any modifications as needed.
