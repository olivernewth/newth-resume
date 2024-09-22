# Oliver Grosvenor-Newth's Resume

## Overview

This repository contains a LaTeX template for my AI Product Manager resume. It's designed to showcase my experience in AI, machine learning, and large language models, with a focus on ethical AI development and product management in the tech industry.

## Purpose

I created this template to:
1. Maintain a consistent and professional format for my resume
2. Easily update and version control my career information
3. Share my resume-building process with friends and colleagues in the tech industry

## Key Features

- Single-page, one-column layout optimized for readability
- Sections include Summary, Experience, Education, Skills, and Awards & Recognition
- Emphasis on AI and machine learning experience, ethical AI practices, and product management achievements
- Customized to align with senior product management roles in AI-focused companies

## Quick Start

Sure, let's create a detailed quick start guide for your LaTeX resume template that includes instructions for setting up and using Visual Studio Code (VS Code).

---

# Oliver Grosvenor-Newth's Resume

## Overview

This repository contains a LaTeX template for my AI Product Manager resume. It's designed to showcase my experience in AI, machine learning, and large language models, with a focus on ethical AI development and product management in the tech industry.

## Purpose

I created this template to:
1. Maintain a consistent and professional format for my resume
2. Easily update and version control my career information
3. Share my resume-building process with friends and colleagues in the tech industry

## Key Features

-  Single-page, one-column layout optimized for readability
-  Sections include Summary, Experience, Education, Skills, and Awards & Recognition
-  Emphasis on AI and machine learning experience, ethical AI practices, and product management achievements
-  Customized to align with senior product management roles in AI-focused companies

## Quick Start

To use this template, follow these steps:

### 1. Clone the Repository

Clone the repository to your local machine using the following command:

```sh
git clone https://github.com/olivernewth/latex-resume.git
cd latex-resume
```

### 2. Install LaTeX

Ensure LaTeX is installed on your system. For macOS, you can use MacTeX:

```sh
brew install --cask mactex
```

For other operating systems, follow the respective installation instructions from the [LaTeX Project website](https://www.latex-project.org/get/).

### 3. Set Up Visual Studio Code

1. **Download and install [Visual Studio Code](https://code.visualstudio.com/)** if you haven't already.
2. **Install the LaTeX Workshop extension**:
   - Open VS Code.
   - Go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window or pressing `Ctrl+Shift+X`.
   - Search for "LaTeX Workshop" and click `Install`.

### 4. Compile the LaTeX Document

1. **Open the project directory in VS Code**:
   ```sh
   code .
   ```
2. **Open the `.tex` file** (e.g., `resume.tex`) in VS Code.
3. **Compile the document**:
   - Open the Command Palette by pressing `Cmd+Shift+P` (or `Ctrl+Shift+P` on Windows/Linux).
   - Type `LaTeX Workshop: Build LaTeX project` and select it.
   - The PDF will be generated and you can view it within VS Code or in your preferred PDF viewer.

### 5. Customize the Content

Edit the `.tex` file to include your own information. The sections are structured to make it easy to update your personal details, experience, education, skills, and awards.

### Example LaTeX Document Structure

Here is an example of how the LaTeX document might be structured:

```latex
\documentclass[a4paper,10pt]{article}
\usepackage[utf8]{inputenc}
\usepackage{geometry}
\geometry{a4paper, margin=1in}
\usepackage{enumitem}
\usepackage{titlesec}
\usepackage{hyperref}

% Custom commands
\newcommand{\resumeItem}[1]{\item #1}
\newcommand{\resumeSection}[1]{\section*{\uppercase{#1}}}

\titleformat{\section}{\large\bfseries}{}{0em}{}[\titlerule]

\begin{document}

\title{Oliver Grosvenor-Newth's Resume}
\author{}
\date{}

\maketitle

\resumeSection{Summary}
\begin{itemize}
    \resumeItem{Experienced AI Product Manager with a focus on ethical AI development and product management in the tech industry.}
\end{itemize}

\resumeSection{Experience}
\begin{itemize}
    \resumeItem{\textbf{AI Product Manager} - Tech Company (Year - Present)}
    \begin{itemize}
        \resumeItem{Led the development of AI-driven products, ensuring ethical AI practices.}
    \end{itemize}
\end{itemize}

\resumeSection{Education}
\begin{itemize}
    \resumeItem{\textbf{Degree} - University (Year)}
\end{itemize}

\resumeSection{Skills}
\begin{itemize}
    \resumeItem{AI, Machine Learning, Ethical AI, Product Management}
\end{itemize}

\resumeSection{Awards \& Recognition}
\begin{itemize}
    \resumeItem{Award Name - Description (Year)}
\end{itemize}

\end{document}
```



## Preview

![Resume Preview](/resume_preview.png)

## Customization

Feel free to fork this repository and customize the template for your own use. The structure is designed to be easily adaptable for various roles in AI and tech.

## License

The LaTeX template format is open for use, but please note that the content of the resume is my personal and professional information. If you use this template, ensure you replace all content with your own information.

## Acknowledgments

This template was inspired by and adapted from [Sourabh Bajaj's resume template](https://github.com/sb2nov/resume).

## Feedback and Contributions

I welcome feedback and suggestions for improving this template. Feel free to open an issue or submit a pull request if you have ideas for enhancements.