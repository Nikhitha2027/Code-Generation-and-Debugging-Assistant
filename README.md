# Code Generation and Debugging Assistant Using DeepLearning and Large Language Models

## Abstract

Debugging is one of the most difficult and time-consuming tasks in software development. Traditional debugging methods require a lot of manual effort and are not effective in handling logical and semantic errors in large software systems. Recent developments in Artificial Intelligence (AI) and Large Language Models (LLMs) have introduced intelligent debugging systems that can automatically repair code, detect faults, and provide interactive debugging support. However, existing AI-assisted debugging systems still have limitations such as incorrect AI-generated fixes, weak semantic understanding, lack of explainability, and poor multi-file debugging support.

This research paper presents a comparative study of three recent papers related to AI-assisted debugging systems:

* Debugging with Open-Source Large Language Models: An Evaluation
* Designing for Novice Debuggers: A Pilot Study on an AI-Assisted Debugging Tool
* AI-Assisted Debugging: The Future of Automated Code Fixing

The methodologies, strengths, and limitations of these systems are analyzed in detail. Based on the identified research gaps, this paper proposes an improved AI-powered system called **Code Generation and Debugging Assistant**, which combines Large Language Models, fault localization, semantic analysis, explainable AI, and interactive debugging support to improve debugging accuracy and developer learning experience.

**Keywords:** AI-Assisted Debugging, Large Language Models, Automated Program Repair, Explainable AI, Fault Localization, Semantic Error Detection, Interactive Debugging



# Problem Statement

Traditional debugging methods require significant manual effort and are often ineffective in detecting semantic, logical, and multi-file errors. Although AI-assisted debugging systems using Large Language Models (LLMs) can generate automated fixes, they still suffer from limitations such as hallucinated solutions, weak semantic understanding, lack of explainability, and poor debugging guidance for beginners.

Therefore, there is a need for an intelligent AI-powered debugging system that combines fault localization, semantic analysis, explainable AI, and automated patch validation to improve debugging accuracy, reliability, and learning support.



# I. Introduction

Debugging is an important part of software development and maintenance. Developers often spend a lot of time finding and fixing bugs in programs. Traditional debugging methods such as print debugging, breakpoint analysis, and manual testing become difficult and less effective when software systems become large and complex.

The growth of Artificial Intelligence (AI) and Large Language Models (LLMs) such as GPT-4, DeepSeek-Coder, CodeLlama, and WizardCoder has improved software development tasks like code generation, automated debugging, code explanation, and bug fixing. AI-assisted debugging systems can now detect errors, suggest fixes, explain bugs, and provide real-time debugging support.

Although AI-assisted debugging systems give good results, they still face problems such as incorrect AI-generated fixes, weak understanding of program logic, lack of proper explanations, and poor support for multi-file debugging. These limitations reduce trust in AI debugging systems and make learning difficult for beginner programmers.

This paper presents a comparative study of three research papers related to AI-assisted debugging and identifies the missing features and limitations in existing systems.



# II. Literature Review

Earlier debugging methods mainly depended on manual techniques such as print debugging, breakpoint analysis, and traditional testing to find software errors. These methods required a lot of developer effort and became difficult to manage for large and complex software systems.

With the development of Artificial Intelligence (AI) and Machine Learning (ML), automated debugging systems were introduced to help developers detect and fix bugs more easily. Early AI-based debugging systems used rule-based methods, static analysis, and fault localization techniques to identify possible error locations in code. Although these systems improved debugging speed, they often failed to properly understand program logic and contextual errors.

Recent advancements in Large Language Models (LLMs) such as GPT-4, DeepSeek-Coder, CodeLlama, and WizardCoder have changed debugging methods by supporting automated code generation, bug fixing, code explanation, and conversational debugging. Transformer-based models improved the understanding of source code and allowed AI systems to generate more human-like debugging suggestions.

Recent research studies show that AI-assisted debugging systems can improve debugging speed and developer productivity. However, existing systems still face problems such as incorrect AI-generated fixes, lack of proper explanations, weak semantic understanding, and poor multi-file debugging support.



# III. Proposed System

The system proposed in this research work, **Code Generation and Debugging Assistant (CGDA)**, is the result of a combination of different ideas and outcomes obtained from three existing research papers. The system incorporates the AI support provided by some of the current AI models, specifically those based on Large Language Models (LLMs), like GPT-4, DeepSeek-Coder and CodeLlama, to assist users in auto-generating code and to detect and fix bugs in code written in different programming languages.

The system automatically supports debug, identifies faults, gives suggestions and details on why a particular error occurred. It also gives users who are beginners at programming interactive guidance and support for smarter, more effective debugging using semantic analysis and automated testing.

Unlike existing approaches, our proposed system tackles a distinct set of challenges including:

1. Decreasing the rate of incorrect fixes generated by AI
2. Debugging spanning multiple files
3. Providing greater explainability for the user during the debugging process

The goal of our system is to decrease the time and effort required to debug, increase accuracy, and make the process easier for developers and users alike.



# IV. Methodology

## A. Code Input

The user writes, uploads, or pastes source code into the system for debugging and analysis.

