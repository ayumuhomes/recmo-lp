# Privacy Policy

Last Updated: December 2025

This Privacy Policy explains how Recmo ("the App") handles your information.

---

## 1. Information We Collect

### Information Processed by the App

The App processes the following information **only on your device**:

- **Audio Data**: Audio played on your Mac (web meetings, calls, videos, etc.) and microphone input
- **Transcription Data**: Text generated from audio
- **Summary Data**: Summary text generated from transcriptions
- **Memo Data**: Notes entered by the user during recording
- **Settings**: App preferences (output folders, Whisper model selection, etc.)

### Information We Do Not Collect

- Personally identifiable information (name, email, etc.)
- Location data
- Device identifiers
- Usage analytics

---

## 2. Data Storage

### Local Storage

All audio data, transcription data, and summary data are stored **only on your Mac**. Default storage locations are:

- Audio files: `~/Documents/Recmo/audio/`
- Transcripts: `~/Documents/Recmo/transcripts/`
- Summaries: `~/Documents/Recmo/summaries/`

You can change these locations in the app settings.

### Cloud Transmission

The App **does not transmit audio recordings (audio files) to any cloud servers**. Recording and transcription are processed entirely on your Mac.

However, **when using the summarization feature, transcription text is sent to the OpenAI API**. See "Third-Party Services" below for details.

---

## 3. Third-Party Services

### OpenAI API (Summarization Feature)

When using the summarization feature, **transcription text is sent to the OpenAI API**. This is required to generate summaries.

- **Data sent**: Transcription text and memos (used for summary generation)
- **Data not sent**: Audio files, filenames, or any other personal information
- **API key management**: You use your own OpenAI API key
- **When data is sent**: When a recording is completed with summarization enabled, or when you manually trigger re-summarization

For OpenAI's privacy practices, please refer to [OpenAI's Privacy Policy](https://openai.com/privacy/).

**Important**: The summarization feature is optional. If you do not set up an API key, no transcription text will be sent to the cloud. Recording and transcription work fully offline.

---

## 4. Required Permissions

The App requires the following system permissions:

| Permission | Purpose |
|------------|---------|
| Screen Recording | Required to capture system audio (meeting app audio) |
| Microphone | Required to capture microphone audio (your voice) |
| Notifications | Required to notify you of recording/processing completion (optional) |

Data obtained through these permissions is used solely to provide the App's functionality and is not transmitted externally (except for the summarization feature).

---

## 5. Data Deletion

### Deleting Recording Data

You can delete individual recordings from the recording history. Deleted data is permanently removed and cannot be recovered.

### Uninstalling the App

Uninstalling the app does not delete your saved data (audio, transcripts, summary files). To completely remove all data, manually delete the files from your storage folders.

---

## 6. Third-Party Sharing

The App does not sell, rent, or share your personal information with third parties.

---

## 7. Security

The App implements the following security measures:

- All data is stored locally and managed on your encrypted file system
- Communication with the OpenAI API is encrypted via HTTPS
- The app runs in a sandboxed environment with restricted access to only permitted folders

---

## 8. Children's Privacy

The App is not intended for children under 13. We do not knowingly collect personal information from children under 13.

---

## 9. Changes to This Policy

This Privacy Policy may be updated without prior notice. When changes are made, we will update this page and modify the "Last Updated" date.

---

## 10. Contact Us

If you have questions about this Privacy Policy, please contact us at:

- Email: [Contact Email Address]

---

© 2025 Recmo. All rights reserved.
