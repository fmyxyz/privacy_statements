## Privacy Policy

**Last updated:** 2026-09-13
**Effective date:** 2026-09-13

Welcome to MetronomePro (the "App"). We take your privacy seriously. This policy
explains what happens to your information when you use the App.

### 1. Information we collect

**The App does not collect any personal information.**

The App requires no network permission, connects to no network service, and
integrates no third-party SDK, no advertising SDK, and no account login. Using
the App does not produce any transmission of personal identity, device,
location, or behavioural information.

### 2. Permissions used and their purpose

| Permission | Purpose |
|------------|---------|
| `ohos.permission.KEEP_BACKGROUND_RUNNING` | Declares a background mode so the metronome keeps playing audio when the app moves to the background (e.g. locked screen or app switch), keeping practice uninterrupted. |

This permission only supports uninterrupted background audio playback. It does
not access your contacts, photos, location, microphone, camera, or personal data.

### 3. Data storage and processing

All data produced by the App is stored locally on your device:

1. **Practice records and progress** are stored in a private on-device database
   (`metronome.db`): practice sessions (time, duration, BPM, time signature,
   hit/early/late/miss/extra counts, and the pattern or level practiced) and
   level progress.
2. **Preferences** are stored in the system preference store
   (`metronome_prefs`), e.g. your BPM and time-signature settings.
3. **Custom scores** you create are saved as JSON files under the app's
   dedicated `scores/` directory, which the *system cloud file service* of your
   Huawei device syncs across devices signed in with the same Huawei account.
   This sync is performed by the system capability itself; the App never
   transmits or collects your data.

All of the above is produced actively by you and used solely to run App
features. The App transmits nothing to any server and does not share data with
other developers or third parties.

### 4. Sharing, transfer and disclosure

The App does **not** share, transfer, or publicly disclose any of your personal
information or personal data.

### 5. Retention

All local data is removed by the system when you uninstall the App. You can also
clear practice history in the "History" tab or manage app data in system
settings at any time.

### 6. Children's privacy

The App collects no personal information and involves no processing of
children's data. If you are a minor, please use the App under a guardian's
guidance.

### 7. Changes to this policy

We may update this policy from time to time. Revised versions will be published
on this page and marked with a new update date.

### 8. Contact us

Questions, comments or requests regarding this policy may be sent to the contact
email shown on the developer profile page of the app store (filled in at
submission time).
