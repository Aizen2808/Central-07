Central 26 — connected prototype

This version connects the Central 26 front-end to the Supabase backend.
It supports anonymous sign-in, room creation/joining, shared syllabus subjects/topics,
shared YouTube videos, realtime chat, and realtime member list.

The syllabus PDF is intentionally not connected to shared storage yet; that is the next backend step.

Supabase project URL is embedded in index.html and the browser-safe publishable key is used.
Never put a Supabase secret/service-role key in this file.


Fixed in this build: createRoom() now declares roomId correctly.
For testing, deploy the folder to GitHub Pages (or another HTTPS host) rather than opening index.html directly with file://.
