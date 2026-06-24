
<div align="center">

<img src="https://drait.edu.in/assets/images/full_logo-wide.png" height="80" style="background:white; padding:8px; margin:0 16px;" />
<img src="https://www.erafoundationindia.org/images/logo.svg" height="80" style="background:white; padding:8px; margin:0 16px;" />
<img src="https://comedkares.org/wp-content/uploads/2023/04/Comedkares-Logo-EPS.png" height="80" style="background:white; padding:8px; margin:0 16px;" />

# Code Generation and Debugging Assistant

### Department of Master of Computer Applications
### Dr. Ambedkar Institute of Technology, Bengaluru

**Nikhitha H S**  
**MCA**  
**1DA24MC033**

</div>

---

## Abstract

Software debugging is one of the most challenging and time-consuming phases of software development. Developers spend a significant portion of their time identifying, analyzing, and fixing defects in source code. Recent advancements in Artificial Intelligence (AI) and Large Language Models (LLMs) have enabled intelligent systems capable of automating debugging tasks and assisting developers in generating effective code fixes. This project presents a Code Generation and Debugging Assistant that combines static code analysis, error localization, and Large Language Models to automatically detect syntax, runtime, and logical errors in source code. The system provides detailed explanations of identified issues and generates context-aware fixes to improve software quality and developer productivity. Previous studies have demonstrated that AI-assisted debugging tools can improve debugging efficiency, automate bug fixing, and support developers in identifying software defects more effectively [1][2][3].

---

## Keywords

Artificial Intelligence, Automated Debugging, Program Repair, Large Language Models, Software Engineering, Bug Detection, Code Analysis, Machine Learning.

---

# 1. Introduction

Software debugging plays a critical role in the software development lifecycle. As applications become increasingly complex, identifying and resolving defects becomes more difficult and time-consuming. Traditional debugging approaches require developers to manually inspect source code, analyze execution traces, and identify root causes of errors.

Recent developments in Artificial Intelligence have introduced new possibilities for automated debugging. AI-powered systems such as ChatGPT, GitHub Copilot, RepairLLaMA, and other Large Language Model-based solutions have demonstrated the ability to understand programming logic, detect bugs, and suggest corrective actions [1]. Research on AI-assisted debugging environments has shown improvements in debugging effectiveness, particularly for novice programmers through guided fault localization and intelligent hint generation [2]. Furthermore, evaluations of open-source Large Language Models have demonstrated their capability to repair a substantial percentage of software defects across multiple programming languages [3].

This project proposes an AI-powered debugging platform that leverages modern Large Language Models and static code analysis techniques to automate software debugging. The system analyzes source code, identifies errors, explains issues, and generates optimized fixes that assist developers throughout the debugging process.

---

# 2. Literature Review

## 2.1 AI-Assisted Debugging: The Future of Automated Code Fixing

Khartode et al. investigated the role of AI systems such as ChatGPT, GitHub Copilot, RepairLLaMA, and GAMMA in automated debugging. Their study concluded that AI-assisted debugging significantly improves bug detection accuracy, debugging speed, and developer productivity while reducing manual effort. The authors also emphasized that human validation remains necessary when handling complex semantic and logical errors [1].

## 2.2 Designing for Novice Debuggers: A Pilot Study on an AI-Assisted Debugging Tool

Kurniawan et al. proposed CodeHinter, an intelligent debugging assistant designed for novice programmers. The system integrates fault localization techniques, AI-generated hints, quizzes, and guided debugging workflows to help users identify and fix software defects. The study demonstrated that structured AI assistance improves debugging effectiveness and supports learning during the debugging process [2].

## 2.3 Debugging with Open-Source Large Language Models: An Evaluation

Majdoub and Ben Charrada evaluated multiple open-source Large Language Models using the DebugBench benchmark consisting of more than 4,000 buggy code instances. Their results showed that advanced open-source models such as DeepSeek-Coder achieved strong debugging performance and successfully repaired a large percentage of software defects across Python, Java, and C++ programs [3].

---

# 3. Problem Statement

Debugging software applications is a resource-intensive and time-consuming task. Existing debugging tools often provide limited support for understanding root causes and generating automated fixes. Developers must manually analyze source code, identify bugs, and implement corrective actions, leading to increased development costs and reduced productivity.

Research indicates that debugging often consumes a major portion of software development activities, creating a need for intelligent systems capable of automating bug detection and repair processes [1][3].

---

# 4. Objectives

- Develop an AI-powered automated debugging platform.
- Detect syntax, runtime, and logical errors automatically.
- Generate context-aware code repair suggestions.
- Provide detailed explanations for identified issues.
- Improve developer productivity and debugging efficiency.
- Support multiple programming languages.
- Enhance software quality through intelligent code analysis.

---

# 5. Methodology

The proposed methodology draws inspiration from modern AI-assisted debugging systems that combine fault localization, intelligent hint generation, and automated code repair mechanisms. Similar approaches have been shown to improve debugging effectiveness and provide meaningful support to programmers during software maintenance activities [2][3].

