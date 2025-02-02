## Make Automation to save text in Notion from a Telegram Bot message

**Have you ever felt overwhelmed by a collection of useful resources scattered across various platforms?** I’d like to share an automation I developed to help organize these resources into multiple Notion pages.

This automation uses a **Telegram bot as a trigger and includes several commands for different Notion pages**. When you send a message to the bot, it performs these actions:

Sending a URL: If you send a URL, the bot performs **web scraping** to gather content details and generates a brief description using Groq AI. This description, along with the link, is automatically added to the specified Notion page.

Sending Plain Text: If you send **text**, it is **directly added** to the designated Notion page.

Additionally, there is a Google Sheet that stores the commands sent, ensuring the content is organized in the appropriate Notion page. Another Google Sheet maps each page (and corresponding bot command) to its Notion ID, allowing for the inclusion of various types of content in different Notion pages.

While this automation is quite basic, I believe it has great potential for streamlining the organization of diverse resources. I hope you find it helpful!
