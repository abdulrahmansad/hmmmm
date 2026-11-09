# HMMMM — For Arshi

An interactive, mobile-first birthday surprise created for 22 November 2026.

## Open the experience

Open `index.html` locally, or deploy it with GitHub Pages.

**GitHub Pages:** Settings → Pages → Build and deployment → Source: **GitHub Actions**. The supplied workflow publishes the static website after updates to `main`. Once enabled, the expected public URL is `https://abdulrahmansad.github.io/hmmmm/`.

## Story

1. Marah Jamela? — literary opening
2. A birthday wish and dua
3. A teasing fight-choice interaction; **both answers progress**
4. Muuh banaliya — auto-advances after about 3 seconds
5. A secret confession
6. Turkish poetry at the Bosphorus, with optional translation
7. Driving-school teasing
8. Luxury YSL gift joke
9. Biryani punchline
10. A song-player finale

## Personal photo and song assets

This repository is **public**. **Never commit Arshi's or your personal photos, identifiable recordings, or voice-clone training data without explicit permission.** The initial implementation intentionally uses CSS art rather than likeness-changing AI images. Original identity-preserving photos can be introduced later using private hosting, or by making the repository and deployment appropriately private; note that GitHub Pages sites can still be public even for a private repo depending on plan/settings.

For the finale, provide an audio file at `assets/arshi-song.mp3` **only once privacy and consent are resolved**. The player currently displays a friendly missing-audio message instead of pretending a song exists.

## Technology

Single-file static site, no build step. Responsive CSS, accessible focus states, optional UI tones, reduced-motion support, touch-friendly controls.

## Notes

The user's conversational copy is preserved without generic romantic rewriting. The Turkish line is used as an unattributed expression. This is a preview, not a deployed site until Pages is enabled.
## Optional background soundtrack

The site is wired for a quiet looping background soundtrack at `assets/kendine-iyi-bak.mp3` (about 8.5% player volume). Browsers require a user tap or key interaction before playback starts. The audio stops when the final personal song begins. The sound button toggles effects and background music together.

**The copyrighted Ahmet Kaya track is NOT included.** Only add this audio if you have the necessary rights or license to publish it on a public GitHub Pages site. Without the file, the site continues silently. Do not assume owning a streaming subscription grants permission to redistribute an MP3.
