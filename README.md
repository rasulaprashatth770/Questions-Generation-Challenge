\# Advanced Question Generation System

This project implements an \*\*Advanced Question Generation System\*\*
to generate \*\*Multiple-Choice Questions (MCQs)\*\* and \*\*Open-Ended
Questions\*\* from text-based content in PDF files. The system leverages
\*\*Retrieval-Augmented Generation (RAG)\*\*, pre-trained language
models (e.g., \*\*T5\*\*), and vector search with \*\*FAISS\*\* to
ensure high-quality and context-aware question generation.

\-\--

\## Table of Contents

\- \[Overview\](#overview)

\- \[Setup Instructions\](#setup-instructions)

\- \[Prerequisites\](#prerequisites)

\- \[Installation\](#installation)

\- \[Setting up the Environment\](#setting-up-the-environment)

\- \[Usage Examples\](#usage-examples)

\- \[Generate Questions\](#generate-questions)

\- \[View the Results\](#view-the-results)

\- \[Dependencies List\](#dependencies-list)

\- \[License\](#license)

\-\--

\## Overview

The \*\*Advanced Question Generation System\*\* extracts key topics from
a given \*\*Project Management\*\* book (in PDF format) and generates
questions in two formats:

1\. \*\*MCQs\*\*: 15 questions per topic, with options and explanations.

2\. \*\*Open-Ended Questions\*\*: 5 questions per topic, with model
answers and key points.

Key features:

\- \*\*RAG Pipeline\*\*: Combines retrieval of relevant context using
\*\*FAISS\*\* with a pre-trained language model for question generation.

\- \*\*Fine-Tuned Model\*\*: Uses a fine-tuned model like \*\*T5\*\* or
\*\*LLaMA\*\* for better performance.

\- \*\*JSON Outputs\*\*: Saves the generated topics and questions in
structured JSON files.

\- \*\*Web Interface\*\*: Displays the results via a user-friendly
Flask-powered web page.

\-\--

\## Setup Instructions

\### Prerequisites

Before starting, ensure your system meets the following requirements:

\- \*\*Python 3.7 or higher\*\*

\- \*\*pip\*\* (Python package installer)

\- A compatible PDF file (e.g., a \*\*Project Management\*\* guide).
