# Styler — Chat Guardian Style and AI Persona customizer

Customize the look and feel of the **Chat Guardian** dashboard and change the AI's moderation mood/personality.

## Features
- **Dashboard Styles Overrides**: Custom stylesheet themes using CSS variables inject presets into the DOM to style the dashboard.
- **UI Themes**: Matrix Green, Crimson Vampire, Cyberpunk Purple, Monochrome Light, and Classic Dark.
- **AI Moderator Mood**: Changes the system prompt of the content safety AI to adopt different personality traits.
- **Mood Presets**: Strict (default), Friendly, Sarcastic, Passive-Aggressive, Pirate, and Moodswings (randomizes mood with every safety check).

## Installation

### Method A — Via the Dashboard (Recommended)
1. Open the Chat Guardian dashboard.
2. Navigate to the **Plugins** tab.
3. Click **Install** next to **Styler**.
4. Enable the plugin using the toggle switch. The navigation sidebar will automatically update with the **Styler** customize tab.

### Method B — Manual Installation
1. Clone this repository into the `plugins/styler` folder of your Chat Guardian codebase:
   ```bash
   git clone https://github.com/timpim-dev/Styler_for_chatGuardian plugins/styler
   ```
2. Restart the Chat Guardian service.
