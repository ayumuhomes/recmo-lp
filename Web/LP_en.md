# Recmo

## From Recording to Remembering.

**One-tap recording. Local transcription. Auto-saved to your notes.**

[Download on the App Store](https://apps.apple.com/app/id6756238386)

---

## Sound familiar?

- "What did we decide in that meeting...?" Can't remember afterward
- Can't focus on the conversation while taking notes
- Made a recording, but no time to listen back
- Worried about uploading audio to cloud services
- Spending over an hour writing meeting notes every time

**Recmo solves all of that.**

---

## What Recmo Can Do

### Record Any Audio Playing on Your Mac

Not just web meetings. If audio plays on your Mac, Recmo can record, transcribe, and summarize it.

| Example | Use Case |
|---------|----------|
| Zoom / Google Meet / Teams | Meeting minutes |
| FaceTime / LINE / Discord | Call recordings |
| YouTube / Video courses | Summarize video content |
| Podcasts / Audio content | Never miss key points |
| Language learning materials | Transcription for study support |

**No virtual audio devices like BlackHole required.**

---

### One-Tap Workflow

Just press record. Recmo handles the rest.

```
Start Recording -> Auto Transcription -> Auto Summary
```

Set up global hotkeys to start/stop recording without opening the app. No need to interrupt your conversation.

**It's that simple:**
1. Click the menu bar icon (or press your hotkey)
2. Start recording
3. Stop when done

---

### Meeting Notes That Power Your Summary

Take notes during recording. These notes are used as reference when AI generates the summary.

**Use it like this:**
- Jot down keywords when something feels important
- Write your agenda beforehand -> Get an organized summary by topic
- Mark items with "decision", "TODO", "@John" -> Prioritized extraction

Open notes with a hotkey. Just drop keywords while listening. That's all it takes for a more accurate summary.

---

### Fully Local Transcription

Your audio never leaves your Mac. High-accuracy transcription powered by whisper.cpp runs entirely on your device.

- Safe for confidential meetings
- Works offline
- Fast processing (fraction of real-time with Core ML)

**Only the summarization feature sends transcription text to the OpenAI API (audio data is never sent).**

---

### Re-transcribe & Re-summarize Anytime

Want to try a different Whisper model? Changed your summary prompt? No problem. Re-process anytime from your recording history.

**As long as you have the audio, you can redo it as many times as you want.**

---

## How It Works

```
+-----------------------------------------------------------+
|                      Your Mac                              |
|  +--------------+    +----------------+                    |
|  |  Recording   | -> | Transcription  |                    |
|  | System Audio |    |  Whisper.cpp   |                    |
|  |   + Mic      |    |   (Core ML)    |                    |
|  +--------------+    +-------+--------+                    |
|       Local                Local                           |
+------------------------------|-----------------------------+
                               |
                               v
                    +--------------+
                    |   Summary    |
                    |  OpenAI API  |
                    | (text only)  |
                    +--------------+
                        Remote
```

---

## Auto-Summary for Clear Action Items

When recording ends, AI automatically generates a summary. What was decided. Who does what. Crystal clear.

```markdown
## Summary
Final confirmation meeting for the new feature release. Discussed design, testing, and schedule.

## Decisions
- New feature launches next Monday
- Design finalized with current proposal

## To-Do (with assignees)
- [ ] Final design review (Owner: Tanaka)
- [ ] Prepare test environment (Owner: Sato)

## Concerns
- Server load testing incomplete

## Notes
- Next meeting: Friday 3pm
```

---

## Sync with Obsidian & Your Favorite Note Apps

Set your output folders freely. Point to your Obsidian vault or any folder you prefer. Transcripts and summaries are saved automatically.

```
Example:
Audio: ~/Documents/Recmo/audio/
Transcripts: ~/Obsidian/Meeting Notes/
Summaries: ~/Obsidian/Meeting Notes/
```

**Outputs in Markdown, ready to use as-is.**

---

## Requirements

| Item | Requirement |
|------|-------------|
| OS | macOS 13 Ventura or later |
| Supported Apps | Any app that plays audio on your Mac |
| Permissions | Screen Recording, Microphone |
| Languages | Japanese, English |

---

## Pricing

### Free

- Recording limit: Up to 5 minutes per session
- Recording history: Up to 5 items saved
- All basic features available

### Pro - $4.99/month

- Recording limit: Up to 4 hours per session
- Recording history: Unlimited
- All features unlimited

To cancel or change your subscription, use the App Store

---

## FAQ

**Q. Where is my recording data stored?**

A. Everything is stored locally on your Mac. No cloud uploads, ever.

**Q. What data is sent when using summarization?**

A. When using the summarization feature, only the transcription text is sent to the OpenAI API. Audio data, filenames, and metadata are never sent.

**Q. How accurate is the transcription?**

A. We use OpenAI's Whisper model, which provides high accuracy for both English and Japanese. You can adjust model size in settings to balance accuracy and speed.

**Q. Do I need an API key for summarization?**

A. Yes, only the summarization feature requires an OpenAI API key. Transcription runs entirely locally and works without any API key.

**Q. Which apps are supported?**

A. Any app on your Mac that plays audio. Zoom, Google Meet, Teams, FaceTime, LINE, Discord, YouTube, and more.

**Q. Will my recordings be deleted if I uninstall the app?**

A. No. Your recordings, transcripts, and summaries are saved in folders you specify, so they remain even after uninstalling the app.

---

## Simplify Your Meetings with Recmo.

Focus on the conversation. Let Recmo handle the rest.

[Download on the App Store](https://apps.apple.com/app/id6756238386)

---

(c) 2025 Recmo. All rights reserved.

*Record + Memo = Recmo*
