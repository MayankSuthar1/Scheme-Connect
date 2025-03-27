# SchemeConnect - AI-Powered Healthcare Scheme Accessibility Platform

## Team: INSIDER

### Domain: Healthcare

## Problem Statement
Many citizens, particularly in rural and underserved communities, lack awareness and access to government healthcare schemes.
Challenges include:
- Limited awareness of available healthcare schemes.
- Complex eligibility criteria that make it difficult for individuals to determine which schemes they qualify for.
- Lengthy and bureaucratic application processes.
- Lack of interoperability across various Digital Public Infrastructures (DPIs), making access and verification cumbersome.

## Solution Overview
SchemeConnect is an AI-powered platform designed to enhance access to healthcare schemes by:
- **Automated Eligibility Mapping**: AI assesses user eligibility based on demographics, income, health conditions, and other factors.
- **Increased Awareness**: Personalized recommendations for Central & State government healthcare schemes.
- **Simplified Application Process**: AI-powered automation assists users in completing and submitting applications.
- **Interoperability with DPIs**: Seamless document verification and access by integrating with public infrastructure.

## Primary Users
- **Citizens in Rural Areas**: Those lacking awareness and access to healthcare schemes.
- **Healthcare Workers**: Assist citizens without mobile devices or internet connectivity in registering for schemes and providing information.

## Scalability
- **Cloud-Based & Mobile-Friendly**: Accessible via smartphones and web browsers.
- **Modular Design**: Expandable to include other social welfare schemes such as food security and education.
- **API Integration**: Connects with state and central government databases for real-time updates.

## Key Features
- AI-powered scheme matching and recommendations.
- Multilingual chatbot for conversational assistance.
- Secure authentication with OAuth2 and JWT.
- Cloud-hosted scalable architecture with offline functionality.
- Voice-enabled interactions using Web Speech API.
- Analytics and tracking for user engagement.

## Open-Source AI Technologies Used
- **BERT / GPT Models** – NLP for multi-language support.
- **ML-Based Recommendation Engine** – Personalized scheme suggestions.
- **OCR & Document Verification** – Extracts and verifies documents.
- **Chatbot (Rasa/Google Dialogflow)** – AI-driven assistance.
- **Frontend** – Next.js with PWA for enhanced performance.
- **Backend** – Python with FastAPI for high-performance APIs.
- **AI Agents** – LangChain framework for orchestrating AI workflows.
- **LLM Integration** – Gemini 2.0 for natural language understanding.
- **Database** – PostgreSQL with JSON support for scheme details.
- **Vector Database** – FAISS for efficient scheme information retrieval.
- **Containerization** – Docker for consistent deployment.
- **Cloud Hosting** – Azure App Service for scalable web hosting.
- **Offline Support** – Next.js PWA plugin with service workers.
- **Analytics** – Mixpanel for tracking user interactions.

## Why These Technologies?
- Cost-effective, scalable, and secure.
- NLP models enable smart eligibility matching.
- Rasa powers a multilingual chatbot.
- Tesseract OCR ensures accurate document verification.
- FastAPI enables seamless government database integration.
- Cloud-based deployment ensures accessibility in remote areas.

## Solution Architecture
1. **User Interaction Layer** - Next.js PWA frontend with offline functionality.
2. **Communication Layer** - FastAPI gateway for handling requests.
3. **Core Services Layer** - Manages authentication, profiles, and notifications.
4. **AI Layer** - LangChain orchestrating AI-driven decision-making.
5. **Model Integration Layer** - Gemini 2.0 for NLP.
6. **Data Storage Layer** - PostgreSQL, FAISS, and document storage.
7. **External Integration Layer** - Government APIs and health records.
8. **Infrastructure Layer** - Scalable cloud hosting and deployment.

## Datasets
- Publicly available government healthcare scheme databases.
- User-generated application data.
- Synthetic datasets for AI model training while preserving privacy.

## Summary
SchemeConnect is a PWA that uses AI to match users with healthcare schemes based on their profile. It provides personalized recommendations, document verification, and a multilingual chatbot to guide users through the process. Designed for scalability, it ensures accessibility for rural communities and healthcare workers while maintaining data security and interoperability with government databases.

