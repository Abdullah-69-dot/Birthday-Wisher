# Birthday Wisher

A Python automation project that sends personalized birthday emails to your friends and family. The script reads data from a CSV file containing names, emails, and birthdays, and automatically sends a custom birthday wish via email on the correct date.

## Features

- Reads birthday data from a CSV file
- Sends personalized emails using SMTP
- Easy to configure and extend

## Technologies Used

- Python 3
- `smtplib` for sending emails
- `csv`, `datetime`

## Usage

1. Add birthday data to the provided CSV file.
2. Configure your email credentials in the script.
3. Run the script daily (manually or via a scheduler like cron).

## Setup

```bash
pip install -r requirements.txt
python main.py
```

---
