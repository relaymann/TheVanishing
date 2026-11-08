# THE VANISHING — NeoForge 1.21.1

This repository contains the current **THE VANISHING 0.1.1 AI/entity upgrade source package**.

## Source package

The complete project source is stored at:

`THE_VANISHING_NeoForge_1.21.1_AI_Upgrade_0.1.1_source.zip`

Extract the archive. The Gradle project is inside the `thevanishing/` directory.

## Build

Requirements:
- Java 21
- Gradle wrapper included in the source archive
- NeoForge 1.21.1 development dependencies (downloaded by Gradle)

From the extracted `thevanishing/` directory:

```bash
./gradlew build
```

On Windows:

```bat
gradlew.bat build
```

The compiled mod JAR is produced under `build/libs/`.

## Included systems

- Existing story characters and canon documentation
- Character profile and dialogue logic
- Persistent character encounter and social memories
- Mood and context-aware interaction behavior
- Null entity stalking, awareness, target memory, and disturbance cooldown logic
- World-persistent story state
- Project and story audit scripts

## Verification status

The source package includes structural and story/AI audit scripts and a build-status report. The previous handoff passed the offline audits; a full Gradle compilation and in-game multiplayer test were not completed in that environment. Run the Gradle build before treating this source snapshot as release-ready.

## Project continuity

This is an update to the existing THE VANISHING project, not a replacement story. Preserve established lore, character relationships, and Raging's established energetic personality and speech mannerisms when extending the project.