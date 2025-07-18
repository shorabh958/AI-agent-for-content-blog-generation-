Project Title:
AI Agent to Auto-Generate Blog Posts and Thumbnails from YouTube Videos using Gumloop
---------------------
📌 Description:
This project uses a no-code AI agent workflow (built in Gumloop) that takes a YouTube video link and automatically:
---------------------
1. Extracts the video transcript.
2. Generates a full blog post from it using structured prompts.
3. Creates a thumbnail image URL using the video ID.
4. Posts the blog draft to a Ghost CMS instance via API.
----------------------
🔧 Architecture:
🧠 LLM Used: GPT-4 (Mini/Max for different steps)

🔗 Agents: Multiple GPT nodes working in parallel for summarization, blog post generation, and title crafting

🌐 API Integration: Ghost CMS API + n8n webhook compatible

🧩 Subflows: Blog generation, thumbnail extraction, structured prompt chaining

🔁 Trigger: Manual input (YouTube URL), but extensible to scheduler or webhook



> **Sample Input:**
> `https://www.youtube.com/watch?v=m7csN192BQ4&ab_channel=RetroGameCo`


✅ Output:
Blog post: HTML content with intro, mid-review, and final verdict

> **Thumbnail**
Thumbnail URL: https://img.youtube.com/vi/m7csNl92BQ4/hqdefault.jpg

> **Working Agent**
Gumloop URL: https://www.gumloop.com/pipeline?workbook_id=nVCdNRwDXrrbPqnkQGRwVh 
Optional: Auto-posts to Ghost blog
