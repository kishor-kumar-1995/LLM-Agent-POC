# LLM-Agent-POC

Simple browser-based LLM Agent POC using AI Pipe.  
Open `index.html` in the browser or visit the GitHub Pages link after enabling Pages.

## How to use
1. Open the page (GitHub Pages or local file).
2. In the **Model Picker** widget (top-right area), paste your **AI Pipe / OpenRouter** API key.
3. Type a prompt and press **Send**.

## Notes
- Tool calls available: `run_code` (executes JS in sandbox) and `ai_pipe` (re-queries AI Pipe).
- If you want *live web search*, add a search API (Bing/SerpAPI) and update `toolGoogleSearch`.
