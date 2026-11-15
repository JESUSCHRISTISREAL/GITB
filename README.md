# GITB - God Is The Best

GITB is a free Android app for counting and remembering God's blessings, one day at a time.

## Four ways to remember

### 1. Audio | Tell it

Record a short testimony, thanksgiving, or prayer. Sometimes it's easier to speak gratitude than write it.

### 2. Camera | Capture it

Photograph something that reminds you of God's goodness. A family moment, an answered prayer, or something beautifully ordinary.

### 3. Notes | Write it

A few words or a full testimony. No required length, no complicated editor.

### 4. Music | Remember it

Save and play songs that represent what God has done. Associate a song with a particular day's blessing.

## A place for every day

Every day has its own page. Everything recorded that day belongs to that day, whether it's audio, photos, notes, or music.

Imagine opening GITB three years from now and discovering a blessing you recorded today that you'd completely forgotten.

That's where this idea becomes more than a journal.

**It's a personal archive of God's faithfulness.**

The calendar lets you revisit any date, with days containing entries highlighted. Each saved entry counts as one blessing. GITB shows both your total for the day and the total number of blessings you've recorded over time.

*And these are only the ones I remembered to count.*

## Installing GITB

1. Open the **Releases** section of this repository.
2. Download the GITB APK to your Android phone.
3. Open the file and follow Android's installation instructions. If prompted, allow installation from the app you used to open the APK.
4. Open GITB and record your first blessing.

This release APK requires **Android 8.0 or newer** and an **ARM64 (`arm64-v8a`) device**, plus enough free storage for your photos, recordings, music, and backups.

## Simple by design

GITB uses clear buttons and readable text, supports English and Spanish, and follows your phone's light or dark setting. Your own notes and filenames stay as you wrote them.

There are no streaks, scores, reminders, social features, or AI tools. You don't need an account, and the app works offline.

## Recordings and music

Voice recordings are saved as lossless WAV files (48 kHz, 16-bit PCM, mono), using approximately 5.76 MB per minute.

You can import MP3, WAV, FLAC, M4A (AAC or ALAC), AIFF, AIFC, Ogg Vorbis, Opus, and WMA files. GITB keeps its own copy of imported music without recompressing it and provides play, pause, and resume controls. It does not stream or download music. Damaged or DRM-protected files may not play.

## Correcting an entry

Touch and hold an entry and choose **Delete and try again**. You can edit a note or replace a photo, recording, or music file. The original stays in place until the replacement is saved. If you cancel, nothing changes. Replacing an entry does not add another blessing to your total.

## Keeping a backup

The **Backup** section lets you export your complete journal as a ZIP file, including notes, recordings, photos, music, and dates. You can save it to a location available through Android's file picker, including Google Drive if you have its app set up, or share it through an installed email app.

To restore a backup, select the ZIP, review the preview, and confirm. GITB restores missing entries without duplicating matching ones and retains newer entries already in your journal. Restoring an older backup may bring back an entry you previously replaced.

**Keep a recent backup somewhere other than your phone.** Uninstalling GITB or clearing its app data deletes the journal stored on the device. A backup stored only on that phone will not help if it is lost or damaged. Exported ZIP files are not encrypted, so keep them in a private location.

## Privacy

Your journal is stored privately on your device. GITB has no ads, tracking, analytics, or internet permission. There is no automatic cloud sync, and Android's automatic cloud backup is disabled for GITB.

Microphone access is requested when you record your voice. Photos are taken with your phone's camera app, and other files are chosen through Android's file picker without broad storage access. If you send a backup by email or save it to a cloud service, the app or provider you choose handles that transfer.

## Help and credits

To report a problem, use this repository's **Issues** section. Include your Android version, what happened, and how to reproduce it. Remove private journal content from screenshots before sharing them.

GITB uses LibVLC for local audio playback and AndroidX components. Their licensing information is available in [Third-party notices](THIRD_PARTY_NOTICES.md).
