# RapidAPI Setup Guide for JobCopilot

## 🚀 Quick Setup Steps

### 1. Get Your RapidAPI Key
1. Go to [RapidAPI.com](https://rapidapi.com)
2. Sign up for a free account (or log in)
3. Search for "ChatGPT API" in the marketplace
4. Subscribe to a ChatGPT API service (many free tiers available)
5. Copy your RapidAPI key from the dashboard

### 2. Popular ChatGPT APIs on RapidAPI
- **ChatGPT API** by OpenAI (Official)
- **ChatGPT API** by various providers
- **AI Text Generator** services
- **GPT-3.5/GPT-4 APIs**

### 3. Update Your .env File
Replace `your_rapidapi_key_here` with your actual RapidAPI key:
```
VITE_RAPIDAPI_KEY=your_actual_rapidapi_key_here
VITE_RAPIDAPI_HOST=chatgpt-api8.p.rapidapi.com
```

### 4. Common RapidAPI Hosts for ChatGPT
- `chatgpt-api8.p.rapidapi.com`
- `openai80.p.rapidapi.com`
- `chatgpt-best-price.p.rapidapi.com`
- `cheapest-gpt-4-turbo-gpt-4-vision-chatgpt-openai-ai-api.p.rapidapi.com`

### 5. Benefits of RapidAPI
✅ More reliable API access
✅ Better rate limits
✅ Multiple AI service options
✅ Cost-effective pricing
✅ Unified API management
✅ Free tiers available

### 6. Troubleshooting
- Make sure your RapidAPI subscription is active
- Check that the API host URL is correct
- Verify your key has sufficient credits
- Restart the development server after updating .env

## 💡 Alternative APIs
If you prefer different AI services, you can also use:
- Hugging Face APIs
- Cohere APIs
- Anthropic Claude APIs
- Google PaLM APIs

Just update the API calls in `/src/utils/openai.js` accordingly.
