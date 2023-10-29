
---

# Text Summarizer App

This is a simple Text Summarizer web application using SBert and Bert-Extractive-Summarizer. It allows you to enter text, summarize it, and view the summarized result.


## Requirements

- Python 3.7 or higher
- pip

## Setup

To set up and run the Text Summarizer App, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/text-summarizer-app.git
cd text-summarizer-app
```

### 2. Create a Virtual Environment (Optional but recommended)

It's a good practice to work within a virtual environment to isolate your project's dependencies. If you don't have `virtualenv` installed, you can install it using `pip`:

```bash
pip install virtualenv
```

Now, create a virtual environment:

```bash
virtualenv venv
```

Activate the virtual environment:

- **On Windows:**

  ```bash
  venv\Scripts\activate
  ```

- **On macOS and Linux:**

  ```bash
  source venv/bin/activate
  ```

### 3. Install Required Packages

Install the necessary Python packages using the provided `requirements.txt` file:

```bash
pip install -r requirements.txt
```

### 4. Run the Application

Now you can run the Text Summarizer App:

```bash
python app.py
```

The Flask web application will start, and you'll see a message like "Running on http://127.0.0.1:5000/." Open your web browser and navigate to this URL to use the app.  
## Input
![App in Action](/Sample/text.png)
## Output
![App in Action](/Sample/summary.png)

## How to Use

1. Enter the content you want to summarize in the text area.
2. Click the "Summarize" button.
3. The summarized result will be displayed in a new page.

## Troubleshooting

If you encounter any issues or have questions about the Text Summarizer App, please feel free to reach out to me or open an issue.

---

