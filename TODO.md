# TODO: Make Bot Support Both Slash Commands and Prefix Commands

## Overview
Convert the Discord bot from slash-only commands to hybrid commands supporting both slash commands and prefix commands with "x" prefix.

## Steps
1. [x] Update config.yaml to change prefix from "/" to "x"
2. [ ] Update admin.py: Add prefix command versions for all slash commands
3. [ ] Update verification.py: Add prefix command versions
4. [ ] Update utility.py: Add prefix command versions
5. [ ] Update tickets.py: Add prefix command versions
6. [ ] Update temp_voice.py: Add prefix command versions
7. [ ] Update social_alerts.py: Add prefix command versions
8. [ ] Update roles.py: Add prefix command versions
9. [ ] Update music.py: Add prefix command versions
10. [ ] Update moderation.py: Add prefix command versions
11. [ ] Update leveling.py: Add prefix command versions
12. [ ] Update giveaways.py: Add prefix command versions
13. [ ] Update games.py: Add prefix command versions
14. [ ] Update economy.py: Add prefix command versions
15. [ ] Update analytics.py: Add prefix command versions
16. [ ] Update ai_chat.py: Add prefix command versions
17. [ ] Test the bot to ensure both command types work
18. [ ] Update documentation if needed

## Notes
- For each slash command, add a corresponding @commands.command with the same logic
- Use the same function body to avoid code duplication
- Ensure permissions and checks are applied to both versions
- Prefix commands will use traditional argument parsing, slash commands use describe
