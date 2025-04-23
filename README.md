# 🚀 LLM-Powered Web Automation Framework
Welcome to the future of browser automation!
This framework combines the power of Large Language Models (LLMs) with Playwright and Python to create a natural language-driven automation tool for the web. Built for QA testers, developers, and automation enthusiasts, it lets you describe your actions in plain English—and the AI does the rest.

## ✨ Key Highlights

✅ No coding required – automate complex browser tasks using simple instructions


🧠 GenAI at the core – powered by free or paid LLMs (like OpenAI or Hugging Face)


🧪 QA-friendly – ideal for test case execution, UI flows, and repetitive validations


🔧 Playwright integration – gives full browser control and robust automation capabilities


🌐 CDP support – interact directly with live Chrome instances via DevTools Protocol


Whether you're a manual tester looking to automate without scripting, or a developer prototyping UI flows quickly, this framework is your AI sidekick for browser automation.

## Installation Guide

### Prerequisites
- Python 3.11 or higher
- Git (for cloning the repository)


## Installation Guide

### Prerequisites
- Python 3.11 or higher
- Git (for cloning the repository)

### Option 1: Local Installation

Read the [quickstart guide](https://docs.browser-use.com/quickstart#prepare-the-environment) or follow the steps below to get started.

#### Step 1: Clone the Repository
```bash
git clone https://github.com/Abdullahiqbal04/NextGen-Testers
cd NextGen-Testers
```

#### Step 2: Set Up Python Environment
We recommend using [uv](https://docs.astral.sh/uv/) for managing the Python environment.

Using uv (recommended):
```bash
uv venv --python 3.11
```

Activate the virtual environment:
- Windows (Command Prompt):
```cmd
.venv\Scripts\activate
```
- Windows (PowerShell):
```powershell
.\.venv\Scripts\Activate.ps1
```
- macOS/Linux:
```bash
source .venv/bin/activate
```

#### Step 3: Install Dependencies
Install Python packages:
```bash
uv pip install -r requirements.txt
```

Install Browsers in Playwright:
You can install specific browsers by running:
```bash
playwright install --with-deps chromium
```

To install all browsers:
```bash
playwright install
```

#### Step 4: Configure Environment
1. Create a copy of the example environment file:
- Windows (Command Prompt):
```bash
copy .env.example .env
```
- macOS/Linux/Windows (PowerShell):
```bash
cp .env.example .env
```
2. Open `.env` in your preferred text editor and add your API keys and other settings

## Usage

### Local Setup
1.  **Run the WebUI:**
    After completing the installation steps above, start the application:
    ```bash
    python webui.py --ip 127.0.0.1 --port 7788
    ```
