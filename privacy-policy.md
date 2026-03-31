# Privacy Policy for Compose Assistant

*Last updated: March 31, 2026*

## Overview

Compose Assistant is a browser extension that provides AI-powered writing assistance, chat, and form-filling capabilities. This policy explains what data we collect, how we use it, and your rights.

## What We Collect

Compose Assistant collects the following data to provide its services:

- **Account information**: Name and email address via Google Sign-In, used for authentication and personalizing drafts.
- **Text field content**: The content of the text field you are actively composing in is sent to our server to generate AI-assisted drafts. This includes surrounding page context (e.g., conversation thread) needed to produce contextually relevant responses.
- **Page metadata**: The URL and page title of the site you are composing on, used to determine platform-specific formatting (e.g., LinkedIn vs Gmail).
- **Chat messages**: Messages you send through the built-in chat panel are processed by AI models to generate responses. Chat history is stored locally in your browser.
- **Page content** (Page mode): When you use the "Page" chat mode, the visible text content of the current page is sent to our server to provide context-aware responses.
- **File uploads**: Images or files you attach in the chat panel are sent to our server for processing. These are not permanently stored.
- **User preferences**: Your selected LLM provider, model, and API keys (if using Bring Your Own Key), stored locally in your browser only.
- **Feedback**: Bug reports and feature requests you submit through the extension, along with your user ID and extension version.
- **Notes**: Personal notes or preferences you save through the extension are stored in your memory profile.

## Permissions Explained

- **activeTab / host_permissions**: Required to read page content and insert generated text into text fields on any website you visit.
- **storage**: Stores your preferences, chat history, and authentication state locally.
- **scripting**: Injects the content script to interact with text fields on web pages.
- **identity**: Handles Google Sign-In authentication.
- **contextMenus**: Provides right-click menu options for settings and chat.
- **tabs**: Detects the active tab to deliver compose results to the correct page.
- **debugger** (optional): When granted, enables more reliable text insertion on sites that block standard input methods (e.g., some rich text editors). This permission is requested on-demand and can be denied without affecting core functionality.

## How We Use Your Data

- Text content and page context are sent to our server and processed by AI language models (Google Gemini by default, or your chosen BYOK provider) solely to generate writing suggestions and chat responses.
- Account information is used to maintain your personal memory context so the assistant can provide personalized drafts.
- Feedback is used to improve the extension and is associated with your user ID.
- We do not sell, share, or transfer your data to third parties for advertising or marketing purposes.

## Bring Your Own Key (BYOK)

- If you configure a third-party AI provider (OpenAI, Anthropic, OpenRouter, or a custom endpoint), your API key is stored locally in your browser and sent to our server only when making API calls on your behalf.
- Your API key is transmitted over HTTPS and is not stored on our servers.
- When using BYOK, your text content is forwarded to your chosen provider according to their own privacy policies.

## Data Storage

- User preferences, authentication state, and chat history are stored locally in your browser via Chrome Storage.
- Writing context (memories and notes) is stored in Supermemory, isolated per user account. Each user can only access their own data.
- Text content sent for draft generation is not permanently stored on our servers.
- Debug/history data (compose traces) is stored locally in your browser and limited to the 5 most recent requests.

## Data Security

- All data is transmitted over HTTPS (encrypted in transit).
- Each user's data is isolated by unique user ID.
- Google OAuth tokens are used transiently and not persisted on our servers.
- BYOK API keys are stored in local browser storage only (not synced across devices).

## Your Rights

- You can delete your stored memories at any time through the extension's chat panel (Memories viewer).
- You can clear your chat history at any time using the chat panel controls.
- You can sign out at any time, which stops all data collection.
- Uninstalling the extension removes all locally stored data.
- You can deny optional permissions (like debugger) without losing core functionality.

## Contact

If you have questions about this privacy policy, contact kevindoshi17@gmail.com.
