<h1 align="center">
  <img src="https://raw.githubusercontent.com/ReMaverickNet/.github/main/assets/remaverick-icon.svg" alt="ReMaverick icon" width="72" height="72" valign="middle">
  ReMaverick
</h1>

**ReMaverick** is an independent community research and preservation project focused on **SPLITGATE: Arena Reloaded** and the infrastructure that keeps it playable.

1047 Games has announced that active development is ending and that, on **September 3, 2026**, Arena Reloaded will move from dedicated servers and matchmaking to peer-to-peer hosting with a server browser. ReMaverick exists to document the game before and after that transition, preserve reproducible technical knowledge, and investigate whether community-operated infrastructure can keep the game healthy long-term.

## Areas of research

- Networking and session establishment
- Server discovery and server-browser behaviour
- Matchmaking and online services
- Unreal Engine networking and runtime behaviour
- Build and version archaeology
- Windows and Linux/Proton compatibility
- RedKard / MerlinAntiCheat integration, from an observational and compatibility perspective
- Community-server feasibility
- Preservation tooling and documentation

## Contributing

You do not need to be a reverse engineer to contribute. A carefully documented test session, packet capture, game log, build observation, or compatibility report can be valuable.

AI assistance is **encouraged** for log reduction, scripting, research, translation, hypothesis generation, and analysis. Contributions must document how AI was used and what was independently verified.

Start with the [research repository](https://github.com/ReMaverickNet/research).

## Scope

ReMaverick is not affiliated with, endorsed by, or operated by 1047 Games.

Do not commit proprietary game binaries, encrypted/packaged game content, credentials, personal information, or other material that should not be redistributed. Preserve observations, hashes, metadata, and analysis instead.

Anti-cheat research is limited to understanding behaviour, compatibility, architecture, and interoperability. We do not publish instructions for disabling, bypassing, tampering with, or evading anti-cheat systems.

### Community collaboration

ReMaverickNet is an independent research and preservation project. We are currently collaborating with members of [Splitgate Lifers](https://discord.gg/gyXGrSrhpD), which is a community-led Splitgate: Arena Reloaded revival effort, while focusing on investigating the game's networking and the potential feasibility of community-hosted authoritative infrastructure following the transition away from official dedicated matchmaking, particularly in the [research repository](https://github.com/ReMaverickNet/research).

SGLifers is independently focused on keeping the game's community active through P2P and other community initiatives, while ReMaverickNet's focused primarily on technical research and preservation. The two projects remain independent though, and this work is not affiliated with or endorsed by 1047 Games.

## Contact & legal

ReMaverick is an independent community research and preservation project and is not affiliated with, endorsed by, or operated by 1047 Games, Inc.

**SPLITGATE** and related names, logos, and other trademarks are the property of their respective owners, including 1047 Games, Inc.

For questions, corrections, takedown requests, legal concerns, or other matters relating to the project, contact **[maverick@xdan.me](mailto:maverick@xdan.me)**.

Please do not send passwords, authentication tokens, personal information, private communications, or proprietary game files.

## Why "ReMaverick"?

To my knowledge, Maverick was the name given to Splitgate 2's primary backend domain and internal API service name for 1047 Games. Since this aims to return Splitgate AR servers via dedicated server hosting as the final potential goal of this project, the name **Re**Maverick works well.
