# langflow-STEM-EducationTutor-Agent

## **Project Overview**  
This project is a multi-agent tutoring system built to enhance STEM education by providing personalized learning experiences for students. Using LangFlow, the system integrates multiple AI agents to deliver content, guide problem-solving, assess understanding, and facilitate collaboration. The goal is to empower students with tailored support while improving their interest and comprehension in STEM topics.

---
## **Key Features**  
- **Content Retrieval**: Fetch relevant STEM materials, including tutorials, videos, and articles, from trusted sources.  
- **Interactive Problem-Solving**: Provide step-by-step guidance and hints for solving STEM problems.  
- **Assessment Generation**: Create quizzes and evaluate student responses for targeted feedback.  
- **Collaborative Learning**: Facilitate group discussions and projects to enhance peer learning.  
- **Performance Feedback**: Offer detailed feedback and recommendations for improvement.

---

## **System Components**  

### **Agents**
1. **Content Agent**  
   - **Task**: Retrieve educational content based on STEM topics and grade levels.  
   - **Tools**: Search API, Wikipedia API.  

2. **Problem-Solving Agent**  
   - **Task**: Provide step-by-step solutions and hints for STEM problems.  
   - **Tools**: OpenAI, Wolfram Alpha API.  

3. **Assessment Agent**  
   - **Task**: Generate quizzes and evaluate student understanding of STEM topics.  
   - **Tools**: OpenAI.  

4. **Feedback Agent**  
   - **Task**: Deliver personalized feedback and recommendations.  
   - **Tools**: OpenAI.  

---

## **Technologies and Tools Used**
- **LangFlow**: For orchestrating the multi-agent pipeline.  
- **APIs**:  
  - **Search API**: For retrieving online content.  
  - **Wikipedia API**: For accessing verified educational resources.  
  - **Wolfram Alpha API**: For solving mathematical and computational problems.  
- **AI Model**:  
  - **OpenAI (GPT)**: For natural language processing, content generation, and feedback creation.

---

## **Installation and Setup**  
1. **Clone the Repository**:  
   ```bash
   git clone <repository_url>
   cd <repository_directory>
   ```

2. **Install Dependencies**:  
   Ensure Python and LangFlow are installed. Use `pip` to install required libraries:  
   ```bash
   pip install -r requirements.txt
   ```

3. **Set Up API Keys**:  
   Add API keys for the following in a `.env` file:  
   - Search API  
   - Wikipedia API  
   - Wolfram Alpha API  
   - OpenAI API  

   Example `.env` file:  
   ```env
   SEARCH_API_KEY=<your_key>
   WIKIPEDIA_API_KEY=<your_key>
   WOLFRAM_API_KEY=<your_key>
   OPENAI_API_KEY=<your_key>
   ```

4. **Run the LangFlow Pipeline**:  
   Launch LangFlow and load the pipeline JSON file:  
   ```bash
   langflow
   ```

## **How It Works**  
1. Input the student's **topic**, **grade level**, or **specific question**.  
2. Agents collaborate to:  
   - Retrieve and structure relevant content.  
   - Guide the student through problem-solving.  
   - Generate quizzes and activities.  
   - Provide performance feedback.  
3. Outputs are delivered in structured format and visualized in an interactive UI.

## **Future Enhancements**
- Add support for additional APIs for more diverse content retrieval.  
- Implement real-time collaboration tools like Zoom or Google Meet integration.  
- Expand to include interactive simulations for complex STEM concepts.  

---

## **Contributors**
- **Ogechi Faith**  
  - Expertise: LLMs, multi-agent systems, Python, SQL, Power BI, and LangFlow development.  

For questions or contributions, feel free to reach out!

