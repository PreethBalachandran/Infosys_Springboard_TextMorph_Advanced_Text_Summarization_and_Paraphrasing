
# Milestone 4

## Project Overview

This project is an AI-powered text processing platform that integrates advanced Natural Language Processing (NLP) models with a secure authentication system and interactive dashboards. The application allows users to perform tasks such as text summarization, paraphrasing, readability analysis, and AI chat interactions through a modern web interface.

Milestone 4 extends the previous implementation by introducing an advanced **Admin Dashboard, enhanced user personalization features, analytics visualizations, and feedback analysis tools**.

The platform is designed to provide a secure, scalable, and user-friendly environment for AI-based text processing.

---

# Key Features Implemented

## 1. Secure Authentication System

The platform includes a robust authentication system designed to protect user accounts and ensure secure access.

Features include:

* User registration and login
* Password hashing using **bcrypt**
* JSON Web Token (JWT) based authentication
* Email OTP verification for password reset
* Security question verification
* Login rate limiting to prevent brute-force attacks
* Password history protection

---

# Admin Dashboard (Management & Analytics)

The Admin Dashboard acts as a **central command center** that allows administrators to monitor system activity, manage users, and analyze application usage.

### User Management

Administrators can manage user accounts through the dashboard.

Capabilities include:

* Promote users to **Admin role**
* Lock or unlock user accounts
* Delete user accounts
* View registered users and account creation details

---

### Activity Monitoring

The admin panel provides insights into system activity.

Features include:

* Real-time active user tracking
* Monitoring overall system activity
* Viewing historical logs of user actions

---

### Data Visualization

Interactive analytics are displayed to help understand system usage.

Charts are generated to visualize:

* AI models being used most frequently
* Languages selected by users
* Most commonly used platform features

Visualization tools used include interactive charts created using **Plotly**.

---

### Feedback Analysis

User feedback collected through the platform is analyzed visually.

Features include:

* Feedback trend analysis
* WordCloud visualization to identify common feedback keywords
* Insights into user satisfaction and improvement areas

---

### Data Export

Administrators can download system data for analysis or record-keeping.

Export options include:

* User information
* Activity history logs
* User feedback datasets

Data can be exported for reporting and analysis purposes.

---

# User Dashboard & Profile Personalization

The user dashboard provides a personalized experience while interacting with the AI tools.

### Profile Management

Users can manage their personal profile information.

Features include:

* Update email address
* Change account password
* Upload or update profile avatar (display picture)

---

### Personalized Experience

The user interface allows customization and personalization features to enhance the user experience.

Enhancements include:

* Improved dashboard navigation
* Personalized profile display
* Clean and modern interface design
* Responsive layout for better usability

---

# AI Modules Integrated

The platform integrates several NLP capabilities.

### Text Summarization

Generates concise summaries from long text inputs using transformer models.

Models used:

* BART
* PEGASUS
* FLAN-T5


---

### Paraphrasing Engine

Rewrites sentences while maintaining the original meaning.

Model used:

* T5 Transformer

---

### Readability Analyzer

Analyzes the complexity of text and provides readability scores.

Metrics calculated include:

* Flesch Reading Ease
* Flesch-Kincaid Grade Level
* SMOG Index
* Gunning Fog Index
* Coleman-Liau Index

---

# Dataset Augmentation & Model Fine-Tuning

To improve model performance, dataset augmentation techniques were applied.

Methods used:

* Synonym replacement
* Random word deletion
* Sentence shuffling
* Paraphrase-based augmentation

Models were further optimized using **fine-tuning techniques and quantization (4-bit / 8-bit optimization)** to improve efficiency and reduce memory usage.

---

# Technologies Used

Backend:

* Python
* PostgreSQL
* JWT Authentication
* bcrypt Security

AI / NLP:

* Transformers
* PyTorch
* NLTK

Frontend:

* Streamlit
* Plotly
* Custom CSS

Additional Libraries:

* PyPDF2
* WordCloud
* pandas
* numpy

---

# Project Structure

```
Milestone4
│
├── Milestone4_finaldemo.ipynb
├── requirements.txt
├── README.md

```

---

## Install Dependencies

```
pip install -r requirements.txt
```

---

## Configure Environment Variables

Create a `.env` file with the following configuration:

```
EMAIL_ADDRESS=your_email
EMAIL_PASSWORD=your_email_password
JWT_SECRET=your_secret_key

DB_NAME=database_name
DB_USER=postgres
DB_PASSWORD=postgres
DB_HOST=localhost
DB_PORT=5432
```

---

## Run the Application

```
streamlit run app.py
```

The application will open in your browser.

---

# Screenshots


---

# Conclusion

This project demonstrates the integration of **secure authentication, AI-based text processing, user analytics, and interactive dashboards** into a unified application.

The platform provides powerful AI tools alongside an intuitive user experience, while the admin dashboard enables effective system monitoring and management.
