# Finfree-AI-Chatbot

## Project Overview

The Finfree AI Chatbot is a conversational agent developed for Finfree—a business that resells courses and skills for achieving financial freedom. The chatbot was built using Dialogflow Flow and Console to provide users with an interactive experience, answer queries, and guide them through course options and financial advice.

## Statement of Problem

In today's digital landscape, potential learners often struggle to quickly find the right educational resources among a vast array of options. Finfree faced challenges with:
- **Inefficient Information Retrieval:** Users had difficulty navigating the website to locate relevant courses and financial tips.
- **High Support Load:** Repetitive queries burdened customer support, affecting response times and user satisfaction.
- **Lack of Personalization:** The existing system did not tailor interactions to individual user needs, resulting in a less engaging experience.

The goal of the chatbot was to address these issues by providing a streamlined, automated, and conversational solution to improve user engagement and support.

## Objectives

- **Enhance User Engagement:** Provide an intuitive interface for users to quickly access course information and financial guidance.
- **Automate Customer Support:** Answer frequently asked questions and streamline the process of finding relevant content.
- **Lead Generation:** Assist in capturing potential leads by directing users to course sign-ups and additional resources.

## Technologies & Tools Used

- **Dialogflow Flow:** For designing the conversational flow using a visual interface.
- **Dialogflow Console:** For managing intents, entities, and deploying the chatbot.
- **Google Cloud Platform (GCP):** Underlying infrastructure to host and manage the chatbot.
- **Web Integration:** Embedded on the Finfree social media site to interact with visitors in real time.

## Architecture & Design

### Conversation Flow

1. **Welcome Intent:** Greets the user and provides options to learn about courses, ask financial questions, or get general guidance.
2. **Intent Handling:**
   - **Course Inquiries:** Answers questions about available courses, enrollment procedures, and pricing.
   - **Financial Advice:** Provides curated tips on achieving financial freedom.
   - **FAQs:** Handles common questions related to Finfree’s services and content.
3. **Fallback Intent:** Captures unrecognized queries and prompts the user to rephrase or contact support.

### Key Components

- **Intents:** Configured with training phrases that reflect the language of Finfree’s target audience.
- **Entities:** Defined to capture specific details such as course names and financial terms.
- **Context Management:** Used to maintain conversation state and ensure coherent multi-turn dialogue.
- **Webhook Integrations (Optional):** Connected to external APIs or databases for dynamic content retrieval, if needed.

## Implementation Details

1. **Designing the Flow:**
   - I Used Dialogflow Flow to visually map out conversation paths.

![image](https://github.com/user-attachments/assets/64e67701-0af1-42d6-9cc5-b53cd4a43c8c)

   - I Created multiple intents to cover a variety of user queries.

![image](https://github.com/user-attachments/assets/5f460ff4-bcd9-4a0d-aaa9-f72f74aa9773)


1. **Setting Up Intents & Entities:**
   - Developed training phrases based on common user queries.
   - Defined custom entities to capture specific terms (e.g., course names, financial jargon).
  
   

2. **Testing & Iteration:**
   - Conducted thorough testing within the Dialogflow Console.
   - Analyzed conversation logs to refine intents and responses.
  
![image](https://github.com/user-attachments/assets/17928240-8aee-447f-9dd4-e4f1343215c3)

![image](https://github.com/user-attachments/assets/ec5d7ae7-56c3-44ab-bf91-3156aedad6f2)


3. **Deployment:**
   - Integrated the chatbot into the Finfree social media site, precislely telegram app.
  
   ![image](https://github.com/user-attachments/assets/c32c7ab6-2fbf-4c94-8c54-7697ccd028a0)

   - Configured continuous monitoring and iterative improvements based on user feedback.

## Challenges & Learnings

- **Intent Recognition:** Fine-tuning training phrases was essential to improve the chatbot's understanding of varied user language.
- **Context Handling:** Managing conversation context helped in maintaining natural and coherent dialogues.
- **Scalability:** The project highlighted the importance of designing modular conversation flows that could be easily extended as Finfree’s offerings grow.

## Future Enhancements

- **Advanced NLP Integration:** Consider incorporating a Retrieval-Augmented Generation (RAG) approach to further enhance response accuracy using external curated data.
- **User Personalization:** Implement user profile tracking to tailor responses based on past interactions.
- **Multi-Channel Deployment:** Expand the chatbot to support other platforms like messaging apps and voice assistants.

## Conclusion

This project provided hands-on experience with Dialogflow's powerful conversational design tools and offered valuable insights into building customer-facing AI solutions. The Finfree AI Chatbot not only streamlined user interaction but also set the stage for future enhancements in AI-driven customer support.

## References

- [Dialogflow Documentation](https://cloud.google.com/dialogflow/docs)
- [Google Cloud Platform](https://cloud.google.com/)

