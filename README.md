# Add to Calendar
An iOS Shortcut for quickly adding the contents of your screen to your Calendar

[Get the Shortcut here.](https://www.icloud.com/shortcuts/77505cb6f9854801a5cfd77ab8781b2f)

**Version 4.0** Adds a model selector, and with in support for Gemini and the Apple Intelligence 'Use Model' Shortcuts action

Whenever you're looking at something on your iPhone, iPad, or Mac that represents an event, such as a concert poster, email booking confirmation, webpage, or even the plans you've made with a friend in a messenger app, just invoke Siri and say: **“Add to Calendar”**. 

The shortcut will:

1. Take a screenshot  
2. Send it to OpenAI for ChatGPT with instructions  
3. Compose a calendar event for your review before saving  

When you run it from the shortcuts app, you'll see a menu with ways to continue and preferences to explore

to set up and run this shortcut you will need an API key from OpenAI
if you don't have one, [get started here](https://platform.openai.com/signup) or use this [step by step guide on YouTube](https://youtu.be/OB99E7Y1cMA?si=VOxTPZqEyVJ099PH).
 Once you have an API key, the first time you run the shortcut you'll be prompted to provide it.

## Key Features

- Works seamlessly with Siri
- Adds a relevant emoji to the event title
- Share Sheet support to easily work with images or screenshots 
- support for multi-event output, and multi image input
- Includes a summary and booking reference (if found) in the notes  
- Uses web search to find additional context like location address or event duration (if they aren't found in the screenshot)
- if a start time or date cant be identified or inferred the shortcut will prompt you to supply them
- The Screenshot that is sent to chatGPT is also attatched to the newly created calendar event. This is great for barcodes and event tickets
- Smart, Easy, and Unobtrusive update checks. API keys and User Preferences are stored in your iCloud Drive within the Shortucts folder. this way updates can be made to the shortcut without requiring any reconfiguring. Update checks run right at the end of the shortcut so they never get in the way of adding events and if there's no update to downloaded you'll never even notice they ran.

> ⚠️ The screenshot is shared with ChatGPT. Please ensure you’re comfortable with its contents before running the shortcut.