## B. Code Analysis

The system analyzes the code to identify syntax errors, logical mistakes, runtime errors, and semantic issues.

## C. Fault Detection

Fault localization techniques are used to identify suspicious lines and possible error locations in the program.

## D. AI-Based Debugging

Large Language Models such as GPT-4, DeepSeek-Coder, and CodeLlama analyze the code and generate possible fixes and debugging suggestions.

## E. Patch Validation

The generated fixes are validated using automated testing and static analysis to check whether the solution works correctly.

## F. Interactive Guidance

The system provides debugging explanations, hints, and step-by-step guidance to help users understand the errors and solutions.



# V. New Features of the Proposed System

The proposed system includes several improved features that are not fully available in the existing research papers.

1. **Multi-file Debugging**
   The system can analyze multiple files together and detect errors between connected files.

2. **Explainable Debugging**
   The system explains why the error occurred and how the suggested fix works.

3. **Reduced Incorrect Fixes**
   Generated fixes are checked using testing and analysis to reduce wrong AI suggestions.

4. **Confidence Score**
   Each generated fix includes a confidence score showing how reliable the solution is.

5. **AI + Fault Localization**
   The system combines AI models with fault localization techniques for better debugging accuracy.

6. **Personalized Guidance**
   The system provides debugging hints and support based on the user’s skill level.

7. **Step-by-Step Debugging Help**
   Instead of directly giving answers, the system guides users through the debugging process.

8. **Automatic Test Case Generation**
   The system automatically creates test cases to validate generated fixes.

9. **Debugging Dashboard**
   Users can track debugging progress, common mistakes, and improvement over time.

10. **Secure Offline Support**
    Open-source AI models can run locally to improve privacy and protect source code.



# VI. System Architecture

The proposed Code Generation and Debugging Assistant follows a layered architecture consisting of:

1. User Interface Layer
2. Code Analysis Module
3. Fault Localization Module
4. AI Debugging Engine
5. Explainable AI Module
6. Patch Validation Module
7. Database and Analytics Module

The architecture allows the system to analyze code, detect bugs, generate fixes, validate solutions, and provide interactive debugging support efficiently.



# VII. Limitations

* AI-generated fixes may sometimes be incorrect
* Advanced logical errors can still be difficult to detect
* Large Language Models require high computational resources
* Multi-file debugging can increase system complexity
* Continuous model updates and training are required
* Automated testing may not cover all possible scenarios
* Performance depends on the quality of input code and test cases



# VIII. Future Scope

Future improvements of the proposed system may include:

* Real-time collaborative debugging
* Voice-based debugging support
* AI chatbot for coding assistance
* Cross-language debugging support
* Automatic code optimization suggestions
* Cloud-based debugging platform
* Mobile application support
* Advanced semantic error detection
* AI-based learning recommendations
* Fully autonomous debugging systems



# IX. Conclusion

This paper presented a comparative study of three AI-assisted debugging research papers and analyzed their approaches, strengths, and limitations. The study identified major challenges in existing systems such as incorrect AI-generated fixes, lack of explainability, weak semantic understanding, and poor multi-file debugging support.

To overcome these limitations, the proposed Code Generation and Debugging Assistant combines Large Language Models, fault localization, semantic analysis, automated testing, and interactive debugging support. The system aims to improve debugging accuracy, reduce developer effort, and provide a better learning experience for programmers.

The proposed framework offers a smarter, faster, and more user-friendly approach to automated debugging and has the potential to improve future software development and learning environments.



# Comparative Analysis of Existing Systems
| Feature               | Debugging with Open-Source LLMs        | Designing for Novice Debuggers | AI-Assisted Debugging       |
| --------------------- | -------------------------------------- | ------------------------------ | --------------------------- |
| Main Focus            | Open-source LLM evaluation             | Beginner-friendly debugging    | Automated code fixing       |
| AI Model Support      | DeepSeek-Coder, CodeLlama, WizardCoder | GPT-4o                         | Large Language Models       |
| Interactive Debugging | No                                     | Yes                            | Partial                     |
| Explainable Debugging | No                                     | Yes                            | Limited                     |
| Beginner Support      | No                                     | Yes                            | No                          |
| Fault Localization    | No                                     | Yes                            | Partial                     |
| Semantic Analysis     | Limited                                | Moderate                       | Moderate                    |
| Multi-file Debugging  | No                                     | No                             | No                          |
| Patch Validation      | Yes                                    | No                             | Partial                     |
| IDE Support           | No                                     | VS Code                        | Partial                     |
| Real-time Debugging   | No                                     | Partial                        | Yes                         |
| Main Limitation       | No explainability                      | Limited language support       | No practical implementation |



# References

1. Y. Majdoub and E. Ben Charrada, “Debugging with Open-Source Large Language Models: An Evaluation,” ESEM 2024.

2. O. Kurniawan et al., “Designing for Novice Debuggers: A Pilot Study on an AI-Assisted Debugging Tool,” Koli Calling 2025.

3. Y. N. Khartode et al., “AI-Assisted Debugging: The Future of Automated Code Fixing,” IJARSCT 2025.
