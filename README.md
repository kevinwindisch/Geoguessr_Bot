Based on the code created by Enric Domingo. (https://medium.com/@enricdomingo/coding-a-geoguessr-autonomous-ai-bot-with-vision-llms-gpt-4o-claude-3-5-and-gemini-1-5-908faf3bc3c7)

Version 1.01:
 - moved cursor off map after guess to make screenshots capture more
 - set default model to gemini-1.5-flash
 - removed need to get "play next round" screen region
 - adjusted LLM prompt to be more specific and exclude regions not included in Google Street View
