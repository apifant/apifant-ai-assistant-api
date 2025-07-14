# Apifant AI Assistant Hub API

## 🎯 Overview

The **Apifant AI Assistant Hub API** provides a comprehensive platform for creating, managing, and deploying intelligent voice assistants with advanced conversational capabilities. Build sophisticated AI-powered phone systems, chatbots, and interactive voice responses with multi-language support and real-time conversation management.

### Key Features

- **🤖 AI Assistant Management**: Create and configure intelligent assistants with custom instructions and behaviors
- **📚 Knowledge Base Integration**: Upload documents, extract web content, and manage assistant knowledge
- **🗣️ Multi-Voice Support**: Integrate with Azure, ElevenLabs, and Apifant voice providers
- **📞 Phone System Integration**: Assign assistants to phone numbers with full call management
- **💬 Real-time Chat**: Interactive chat sessions with conversation history
- **🎭 Character System**: Create personalities with detailed traits and behaviors
- **🌍 Multi-Language Support**: 12+ languages including English, German, Spanish, French, and more
- **📊 Live Monitoring**: Real-time call transcription and conversation tracking
- **🔗 Webhook Integration**: Custom webhook endpoints for data processing
- **🔑 API Key Management**: Centralized management for multiple AI and voice provider keys

## 🔄 Authentication

All API requests require a Bearer token in the Authorization header:

```
Authorization: Bearer YOUR_API_TOKEN
```

## 🌍 Supported Languages

| Language | Code | Language | Code |
|----------|------|----------|------|
| English | `en` | Portuguese | `pt` |
| Spanish | `es` | Dutch | `nl` |
| French | `fr` | Russian | `ru` |
| German | `de` | Chinese | `zh` |
| Italian | `it` | Japanese | `ja` |
| Korean | `ko` | Arabic | `ar` |

## 🎙️ Voice Providers

### Supported Providers

- **Azure**: Microsoft Azure Cognitive Services with global voice options
- **ElevenLabs**: Advanced AI voice synthesis with natural-sounding voices
- **Apifant**: Native voice processing optimized for telephony

### Voice Configuration

Each assistant can be configured with a specific voice provider and voice ID for consistent audio output across all interactions. Voice settings include provider type, voice ID, and display name for easy management.

## 🤖 AI Models

### Available Models

- **OpenAI**: GPT-3.5 Turbo, GPT-4, GPT-4 Turbo, GPT-4o Mini
- **Azure OpenAI**: GPT-35 Turbo, GPT-35 Turbo 16K, GPT-4o Mini
- **Google**: Gemini 1.5 Flash, Gemini 2.0 Flash
- **Ollama**: Llama3, DeepSeek R1 8B, Qwen2.5 7B

### Model Selection Guidelines

Choose the appropriate model based on:

- **Response Speed**: Faster models for real-time conversations
- **Conversation Complexity**: More powerful models for nuanced interactions
- **Cost Considerations**: Balance performance with usage costs
- **Language Support**: Ensure model supports your target languages

## 🤖 Assistant Types & Configuration

### Core Assistant Components

**Instructions**: Define the assistant's primary behavior and response patterns. Be specific about tone, knowledge scope, and interaction style.

**End Instructions**: Specify clear criteria for when conversations should conclude, such as issue resolution or customer satisfaction.

**Greeting Messages**: Create welcoming first impressions that set expectations for the interaction.

**Additional Instructions**: Layer on specialized behaviors or temporary modifications for specific use cases.

### Configuration Options

**Parallel Mode**: Enable cluster execution for high-traffic scenarios requiring faster response times.

**Bark-in Detection**: Allow users to interrupt the assistant's speech, creating more natural conversation flow.

**DTMF Integration**: Support dual-tone multi-frequency signals for phone menu navigation.

## 📚 Knowledge Base System

### Content Sources

**Manual Entry**: Direct text input for policies, procedures, and frequently asked questions.

**File Upload**: Support for various document formats with automatic text extraction.

**URL Extraction**: Web scraping capabilities to pull content from websites and online resources.

### Knowledge Management

Each knowledge entry includes source tracking, extraction status monitoring, and content organization features. The system maintains version history and allows for content updates and removals.

