# Parallel Input Channels

> Give the brain two ways in at the same time.

## Cognitive Mechanism

Dual-coding theory (Paivio, 1971) demonstrates that information processed through two modalities simultaneously produces stronger encoding than either modality alone. For dyslexic readers, the visual channel alone is unreliable: letters swap, lines merge, position is lost. Adding a synchronized auditory channel creates redundancy. If one channel drops, the other carries. The reader does not need perfect decoding from either source because both sources reinforce each other in real time.

## The Pattern

Present the same content through two synchronized modalities: visual text and audio narration. Synchronization must be tight, at the word or phrase level, not the paragraph level. The visual channel highlights the current position in the text while the audio channel reads it aloud.

The user does not choose between reading and listening. They do both. The highlighting acts as a visual anchor that prevents the eye from drifting, while the audio provides the phonological stream that the visual system may be struggling to produce on its own.

Key requirements:
- Word-level or phrase-level synchronization (not sentence or paragraph)
- Visual highlighting tracks the audio position in real time
- Audio uses human-quality TTS voices (robotic voices break the immersion and add processing overhead)
- The user controls playback speed, not just on/off

## Evidence

- **EverbloomReader**: Synchronizes word-by-word text highlighting with high-quality TTS narration. As the voice reads, each word highlights in sequence. The reader follows both streams simultaneously. OpenDyslexic font support reduces visual decoding effort on the text side. The combination means a dyslexic reader can follow a novel at full speed without losing their place.

## COGA Mapping

- **Objective 3: Use clear and understandable content** -- Dual-channel presentation makes content more understandable for users who struggle with text-only formats.
- **Objective 5: Help users focus** -- The synchronized highlight acts as an external attention anchor, reducing the effort required to maintain reading position.
- **Objective 6: Minimize the user's cognitive load** -- Position tracking is offloaded to the highlight. Phonological decoding is offloaded to TTS. The reader's job is comprehension, not mechanics.

## Not This

- **Screen readers** -- Screen readers provide a single auditory channel for users who cannot see the screen. Parallel input channels assume the user can see the screen and provide both channels simultaneously for reinforcement.
- **Audiobooks** -- Audiobooks are audio-only. There is no visual text to follow. Parallel input channels require both streams, synchronized.
- **Karaoke-style lyrics** -- Visually similar, but karaoke highlights for entertainment. Parallel input channels highlight for cognitive support. The design goal is comprehension, not performance.
