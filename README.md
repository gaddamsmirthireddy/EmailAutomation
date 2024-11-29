# Email Automation System

This project automates sending bulk emails using Python. It allows scheduling email dispatches at a specific time and loads recipient information from a CSV file.

---

## Features  
- **Bulk Email Sending**: Automates sending emails to multiple recipients at once.  
- **Scheduling**: Schedule emails to be sent at a specific date and time.  
- **CSV-based Recipient List**: Load recipient information from a CSV file for ease of use.  
- **SMTP Server Integration**: Works with popular email services using SMTP for secure and reliable email dispatch.  
- **Personalized Email Content**: Customize email content with recipient-specific information.

---

## Tech Stack  
- **Python**: Programming language for backend logic and email sending.  
- **pandas**: Library for handling CSV recipient data.  
- **smtplib**: Python’s built-in library for SMTP server communication.

---

## Installation  

### Prerequisites  
- Python 3.x installed on your system.  
- A Gmail or other SMTP email account with appropriate credentials.  
- `pandas` library installed (`pip install pandas`).  

### Steps  

1. **Clone the Repository**  
   Clone this repository to your local machine using the following command:
   ```bash
   git clone https://github.com/your-username/email-automation.git
   cd email-automation
2. **Install Required Libraries**
   Install the necessary dependencies using pip:
   ```bash
   pip install -r requirements.txt
3. **Configure Email Credentials**
   Update the smtp_user and smtp_password variables in the send_emails.py file with your own SMTP credentials:
   ```bash
   smtp_user = 'your_email@gmail.com'
   smtp_password = 'your_password'
4. **Configure Recipient List**
   Modify the recipients.csv file to include the names and email addresses of your recipients.
   ```bash
   <br>
   name,email
   <br>
   John Doe,johndoe@example.com
   <br>
   Jane Smith,janesmith@example.com
   <br>
   Robert Brown,robertbrown@example.com
   <br>
   Emily Davis,emilydavis@example.com

6. **Run the Application**
   Run the email automation script to schedule and send your emails:
   ```bash
   python send_emails.py
7. **Access Email Scheduling**
   You can modify the scheduled time for sending emails by updating the send_time variable in the send_emails.py script. For example:
   ```bash
   send_time = datetime(2024, 12, 1, 10, 0)
### License

This project is licensed under the MIT License. Feel free to use, modify, and distribute it.





