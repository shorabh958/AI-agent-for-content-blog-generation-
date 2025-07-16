🎯 Project Title:
AI Agent to Auto-Generate Blog Posts and Thumbnails from YouTube Videos using Gumloop

📌 Description:
This project uses a no-code AI agent workflow (built in Gumloop) that takes a YouTube video link and automatically:

Extracts the video transcript.

Generates a full blog post from it using structured prompts.

Creates a thumbnail image URL using the video ID.

Posts the blog draft to a Ghost CMS instance via API.

🔧 Architecture:
🧠 LLM Used: GPT-4 (Mini/Max for different steps)

🔗 Agents: Multiple GPT nodes working in parallel for summarization, blog post generation, and title crafting

🌐 API Integration: Ghost CMS API + n8n webhook compatible

🧩 Subflows: Blog generation, thumbnail extraction, structured prompt chaining

🔁 Trigger: Manual input (YouTube URL), but extensible to scheduler or webhook
