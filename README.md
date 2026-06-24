
<div align="center">

<img src="https://drait.edu.in/assets/images/full_logo-wide.png" height="80" style="background:white; padding:8px; margin:0 16px;" />

# AI-Powered Automated Code Debugging and Fixing System

### Department of Master of Computer Applications
### Dr. Ambedkar Institute of Technology, Bengaluru

**Nikhitha H S** · MCA

</div>

---

## Abstract

Software debugging is one of the most challenging and time-consuming phases of software development. Developers spend a significant portion of their time identifying, analyzing, and fixing defects in source code. Recent advancements in Artificial Intelligence (AI) and Large Language Models (LLMs) have enabled intelligent systems capable of automating debugging tasks and assisting developers in generating effective code fixes. This project presents an AI-Powered Automated Code Debugging and Fixing System that combines static code analysis, error localization, and Large Language Models to automatically detect syntax, runtime, and logical errors in source code. The system provides detailed explanations of identified issues and generates context-aware fixes to improve software quality and developer productivity. The proposed platform demonstrates how AI can reduce debugging effort while improving software reliability and development efficiency.

---

## Keywords

Artificial Intelligence, Automated Debugging, Program Repair, Large Language Models, Software Engineering, Bug Detection, Code Analysis, Machine Learning.

---

# 1. Introduction

Software debugging plays a critical role in the software development lifecycle. As applications become increasingly complex, identifying and resolving defects becomes more difficult and time-consuming. Traditional debugging approaches require developers to manually inspect source code, analyze execution traces, and identify root causes of errors.

Recent developments in Artificial Intelligence have introduced new possibilities for automated debugging. AI-powered systems such as ChatGPT, GitHub Copilot, and RepairLLaMA have demonstrated the ability to understand programming logic, detect bugs, and suggest corrective actions. Research indicates that AI-assisted debugging tools significantly improve debugging speed and developer productivity while maintaining high accuracy levels in bug detection and repair.

This project proposes an AI-powered debugging platform that leverages modern Large Language Models and static code analysis techniques to automate software debugging. The system analyzes source code, identifies errors, explains issues, and generates optimized fixes that assist developers throughout the debugging process.

---

# 2. Literature Review

## 2.1 AI-Assisted Debugging: The Future of Automated Code Fixing

Khartode et al. (2025) investigated the role of AI systems such as ChatGPT, GitHub Copilot, RepairLLaMA, and GAMMA in automated debugging. Their findings revealed that AI-assisted debugging significantly improves bug detection accuracy and debugging speed while reducing developer effort. The study also highlighted limitations in handling complex semantic and multi-file bugs, indicating the need for human verification.

## 2.2 Designing for Novice Debuggers: A Pilot Study on an AI-Assisted Debugging Tool

Kurniawan et al. (2025) proposed CodeHinter, an intelligent debugging assistant designed for novice programmers. The system combines fault localization techniques with AI-generated hints and interactive guidance to improve debugging skills. Results showed that structured AI assistance enhances debugging effectiveness and reduces reliance on fully automated solutions.

## 2.3 Debugging with Open-Source Large Language Models: An Evaluation

Majdoub and Ben Charrada (2024) evaluated multiple open-source Large Language Models using DebugBench, a benchmark containing over 4,000 buggy code samples. Their research demonstrated that advanced open-source models such as DeepSeek-Coder achieved strong debugging performance and successfully repaired a large percentage of software defects.

---

# 3. Problem Statement

Debugging software applications is a resource-intensive and time-consuming task. Existing debugging tools often provide limited support for understanding root causes and generating automated fixes. Developers must manually analyze source code, identify bugs, and implement corrective actions, leading to increased development costs and reduced productivity.

There is a growing need for intelligent debugging systems capable of automatically detecting software defects, explaining errors, and generating accurate code fixes. Such systems can improve software quality, reduce debugging effort, and accelerate the software development lifecycle.

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

The proposed system follows the following workflow:

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

The results demonstrate that AI-powered debugging systems can significantly improve software development productivity while reducing debugging complexity.

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

The AI-Powered Automated Code Debugging and Fixing System demonstrates the potential of Artificial Intelligence in automating software debugging processes. By combining static code analysis with Large Language Models, the platform effectively identifies software defects, explains root causes, and generates accurate code fixes. The system improves debugging efficiency, enhances software quality, and reduces developer effort. As AI technologies continue to evolve, intelligent debugging assistants are expected to become an integral component of modern software development environments.

---

# References

1. Y. N. Khartode, B. G. Nevge, A. R. Dabre, S. K. Khamkhedkar, and A. S. Dahivelkar, *"AI-Assisted Debugging: The Future of Automated Code Fixing,"* International Journal of Advanced Research in Science, Communication and Technology, Vol. 5, Issue 3, December 2025.

2. O. Kurniawan, E. Chandra, C. M. Poskitt, Y. Noller, K. T. W. Choo, and C. Jegourel, *"Designing for Novice Debuggers: A Pilot Study on an AI-Assisted Debugging Tool,"* Proceedings of Koli Calling 2025, ACM, 2025.

3. Y. Majdoub and E. Ben Charrada, *"Debugging with Open-Source Large Language Models: An Evaluation,"* Proceedings of ESEM 2024, ACM, 2024.

---

## Installation

```bash
git clone https://github.com/your-username/your-repository.git

cd your-repository

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
