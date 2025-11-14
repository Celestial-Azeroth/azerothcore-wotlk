# AzerothCore Server

## Our Goal
This is a Lunitha focused fork of [AzerothCore](https://github.com/azerothcore/azerothcore-wotlk) designed to create an open-source server implementation that aligns with the ideals of the Lunitha Movement. The mission is transparency and fun, ensuring anyone using this code knows exactly what is happening behind the scenes.  
**This repository serves as a public source code reference** that tries to follow the Lunitha way. Providing complete transparency in server code and modifications for those who wish to preserve and play classic games safely.

## What is AzerothCore?
AzerothCore is an open-source game server application and framework designed for hosting massively multiplayer online role-playing games (MMORPGs). It is based on World of Warcraft and recreates the gameplay experience from patch 3.3.5a (Wrath of the Lich King).  
The original code is based on MaNGOS, TrinityCore, and SunwellCore and provides a solid foundation for creating servers that mimic the mechanics and behavior of the official WoW servers.

## Our Modifications
Below are the changes we have made to the original AzerothCore source:  
| Feature               | Description                                                                  | Status   |
|-----------------------|------------------------------------------------------------------------------|----------|
| Auto Account Creation | Automatically creates new accounts when players log in with new credentials. | Not Possible  |  
| [Reputation Hook](https://github.com/Celestial-Azeroth/azerothcore-wotlk/tree/feature/reputationChangedHook) | Adds a hook to allow modification of reputation gain amounts. | Officially Merged |  

**Security**: All passwords are properly hashed using industry-standard methods before storage.

## Getting Started
**For Players**: This repository is for source code transparency and educational purposes only.  
**For Developers**: If you want to run your own server for personal/educational use, we recommend following the comprehensive setup guide in the [original AzerothCore repository](https://github.com/azerothcore/azerothcore-wotlk).

## Transparency & Safety
- **Open Source**: All our modifications are publicly visible
- **Secure**: We use industry-standard password hashing
- **Game Focused**: Our goal is purely to provide a fun and safe gaming experience

## Links
- **Original Project**: [AzerothCore WOTLK](https://github.com/azerothcore/azerothcore-wotlk)
- **Original Credits**: [See AzerothCore Authors](https://github.com/azerothcore/azerothcore-wotlk/blob/master/AUTHORS)
- **Original License**: [AzerothCore License](https://github.com/azerothcore/azerothcore-wotlk/blob/master/LICENSE)
- **Original Documentation**: [AzerothCore Wiki](https://www.azerothcore.org/wiki)

## License
This project maintains the same licensing as the original AzerothCore:
- New AzerothCore source components: [GNU GPL v2](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)
- Old sources based on MaNGOS/TrinityCore: [GNU GPL v2](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)

**Important**: This is not an official Blizzard Entertainment product and is not affiliated with or endorsed by World of Warcraft or Blizzard Entertainment. This project is for educational and preservation purposes only.
