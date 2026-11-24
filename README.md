# LensLearn AI 📸

> Point your phone or camera at any rock, landscape, plant, architecture, or machine to learn what you see. Built for Pollinations AI Quest [#20023](https://github.com/pollinations/pollinations/issues/20023).

[![Made with pollinations.ai](https://raw.githubusercontent.com/pollinations/pollinations/main/packages/ui/src/brand/badge-made-with.svg)](https://pollinations.ai/?ref=badge)

**Live App:** [https://lekezoa.github.io/lens-learn-ai/](https://lekezoa.github.io/lens-learn-ai/)

---

## 🌟 Overview
Inspired by Outcrop, **LensLearn AI** turns any smartphone camera or desktop webcam into an interactive visual field guide. Pointing at a cliff reveals geological strata; pointing at a leaf identifies species and medicinal botany; pointing at ancient masonry breaks down architectural engineering.

## 🔑 Bring Your Own Pollen (`<polli-connect>`)
- Implements the official Pollinations `<polli-connect>` drop-in component.
- Authorizes spend directly from the visitor's Pollen balance.
- Completely client-side, zero backend server storage, 100% private.

## 🚀 Capabilities
- **Real-Time Camera & Upload:** Live camera viewfinder with target reticle + manual photo uploader.
- **Specialized Explorer Modes:**
  - 🪨 **Geology & Minerals:** Formations, epoch aging, petrology.
  - 🌿 **Botany & Ecology:** Plant species identification and habitat.
  - 🏛️ **Architecture & Heritage:** Building styles and engineering history.
  - ⚙️ **Machinery & Objects:** Mechanical components and function explanation.
- **Audio Narration:** Built-in speech feedback powered by Pollinations voice endpoints.

## 🤖 Models Used
- **Multimodal Visual Analysis:** `openai/gpt-5.4-nano` (free tier, `paid_only: false`, multimodal text + image analysis via `gen.pollinations.ai`).
- **Speech Audio Feedback:** `openai/tts-1` (`paid_only: false`, via `gen.pollinations.ai/v1/audio/speech`).

---
Built with ❤️ for [Pollinations.ai](https://pollinations.ai).