### Step 1: Source Code Submission

Users upload or paste source code into the system.

### Step 2: Static Code Analysis

The code is analyzed using static analysis techniques to identify structural and syntax-related issues.

### Step 3: Error Detection

The system identifies:

- Syntax Errors
- Runtime Errors
- Logical Errors
- Code Quality Issues

### Step 4: AI-Based Processing

Large Language Models analyze the detected issues and generate:

- Error explanations
- Root cause analysis
- Suggested code fixes

### Step 5: Automated Repair

The generated fixes are applied and validated against predefined conditions.

### Step 6: Output Generation

Corrected code and debugging recommendations are presented to the user.

---

# 6. System Architecture

```text
+---------------------+
|     User Input      |
+----------+----------+
           |
           v
+---------------------+
| Code Analysis Layer |
+----------+----------+
           |
           v
+---------------------+
| Error Detection     |
+----------+----------+
           |
           v
+---------------------+
| AI Processing Layer |
+----------+----------+
           |
           v
+---------------------+
| Fix Generation      |
+----------+----------+
           |
           v
+---------------------+
| Validation Module   |
+----------+----------+
           |
           v
+---------------------+
| Corrected Output    |
+---------------------+
```

---

# 7. Technologies Used

## Frontend

- React.js
- HTML5
- CSS3
- JavaScript

## Backend

- FastAPI
- Python

## Database

- Supabase PostgreSQL

## Authentication

- Firebase Authentication

## AI Integration

- Groq API
- Large Language Models (LLMs)

## Development Tools

- Git
- GitHub
- Visual Studio Code

---

# 8. Implementation

The frontend was developed using React.js to provide an interactive user interface for code submission and debugging visualization. FastAPI serves as the backend framework responsible for processing requests, communicating with AI services, and managing application logic.

Supabase PostgreSQL stores user information, debugging history, and project metadata, while Firebase Authentication manages user registration and login functionality.

The AI engine communicates with Large Language Models through the Groq API. The system analyzes uploaded code, detects bugs, generates explanations, and suggests optimized code repairs.

---

# 9. Results and Discussion

The developed platform successfully performs automated bug detection and repair across multiple categories of programming errors.

### Achievements

- Accurate syntax error detection.
- Automated bug localization.
- AI-generated code repair suggestions.
- Improved debugging efficiency.
- Reduced manual debugging effort.
- Enhanced code quality and maintainability.

The obtained results align with findings reported in recent research, where AI-assisted debugging systems demonstrated improvements in bug detection accuracy, debugging efficiency, and automated program repair performance [1][3].

---

# 10. Advantages

- Faster bug detection and correction.
- Reduced development effort.
- Improved software quality.
- Detailed error explanations.
- Scalable and modular architecture.
- User-friendly interface.

---

# 11. Limitations

- Complex business logic may require manual review.
- AI-generated fixes may occasionally be inaccurate.
- Performance depends on model quality.
- Internet connectivity is required for AI services.

---

# 12. Future Scope

Future enhancements include:

- Real-time IDE integration.
- Multi-file project debugging.
- Security vulnerability detection.
- Team collaboration features.
- Offline AI debugging capabilities.
- Custom fine-tuned models for enterprise environments.

---

# 13. Conclusion

The Code Generation and Debugging Assistant demonstrates the growing potential of Artificial Intelligence in software maintenance and debugging. By combining static code analysis with Large Language Models, the platform effectively identifies software defects, explains root causes, and generates accurate code fixes. Consistent with recent research findings, the integration of AI-assisted debugging techniques can significantly improve debugging efficiency, support developers during software development, and enhance overall code quality [1][2][3].

---

# References

[1] Y. N. Khartode, B. G. Nevge, A. R. Dabre, S. K. Khamkhedkar, and A. S. Dahivelkar, "AI-Assisted Debugging: The Future of Automated Code Fixing," International Journal of Advanced Research in Science, Communication and Technology, Vol. 5, Issue 3, Dec. 2025.

[2] O. Kurniawan, E. Chandra, C. M. Poskitt, Y. Noller, K. T. W. Choo, and C. Jegourel, "Designing for Novice Debuggers: A Pilot Study on an AI-Assisted Debugging Tool," Koli Calling '25, ACM, 2025.

[3] Y. Majdoub and E. Ben Charrada, "Debugging with Open-Source Large Language Models: An Evaluation," Proceedings of ESEM 2024, ACM, 2024.

---

## Installation

```bash
git clone https://github.com/your-username/code-generation-debugging-assistant.git

cd code-generation-debugging-assistant

npm install

npm run dev
```

---

## License

This project is developed for academic and research purposes.

---

## Acknowledgement

The authors express sincere gratitude to the Department of MCA, Dr. Ambedkar Institute of Technology, Bengaluru, for providing guidance, support, and resources throughout the development of this project.
````
