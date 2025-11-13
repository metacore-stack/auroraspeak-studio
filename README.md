# AuroraSpeak Studio

AuroraSpeak Studio turns ChatGPT into an expressive voice companion that runs entirely in your browser. Practice pronunciation, rehearse presentations, or enjoy free-flowing dialogue without sharing transcripts with remote services.

## Overview
- Conversational workspace with synchronized text and audio playback
- In-browser speech recognition with optional cloud connectors
- Voice library spanning hundreds of languages and styles
- Local-first storage so sessions stay on your device
- Responsive interface that adapts to desktop, tablet, and mobile

![AuroraSpeak Studio interface preview](./assets/demo-en.png)

## Quick Start
1. **Install dependencies**
   ```bash
   yarn install
   ```
2. **Launch the development server**
   ```bash
   yarn dev
   ```
3. **Open the app** at `http://localhost:5173` and follow the in-app setup tour to choose speech recognition and synthesis providers.

## Production Build
- Generate an optimized bundle with `yarn build`
- Preview the static output locally via `yarn preview`
- Serve the `dist/` directory from any static hosting platform or container runtime

## Architecture Notes
- Frontend: React + TypeScript powered by Vite and Tailwind CSS
- State management: modular store with persistent history
- Audio pipeline: Web Speech API with pluggable adapters for external services
- Localization: i18n framework with bundled English, Spanish, and Simplified Chinese resources

## Project Status
- ✅ Core conversation, speech synthesis, and transcription flows
- ✅ Cross-platform layout and dark mode
- 🚧 Experimenting with custom voice tuning presets
- 🧭 Community roadmap captured in `CHANGELOG.md`

## Contributing
Pull requests and issue reports are welcome. Please review the guidelines in `docs/developer-guide.md` before opening a contribution.

## License
AuroraSpeak Studio is released under the MIT License. See `LICENSE` for details.
