# Gen-Z ATS

Gen-Z ATS is an AI-powered Applicant Tracking System (ATS) that leverages large language models (LLMs) to analyze resumes against job descriptions. It provides a **percentage match score** and identifies missing projects or skills, helping both job seekers and recruiters optimize resumes for better job alignment.

## Features
- **Resume Analysis:** Compares resume content with the job description.
- **Profile Match Score:** Displays a percentage indicating how well the resume aligns with the job profile.
- **Missing Projects Identification:** Highlights projects or skills missing in the resume.
- **Streamlit Web Interface:** Simple and interactive UI for resume evaluation.

## Technologies Used
- **Google Generative AI** – For advanced text analysis and matching.
- **Streamlit** – To create the web-based interface.
- **python-dotenv** – For managing environment variables securely.
- **pdf2image & Pillow** – For processing PDF resumes.
- **poppler-utils** – To convert PDFs to images for enhanced analysis.

## Installation
### Prerequisites
Ensure you have Python (>=3.8) installed on your system.

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/Gen-Z-ATS.git
   cd Gen-Z-ATS
