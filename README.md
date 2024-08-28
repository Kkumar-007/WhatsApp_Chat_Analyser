# WhatsApp Chat Analyzer

WhatsApp Chat Analyzer is a Python-based tool that helps you analyze your WhatsApp chat data. It provides insights such as the most active users, the frequency of messages, and the most common words used in your conversations.

## Features

- **User Activity Analysis:** Identify the most active participants in the chat.
- **Message Frequency:** Analyze the frequency of messages over time.
- **Word Cloud Generation:** Visualize the most common words used in the chat.
- **Media and Link Analysis:** Track the number of media files and links shared.

## Installation

To get started, clone the repository and install the required dependencies.

```bash
git clone https://github.com/Kkumar-007/WhatsApp_Chat_Analyser.git
cd WhatsApp_Chat_Analyser
pip install -r requirements.txt
```
## Usage

### Export WhatsApp Chat:

- Export the chat you want to analyze from WhatsApp without media (text file format).
- Save the `.txt` file in the project directory.

### Run the Analyzer:

- Open a terminal and navigate to the project directory.
- Execute the script using Python.

```bash
python whatsapp_chat_analyzer.py --file chat.txt
```

### View the Results

The analysis results, including charts and data summaries, will be displayed in the terminal or saved as files depending on the configuration.

### Example

Here is an example of how to use the WhatsApp Chat Analyzer:

```bash
python whatsapp_chat_analyzer.py --file sample_chat.txt
```

The script will output statistics about the chat, such as the total number of messages, most active users, and more.

### Requirements
1. Python 3.x
2. Required libraries are listed in requirements.txt. Install them using pip:
```bash
Copy code
pip install -r requirements.txt
```
