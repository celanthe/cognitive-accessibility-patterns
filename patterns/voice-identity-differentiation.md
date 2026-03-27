# Voice Identity Differentiation

> When every agent sounds the same, the brain stops distinguishing between them.

## Cognitive Mechanism

Auditory selective attention relies on voice characteristics -- pitch, timbre, cadence, accent -- to differentiate speakers and assign relevance. This is the cocktail party effect (Cherry, 1953): the brain filters multiple auditory streams by locking onto distinct voice signatures. When AI agents all use the same default TTS voice, the brain cannot form separate speaker identities. Each agent's output blurs into a single undifferentiated stream. For users with ADHD or auditory processing differences, this collapse is worse: attentional filtering is already impaired, and identical voices eliminate the primary cue the brain uses to keep sources separate.

Distinct voice identities give the brain something to grab onto. When Agent A sounds different from Agent B, the user can track who said what without reading metadata or checking labels. The voice becomes the identity.

## The Pattern

Assign each AI agent a distinct, persistent voice. Voice selection is not cosmetic. It is an attentional affordance. Each agent's voice should differ along at least two dimensions (pitch, speed, accent, warmth) so the brain can rapidly distinguish between them.

Key requirements:
- Each agent gets a unique voice configuration that persists across sessions
- Voice differences are perceptible, not subtle -- the user should never have to guess which agent is speaking
- Voice assignments are configurable by the operator, not hardcoded to a vendor
- Multiple TTS backends are supported so voice selection is not constrained by a single provider's catalog
- No vendor lock-in -- if a backend goes down or a subscription lapses, the agent's voice can be remapped to another provider

## Evidence

- **Clarion**: Self-hosted TTS proxy that routes agent speech through multiple backends (ElevenLabs, OpenAI, Google, local models). Each agent is configured with a distinct voice profile: voice ID, speed, pitch adjustments, and backend preference. When an agent speaks, Clarion resolves the voice configuration and returns audio. The operator controls the voice-to-agent mapping without touching agent code. Agents never share a default voice unless the operator explicitly configures them to.

## COGA Mapping

- **Objective 5: Help users focus** -- Distinct voice identities provide an auditory attention anchor. The user can track which agent is communicating without visual context switching.
- **Objective 6: Minimize the user's cognitive load** -- Speaker identification is offloaded from conscious effort (reading labels, checking metadata) to automatic auditory processing (recognizing a familiar voice).
- **Objective 3: Use clear and understandable content** -- Agent communication is clearer when the user can immediately identify the source by voice rather than parsing text headers or UI chrome.

## Not This

- **Text-to-speech quality** -- This pattern is not about making TTS sound more human. It is about making multiple agents sound different from each other. A system with one excellent voice still fails this pattern if all agents use it.
- **Voice assistants** -- Consumer voice assistants (Siri, Alexa) have one voice per device. This pattern addresses multi-agent environments where several AI agents communicate with the same user.
- **Audio branding** -- Brand voice guidelines assign a single voice identity to a company. This pattern assigns separate identities to separate agents within the same system.
- **Accessibility narration** -- Screen readers and accessibility narration provide a single voice for all content. This pattern provides multiple voices to differentiate sources.
