# Generative AI Terms

- Tokens
  - How a model processes text
  - A chunk of text - character, word, sub-word
  - Same text can have different token counts than character counts
  - Tokens are the units for input, output, cost, limits
  - Longer prompts use more tokens 
    - Higher cost
    - More latency

- System prompts 
  - Used for global instructions
    - Tone
    - Rules
    - Expertise
    - Safety
  - Defines role, behavior and constraints
  - Higher priority than user prompt

- User Prompt
  - Contains task or question to be answered
  - Model creates output by combining user and system prompts

- Chat Completions API
  - Generates responses based on conversation history
  - Accepts input as a list of messages
    - User prompts
    - System prompts
    - Assistants
  - Maintains context across multiple turns
  - Used for conversational experiences
    - Chatbots
    - Assistants
  - Requires model deployment name and messages payload

- Multi-Modality/Multi-modal models
  - Modality
    - Type of data 
      - Text 
      - Image
      - Audio
      - Video
  - Unimodal models only support one data type
  - Multi-modal models process multipile input modalities together
  - Enables better understanding by combining context across inputs
  - Can accept mixed inputs and can produce mixed outputs