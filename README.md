# CodTech_task-4

CodTech IT Solutions - VOICE-CONTROLLED APP INTERFACE


COMPANY : CODETECH IT SOLUTIONS

NAME : PREETHI

INTERN ID :CT04DZ111

DOMAIN : FIGMA WEB DEVELOPMENT

DURATION :1 MONTH

MENTOR : NEELA SANTOSH


🏠 Smart Home App Interface

To designing a voice-controlled smart home app interface using Figma, focusing purely on the front-end UX. This will help to create a clean, intuitive, and emotionally resonant experience for commands like “Turn off the lights” or “Set thermostat to 22°C.”

🧱 Layout Structure
1. Home Dashboard Screen
Top Bar

App name or logo

Profile icon

Settings (gear icon)

Main Section

Room cards (Living Room, Bedroom, Kitchen)

Each card shows device status (e.g., lights on, temperature)

Tap or voice to control

Floating Mic Button

Bottom center or bottom right

Pulsing animation when active

Tooltip: “Tap to speak”

🎤 Voice Interaction Overlay
When mic is activated:

Full-screen semi-transparent overlay

Dark blur background

Centered waveform animation

“Listening…” text with subtle glow

Cancel button (X icon)

Transcript Bubble

Appears below waveform

Shows live speech-to-text

Editable with a pencil icon

Confirmation Toast

Bottom pop-up: “Lights turned off in Living Room”

Icon + text + subtle animation

🧊 Device Control Cards
Each room card includes:

Element	Description
🏠 Room Name	“Living Room”
💡 Device Icon	Light, thermostat, speaker, etc.
🔘 Status Toggle	On/Off switch
📊 Quick Stats	Brightness %, temperature, etc.
🎙️ Voice Shortcut	“Say: Turn off the lights” hint
Use Auto Layout for responsive resizing and Variants for toggled states.

🧘 Emotional Design Touches


Color Palette: Soft neutrals with accent colors for active states (e.g., warm yellow for lights, cool blue for thermostat)

Typography: Rounded sans-serif like Inter or SF Pro for friendliness









🏠 HOME PAGE



🟦 Top Section: Voice Command
Floating Mic Button

Centered or bottom-right

Pulsing animation when idle

Tooltip: “Tap to speak”

Voice Overlay (on activation)

Full-screen blur with waveform animation

“Listening…” text + live transcript

Cancel (X) and Help (?) icons



🟨 Middle Section: Recent Commands

Scrollable horizontal list or vertical stack

Each card shows:

🗣️ Command text (e.g., “Set thermostat to 22°C”)

✅ Status (Success, Failed, Pending)

🕒 Timestamp

🔁 Re-run button





🟩 Bottom Section: Quick Controls


Room Cards or Device Tiles

Living Room, Bedroom, Kitchen, etc.

Each tile includes:

💡 Device icon (light, thermostat, speaker)

🔘 Toggle switch (on/off)

📊 Quick stat (e.g., brightness %, temp °C)

🎙️ Voice hint: “Say: Dim the lights”

#OUTPUT


<img width="124" height="362" alt="Image" src="https://github.com/user-attachments/assets/3dacbc30-b740-4a63-b5e1-e0cc7eb021ca" />

⚙️ SETTING PAGE


🟣 Voice Preferences
🎙️ Voice Assistant Toggle

Enable/disable voice control

Choose voice persona (e.g., Calm, Energetic, Neutral)

Language & accent selection

🗣️ Sample Commands Preview

“Say: Lock the door”

“Say: Set temperature to 22°C”

🔊 Voice Feedback Settings

On/off for spoken confirmations

Volume control slider

🟢 Device Management


🏠 Connected Devices List

Room-based grouping (Living Room, Bedroom, etc.)

Device name, type, status (online/offline)

Edit, remove, or rename device



➕ Add New Device

CTA button with modal or guided flow

🔄 Sync Devices



🔵 Temperature Settings


🌡️ Default Temperature Range

Min/max sliders (e.g., 18°C – 28°C)

Preferred comfort setting (e.g., 22°C)

🕒 Schedule Temperature

Daily or weekly routines

Example: “Set to 22°C at 7 AM”

❄️ Eco Mode Toggle

Energy-saving temperature presets

🟡 App Info & Maintenance

📱 App Version

Display current version

“Check for updates” button

#OUTPUT

<img width="121" height="372" alt="Image" src="https://github.com/user-attachments/assets/bd1b1f5c-5fc4-4234-9a0b-f64e87b69e33" />



👤 PROFILE PAGE


🟣 Contact Information
📧 Email Address

Editable field with validation

Tooltip: “Used for notifications and account recovery”

📱 Phone Number

Optional field

Used for SMS alerts or two-factor authentication

🏠 Home Address (optional)

For location-based automation (e.g., geofencing)

🟢 Account Management


🔐 Change Password

“Current Password” + “New Password” fields

Strength meter + visibility toggle

CTA: “Update Password”

🕵️ Privacy Settings

Toggle for data sharing preferences

“Manage voice history” link

“Download account data” option

🔒 Two-Factor Authentication

Enable/disable

Choose method: SMS, email, authenticator app

🔵 Linked Devices



📱 Device List

Shows all devices linked to the account

Device name, type, last active

Option to rename or unlink



➕ Add Device

CTA button with modal flow

QR scan or manual entry

🔄 Sync Devices

#OUTPUT


<img width="95" height="347" alt="Image" src="https://github.com/user-attachments/assets/b176d2af-0c78-4689-9183-0e1e0e5ff5be" />


🧪 Figma Tips


Use Interactive Components for mic button and confirmation toasts

Create Prototypes with voice command simulation (e.g., clicking mic triggers overlay)

Use Smart Animate for transitions like waveform pulsing and toast fade-in

Organize with Pages: Dashboard, Voice Overlay, Device Cards, Confirmation States.
