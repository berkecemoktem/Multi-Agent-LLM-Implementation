# Multi-Agent Software Development Workflow

This project demonstrates a multi-agent system for a structured software development workflow. It utilizes **Google's Generative AI Gemini model** to create a Requirements Analyst, Software Developer, and Tester agents, each handling a distinct role in the process.

## Features

1. **Requirements Gathering**:  
   - The `RequirementsAnalyst` agent engages with the user to gather software requirements.  
   - Generates a comprehensive **Software Requirements Specification (SRS)** document.

2. **Code Generation**:  
   - The `Coder` agent generates Python code based on the provided SRS.  
   - Incorporates clean, well-documented, and PEP 8-compliant code.  
   - Revises the code based on tester feedback.

3. **Code Testing**:  
   - The `Tester` agent validates the generated code against the original SRS.  
   - Provides detailed feedback on bugs, missing requirements, or edge cases.  
   - Marks the code as **passed** or requires further revision.

4. **Iterative Development**:  
   - The system iterates through development cycles (up to 3 revisions) until the code passes all tests.

## How It Works

1. **Start the process**:  
   Run the script to initiate the software development cycle.  
   ```bash
   python main.py
2. **Gather Requirements**:
Interact with the RequirementsAnalyst agent to define the main purpose, features, performance expectations, and constraints for the software.

3. **Generate Code**:
The Coder agent produces Python code to implement the specified requirements.

4. **Test the Code**:
The Tester agent reviews the code and provides feedback, ensuring alignment with the SRS and addressing potential issues.

5. **Iterate**:
The process repeats until the Tester approves the code or the maximum number of iterations is reached.

![image](https://github.com/user-attachments/assets/bc361dba-40e9-41f6-9cda-96bf6c14016b)


## Dependencies

- **Python 3.9+**  
- **Google Generative AI Python SDK** (`google-generativeai`)

#### Contributors

- **Egemen Doruk Serdar**
- **Mustafa Bogac Morkoyun**
- **Irem Besıroglu**



