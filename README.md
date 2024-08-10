Student Document Scrutiny System
Overview
The Student Document Scrutiny System is designed to streamline the process of reviewing and managing student documents. This system automates the document scrutiny process, making it more efficient and reducing manual effort. It provides a user-friendly interface for uploading, reviewing, and managing student documents.

Features
Document Upload: Allows users to upload various student documents.
Document Review: Provides tools for reviewing and annotating documents.
Document Management: Facilitates the organization and management of documents.
User Roles: Supports different user roles with varying levels of access and permissions.
Reporting: Generates reports based on document scrutiny and user activity.
Installation
Prerequisites
Ensure you have the following software installed:

Python 3.x
Required Python libraries (listed in requirements.txt)
Setup
Clone the Repository


git clone https://github.com/Rohan3177/student-document-scrutiny-system.git
Navigate to the Project Directory


cd student-document-scrutiny-system
Install Required Libraries

Create a virtual environment (optional but recommended) and install the dependencies:


python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
pip install -r requirements.txt
Configure the Application

Configure the application by editing the config.yaml file or environment variables as required.

Run the Application

Start the application by running:


python app.py
The application will start and can be accessed at http://localhost:5000 (default port).

Usage
Upload Documents

Navigate to the "Upload" section of the application and select the documents you wish to upload.

Review Documents

Go to the "Review" section to view and annotate documents. Use the available tools to make notes and comments.

Manage Documents

Use the "Manage" section to organize and manage your documents. You can sort, filter, and search documents based on various criteria.

Generate Reports

Access the "Reports" section to generate and download reports related to document scrutiny and user activity.

File Structure
app.py: Main application script.
requirements.txt: List of Python dependencies.
config.yaml: Configuration file for the application.
static/: Contains static files such as CSS, JavaScript, and images.
templates/: Contains HTML templates for the user interface.
docs/: Documentation files.
