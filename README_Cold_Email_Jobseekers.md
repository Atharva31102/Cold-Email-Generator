# Cold Email Generator for Job Seekers

## Project Overview

This project is a **Cold Email Generator** designed to help fresh graduates and job seekers craft professional cold emails when applying for jobs. The tool allows users to input their details, such as **company name, job role, LinkedIn profile, portfolio, and key skills**, and generates a well-structured email.

## Features

- **User-friendly Streamlit interface** for easy email generation.
- **Automated cold email drafting** based on user input.
- **Personalized email structure** to increase response rates.
- **Integration with LangChain** for high-quality email generation.

## Setup & Installation

### 1. Install dependencies:

```sh
pip install streamlit langchain openai
```

### 2. Run the Streamlit app:

```sh
streamlit run cold_email_jobseekers.py
```

## How It Works

1. The user enters:
   - **Their Name**
   - **Company Name** (where they are applying)
   - **Job Role**
   - **LinkedIn Profile Link**
   - **Portfolio/GitHub Link**
   - **Key Skills**
2. The system generates a professional cold email.
3. The user can copy and use the email to apply for jobs.

## Example Output

```
Subject: Excited to Apply for [Job Role] at [Company]

Dear Hiring Manager,

I hope this email finds you well. My name is [Your Name], and I am eager to apply for the [Job Role] position at [Company]. As a recent graduate passionate about [mention key skills], I believe my skills align well with the role.

You can find my LinkedIn profile here: [LinkedIn Link] and my portfolio at [Portfolio Link].
I would love the opportunity to discuss how I can contribute to your team.

Looking forward to hearing from you.

Best regards,
[Your Name]
```

## Future Improvements

- **GPT-4 Integration** for more advanced email customization.
- **Email Sending Feature** directly from the app.
- **Multiple Template Options** based on the industry.