## 🎭 Character System

### Personality Framework

Create rich, consistent personalities with detailed trait definitions:

**Behavioral Patterns**: How the character responds to different situations and user inputs.

**Communication Style**: Formal vs. casual, technical vs. conversational, empathetic vs. direct.

**Emotional Traits**: Enthusiasm levels, patience, humor, and emotional intelligence.

**Background Story**: Context that influences character responses and knowledge.

**Speaking Patterns**: Vocabulary choices, sentence structure, and verbal habits.

### Visibility Settings

- **Private**: Available only to the creator
- **Public**: Accessible to all users
- **Organization**: Shared within your organization

## 📞 Phone Integration

### Phone Number Management

Configure SIP credentials for each phone number, including username, password, and connection settings. Phone numbers can operate in different modes:

**Production Mode**: Live customer interactions with full functionality.

**Test Mode**: Development and testing environment with limited features.

**Echo Mode**: Simple echo responses for connection testing.

### Call Handling

**Inbound Calls**: Automatic assistant assignment based on phone number configuration.

**Outbound Calls**: Programmatic call initiation with custom assistant instructions.

**Call Monitoring**: Real-time transcription and conversation tracking during active calls.

## 💬 Chat System

### Session Management

Create persistent chat sessions with conversation history, message threading, and context retention across interactions.

### Multi-Channel Support

- **Inbound**: Customer-initiated conversations
- **Outbound**: Proactive engagement and follow-ups

### Model Override

Specify different AI models per chat session for specialized requirements or testing scenarios.

## 📊 Live Monitoring

### Real-time Capabilities

**Active Call Tracking**: Monitor all ongoing conversations with live participant lists.

**Transcription Streaming**: Real-time speech-to-text for both channels of phone conversations.

**Call Control**: Administrative functions to monitor, join, or terminate active calls.

### Performance Metrics

Track response times and performance across three key areas:

**Speech-to-Text (STT)**: Audio processing latency and accuracy metrics.

**Text-to-Speech (TTS)**: Voice synthesis speed and quality measurements.

**Large Language Model (LLM)**: AI reasoning and response generation times.

## 🔗 Webhook Integration

### Data Processing

Configure custom endpoints to receive structured data from conversations, including customer information, form submissions, and interaction summaries.

### Configuration Management

Store and retrieve webhook settings with support for multiple endpoints and custom data routing rules.

## 🔑 API Key Management

### Provider Integration

Centralized management for API keys across multiple services:

- OpenAI and Azure OpenAI for language models
- Azure Speech Services for voice processing
- Google Gemini for alternative AI capabilities
- ElevenLabs for premium voice synthesis
- Apifant services for speech-to-text and text-to-speech

### Security Features

Key status monitoring without exposing actual credentials, with support for both personal and organization-level key management.

## 🎯 Use Cases

### 📞 Customer Service Automation

Transform your customer service with AI assistants that handle inquiries 24/7, escalate complex issues to humans, and maintain conversation context across multiple touchpoints.

### 🏢 Business Process Automation

Automate routine business processes like appointment scheduling, lead qualification, order processing, and follow-up communications with intelligent conversation flows.

### 🎓 Educational Applications

Create interactive learning experiences with AI tutors that adapt to individual learning styles, provide instant feedback, and guide students through complex topics.

### 🏥 Healthcare Support

Deploy AI assistants for appointment reminders, medication adherence support, basic health information, and emergency contact routing while maintaining HIPAA compliance.

### 🛒 E-commerce Integration

Enhance online shopping with AI sales assistants that provide product recommendations, answer questions, process orders, and offer personalized shopping experiences.

### 🏦 Financial Services

Implement AI assistants for account inquiries, transaction support, financial education, and fraud prevention while maintaining strict security protocols.

## 📞 Support & Resources

- **📧 Email**: [support@apifant.com](mailto:support@apifant.com)
- **📚 Documentation**: [https://docs.apifant.com](https://docs.apifant.com)
- **🐛 Bug Reports**: [GitHub Issues](https://github.com/apifant/ai-assistant-hub/issues)

## 📄 License

This API is provided under the [Apifant Terms of Service](https://apifant.com/terms).
