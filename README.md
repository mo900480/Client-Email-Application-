# # Email Client Application

A Python-based email client that sends and receives emails using SMTP and IMAP protocols, with a local TCP notification server and a modern dark-themed GUI.

## Project Info

- **Course:** Computer Networks (00207N)
- **University:** Alexandria National University
- **Faculty:** Computers and Data Science
- **Semester:** Fall 2026

## Team Members

- Altaher Ahmed
- Amr Hesham
- Ahmed Badr
- Mohammed Saeed

## Features

- Send emails via SMTP (ports 465/587 with TLS/SSL)
- Receive latest email via IMAP (port 993 with SSL)
- Local TCP notification server on port 9999
- Modern dark GUI built with tkinter
- Desktop push notifications using Plyer
- Wireshark-compatible traffic capture

## Project Structure

| File | Description |
|------|-------------|
| `email_client.py` | Core client: SMTP send, IMAP receive, TCP notify |
| `notification_server.py` | Local TCP server that prints status messages |
| `gui.py` | Dark-themed tkinter interface with console output |

## Requirements

- Python 3.7+
- plyer

## Installation

```bash
pip install plyer

## Usage 
python notification_server.py
Server listening on 127.0.0.1:9999
[127.0.0.1:54321] Email Sent Successfully
 
## Star a GUI 
python gui.py

Now you can send emails .
