[theme.theme.css](https://github.com/user-attachments/files/23559191/theme.theme.css)
/**
 * @name Custom Theme
 * @author Potato
 * @version 1.0
 * @description A customizable BetterDiscord theme
 * @source https://github.com/
 */

:root {
  /* Primary Colors */<img width="962" height="1040" alt="preview" src="https://github.com/user-attachments/assets/8b66151b-dd67-4885-9da4-8b73ae282e9c" />

  --primary-color: #5865F2;
  --secondary-color: #2C2F33;
  --tertiary-color: #23272A;
  --accent-color: #7289DA;
  
  /* Text Colors */
  --text-primary: #FFFFFF;
  --text-secondary: #B9BBBE;
  --text-muted: #72767D;
  
  /* Background Colors */
  --bg-primary: #36393F;
  --bg-secondary: #2F3136;
  --bg-tertiary: #202225;
  
  /* Status Colors */
  --success-color: #43B581;
  --warning-color: #FAA61A;
  --danger-color: #F04747;
  --info-color: #00B0F4;
}

/* Main background */
.app {
  background-color: var(--bg-tertiary) !important;
}

/* Server list */
.guilds__13579 {
  background-color: var(--bg-primary) !important;
}

/* Channel list */
.sidebar__81b00 {
  background-color: var(--bg-secondary) !important;
}

/* Chat area */
.chat__8f78e {
  background-color: var(--bg-tertiary) !important;
}

/* User list */
.members__87e81 {
  background-color: var(--bg-secondary) !important;
}

/* Messages */
.message__8eea5 {
  color: var(--text-primary) !important;
}[README.md](https://github.com/user-attachments/files/23559192/README.md)
# Menomilan Discord Theme

A custom BetterDiscord theme.

## Installation

1. Download the `.theme.css` file
2. Place it in your BetterDiscord themes folder: `%appdata%\BetterDiscord\themes\`
3. Open Discord and enable it in User Settings → BetterDiscord → Themes

## Customization

Edit the color variables at the top of the `.css` file to customize the theme.

---

Made with ❤️


/* Buttons */
button {
  background-color: var(--primary-color) !important;node_modules/
.DS_Store
.env
*.log

  color: var(--text-primary) !important;
}

button:hover {
  background-color: var(--accent-color) !important;
}

/* Input fields */
input,
textarea {
  background-color: var(--bg-primary) !important;
  color: var(--text-primary) !important;
  border-color: var(--primary-color) !important;
}

/* Scrollbar */
::-webkit-scrollbar {
  width: 8px;
}

::-webkit-scrollbar-track {
  background-color: var(--bg-secondary);
}

::-webkit-scrollbar-thumb {
  background-color: var(--primary-color);
  border-radius: 4px;
}

::-webkit-scrollbar-thumb:hover {
  background-color: var(--accent-color);
}
