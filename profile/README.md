<h1 align="center">
  <img src="https://raw.githubusercontent.com/ReMaverickNet/.github/main/assets/remaverick-icon.svg" alt="ReMaverick icon" width="72" height="72" valign="middle">
  ReMaverick
</h1>

**ReMaverick** is an independent community research and preservation project focused on **SPLITGATE: Arena Reloaded** and the infrastructure that keeps it playable.

1047 Games has announced that active development has ended and that, as of **September 3, 2026**, Arena Reloaded has moved from dedicated servers and matchmaking to peer-to-peer hosting with a server browser. ReMaverick exists to document the game before and after that transition, preserve reproducible technical knowledge, and investigate whether community-operated infrastructure can keep the game healthy long-term.

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

## Current technical understanding

First-party information gathered shortly before the P2P transition indicates that **Maverick is a shared backend for both SPLITGATE: Arena Reloaded and EMPULSE**. The backend can dynamically serve either game, reflecting the close technical relationship between the two titles. This helps explain the shared service and protocol behaviour observed in ReMaverick's network research.

The P2P transition removes the official dedicated-server path from normal operation, with **RedKard disabled under P2P**. Arena Royale is expected to transition to P2P, while the former 64-player battle royale is not planned for P2P because of the hosting demands involved.

A future **dedicated server executable** has also been discussed as a possibility, although no implementation, architecture, or commitment has been confirmed. Determining whether such an approach is technically feasible remains one of ReMaverick's longer-term research goals.

The project records these statements as first-party information while keeping confirmed facts, observations, inferences, and hypotheses separate in the research repository.

## Contact & legal

ReMaverick is an independent community research and preservation project and is not affiliated with, endorsed by, or operated by 1047 Games, Inc.

**SPLITGATE** and related names, logos, and other trademarks are the property of their respective owners, including 1047 Games, Inc.

For questions, corrections, takedown requests, legal concerns, or other matters relating to the project, contact **[maverick@xdan.me](mailto:maverick@xdan.me)**.

Please do not send passwords, authentication tokens, personal information, private communications, or proprietary game files.

## Why "ReMaverick"?

**Maverick** is the shared backend and internal API service name used by 1047 Games for **SPLITGATE: Arena Reloaded and EMPULSE**. Since this project investigates preservation and the potential return of community-operated dedicated infrastructure, the name **Re**Maverick works well.
