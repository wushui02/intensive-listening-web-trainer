# Intensive Listening Web Trainer

This repository hosts the Web / iPad Trainer for **Intensive Listening Desk**.

Current release: v1.0.1

It is a static browser app designed for focused English listening practice on iPad, tablets, and desktop browsers.

## What It Does

- Imports an `.ild.json` project exported from Intensive Listening Desk.
- Imports a local audio file selected by the user.
- Plays sentence-level A-B segments based on `startTime` and `endTime`.
- Lets users type dictation, check answers, mark status, and add error annotations.
- Exports an updated `.ild.json` after practice.

## What It Does Not Do

- It does not run Whisper transcription.
- It does not use ffmpeg.
- It does not upload audio.
- It does not require a backend.
- It does not require login, cloud sync, or a database.

## Typical iPad Workflow

1. Use the desktop Intensive Listening Desk app to import audio and generate an `.ild.json` project.
2. Save the `.ild.json` and audio file to iCloud Drive, OneDrive, Google Drive, or another file sync folder.
3. Open this Web Trainer URL on iPad.
4. Import the `.ild.json`.
5. Import the matching audio file.
6. Practice sentence by sentence.
7. Export the updated `.ild.json`.
8. Save it back to your cloud folder.

## Privacy

Audio and project files are handled locally in the browser. This static site does not include any server-side upload logic.

## GitHub Pages

This repository is intended to be deployed with GitHub Pages:

- Source: Deploy from a branch
- Branch: `main`
- Folder: `/root`
