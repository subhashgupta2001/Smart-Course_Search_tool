# Smart Search for Analytics Vidhya Free Courses

This project demonstrates a Smart Search tool developed to help users find the most relevant free courses available on the Analytics Vidhya platform. The tool uses a Language Model to suggest courses based on user search queries and is deployed on Huggingface Spaces for public access.

## Project Overview

The goal of this project is to create a smart search feature that allows users to easily discover free courses on Analytics Vidhya. By leveraging an LLM (Large Language Model), the search tool provides intelligent and context-based recommendations based on user queries.

### Key Features
1. **Course Data Collection**: Collected course details such as titles, descriptions, and curriculum from Analytics Vidhya’s free course offerings.
2. **Smart Search System**: Built a search tool using a Language Model to understand user queries and suggest the most relevant courses.
3. **Deployment**: Hosted on Huggingface Spaces using [Gradio](https://gradio.app/) (or Streamlit) for an interactive and user-friendly interface.

## Steps for Development

### 1. Data Collection
- Scraped or manually gathered course titles, descriptions, and curriculum content for the free courses available on Analytics Vidhya.
- Stored the data in a structured format to make it accessible for processing and searching.

### 2. Building the Smart Search System
- **Model**: Leveraged a pre-trained Language Model to understand search intent and retrieve relevant course information.
- **Framework**: Used Gradio (or Streamlit) for the interface to build an intuitive and interactive search experience.
- **Implementation**: Developed an efficient search mechanism that ranks course results based on relevance to user queries.

### 3. Deployment on Huggingface Spaces
- Deployed the tool on Huggingface Spaces, making it publicly accessible.
- The deployment setup ensures a smooth user experience and is compatible with various devices.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/subhashgupta2001/smart-search-analyticsvidhya.git
   cd smart-search-analyticsvidhya
