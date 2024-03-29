# Ticket Parser

This Python script parses the HTML content of a theater website to calculate the number of tickets available for the event.

## Prerequisites

- Python 3.x
- Install required libraries using `pip install requirements`

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/kjlq/Franko-Theater-Html-Parser.git
   cd repo
   ```

2. Run the script:

   ```bash
   python ticket_parser.py
   ```

## Description

The script fetches the HTML content from a specified URL, searches for elements with the "for-info" class, and extracts information related to the "Конотопська відьма" event. It then calculates the total number of tickets available for this event.

## Structure

- `ticket_parser.py`: Main Python script.

## Notes

- Modify the `afisha_url` variable with the desired URL.
- Adjust the script if the HTML structure of the website changes.

---