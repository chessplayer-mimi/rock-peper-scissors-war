# rock-paper-scissors-war

There are a total of thirty items: ten scissors, ten rocks, and ten papers. When scissors collide with rocks, they will turn into rocks, and so on. However, it's not that simple. A black hole has appeared!!! It can appear anywhere at any time, and any item that touches the black hole will randomly transform into one of the three types. The last thirty unified items in the world will become the ruler! Will you take the bet?

## Setup Instructions

### Firebase Configuration

To protect sensitive information, Firebase configuration has been moved to an external file. Please follow these steps to set up:

1. Copy the template file:
   ```bash
   cp firebase-config.template.js firebase-config.js
   ```

2. Edit the `firebase-config.js` file and fill in your Firebase project credentials:
   - apiKey
   - authDomain
   - databaseURL
   - projectId
   - storageBucket
   - messagingSenderId
   - appId
   - measurementId

3. The `firebase-config.js` file is already added to `.gitignore` and will not be committed to version control.

### Running the Game

Simply open `index.html` in your browser to start playing.

## Security Notes

- Do NOT commit the `firebase-config.js` file to public repositories
- Make sure to set up appropriate security rules in your Firebase Console
- Regularly review and rotate API keys

## File Structure

- `index.html` - Main game file
- `20240806.html` - Legacy version game file
- `firebase-config.js` - Firebase configuration (excluded from git)
- `firebase-config.template.js` - Firebase configuration template
