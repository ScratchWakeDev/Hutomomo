# Hutomomo Discord Bot

**Hutomomo** is a Discord bot designed to streamline moderation by relaying ban information between servers. It helps server admins manage banned users, report issues, and even includes interactive features for banning users.

## Features

### 🔒 Ban Message Relay
Hutomomo listens for ban events in Discord servers and automatically relays the ban messages to other designated servers. This makes it easy for server admins to stay informed about users banned from different communities.

### 📜 Evidence Attachment
When relaying a ban message, Hutomomo allows you to attach additional evidence to support the ban, ensuring other servers have all the necessary context regarding the ban decision.

### 🚩 Report Relay Messages
Relay messages sent by the bot can be reported if users or admins believe there's an issue with the message. This helps maintain accountability and allows for the correction of any mistakes.

### 🔘 Quick Ban Button
Hutomomo includes a convenient button feature that allows users to quickly ban someone directly from the relay message. This simplifies the banning process for admins and moderators.

## How It Works

1. **Listening for Bans**: Hutomomo monitors for ban actions in the server. When a user is banned, the bot captures the ban message, along with the banned user's details and the reason for the ban.
   
2. **Relay to Other Servers**: Once the ban is detected, the bot automatically relays the ban information (including the message, user details, and ban reason) to connected servers.

3. **Adding Evidence**: Admins and moderators can append additional evidence (screenshots, chat logs, etc.) to the relayed ban messages to provide further context.

4. **Report Ban Messages**: Users can report a relayed ban message if they believe it contains errors or misjudgments. These reports are logged and reviewed by server admins.

5. **Ban Button**: The relay messages come with a "Ban" button, making it easy for server admins to quickly ban a user across multiple servers when necessary.

## Privacy & Data Handling

We take your privacy seriously. Hutomomo only collects the minimum necessary information to function, including:
- Ban messages
- User IDs of banned individuals
- Server configurations (guilds)
- Ban reasons and related evidence

For full details, check our [Privacy Policy](./PRIVACY.md).

## Getting Started

1. **Invite the Bot**: Use [this link](https://discord.com/oauth2/authorize?client_id=1245599636073222227) to invite Hutomomo to your server.
2. **Set Up Relay Channels**: Configure the relay channels in the connected servers where the bot will post ban messages.
3. **Start Monitoring**: Once set up, Hutomomo will automatically listen for ban events and relay messages to other servers.

## Support

For support or questions, join our [Discord Support Server](https://discord.gg/XEUBKSSemZ) or email us at [hutomomodev@gmail.com](mailto:hutomomodev@gmail.com).

Thank you for using Hutomomo!
