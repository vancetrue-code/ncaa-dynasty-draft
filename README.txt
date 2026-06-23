TRUE LIVE FROM SCRATCH

This is a new real-time architecture:
- Firebase is the source of truth.
- No localStorage syncing.
- No refresh required for updates.
- Player identity comes from URL.
- Players get a turn alert popup when it becomes their turn.

IMPORTANT:
Before deploying, replace firebaseConfig in index.html with your NEW Firebase web config.

Firebase rules for testing:
{
  "rules": {
    ".read": true,
    ".write": true
  }
}

Database path used:
game/state

Netlify:
Upload this folder/ZIP to a NEW Netlify site.
