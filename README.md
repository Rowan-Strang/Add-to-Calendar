# Add-to-Calendar
iOS Shortcut/Siri Extension for quickly adding events on screen to your Calendar

[Direct Download](https://www.icloud.com/shortcuts/1f2fd3a624224184b77f2c4313a90391)

Whenever you're looking at something on your iPhone, iPad, or Mac that represents an event, such as a concert poster, email booking confirmation, webpage, or the plans you've made with a friend in a messenger app, just invoke Siri and say: **“Add to Calendar”** to run this shortcut.

The shortcut will:

1. Take a screenshot  
2. Send it to ChatGPT to extract event details  
3. Compose a calendar event for your review before saving  

You can also run this shortcut from the Share Sheet to send a screenshot or image you already have.
Or, if you start within the Shortcuts app, you'll be presented with a device-specific contextual menu.


to set up and run this shortcut you will need an API key from OpenAI
if you don't have one, [get started here](https://platform.openai.com/signup) or use this [step by step guide on YouTube](https://youtu.be/OB99E7Y1cMA?si=VOxTPZqEyVJ099PH)
beyond that, this shortcut is very easy to setup and use. (but please do reach out If you get confused)

By calling the ChatGPT API, this shortcut leverages structured outputs for clean and reliable results.  
As long as the event title is visible (or can be inferred), and a start time and/or location are present in the screenshot, the shortcut performs reliably.  
If a date or start time can’t be found, you’ll be prompted to provide one manually.

## Key Features

- Works seamlessly with Siri — invoke the shortcut by voice or by typing to Siri from anywhere in the system to instantly build a new event
- Fully self-contained — no reliance on third-party shortcut apps or additional helper shortcuts; everything runs in one seamless, easy to set up, native experience
- Adds a relevant emoji to the event title
- Share Sheet support — run the shortcut directly from any existing image or screenshot 
- multi-event output (when relevant)
- Multi image input (from the share-sheet or menu)
- Includes a summary and booking reference (if found) in the notes  
- Uses web search to find additional context like location address or event duration (if they aren't found in the screenshot)  
- Attaches the screenshot directly to the calendar event so you'll always have a record of the original event  
- Timezone support — events are created with accurate time zone information  
- Contextual menus — when run from the Shortcuts app directly, you're presented with a device-specific menu where you can upload screenshots, open the camera, report bugs, or navigate elsewhere before continuing  
- Smart and easy updating — once an event is added to your calendar, the shortcut checks RoutineHub for updates. If a newer version is available, you’ll be prompted to download it. Your API key is copied to your clipboard with a short expiry, and the updated shortcut link is opened automatically — making upgrades fast and effortless

> ⚠️ The screenshot is shared with ChatGPT. Please ensure you’re comfortable with its contents before running the shortcut.
