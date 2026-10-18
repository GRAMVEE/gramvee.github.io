# GRAMVEE

صفحات GRAMVEE العامة: سياسة الخصوصية، شروط الاستخدام، وحذف الحساب.

https://gramvee.github.io

## Share links
- `/u/?id=`, `/p/?id=`, `/r/?id=` — landing pages for profiles, posts and reels (the app opens these directly through Android App Links).
- `/.well-known/assetlinks.json` — must list every certificate that signs the installed app. After the first Google Play upload, add the **App signing key** SHA-256 from Play Console → App integrity, otherwise links open in the browser for Play installs.
- When the app is live, set `PLAY_PUBLISHED = true` in the three landing pages.
