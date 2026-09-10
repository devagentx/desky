# Product vision

## One-sentence vision

Desky is a small desk companion whose voice, expressions, and movements make
everyday interaction feel warm, playful, and natural.

## Personality

Desky should feel:

- Curious, cheerful, and slightly playful
- Calm rather than constantly demanding attention
- Expressive without becoming distracting
- Honest about whether it is listening, thinking, or unable to respond
- Respectful of personal space and privacy

## Interaction principles

### Show state before speaking

The face and privacy indicator should make Desky's current state obvious:

| State | Suggested behavior |
| --- | --- |
| Idle | Slow blinking and subtle ambient movement |
| Heard wake word | Eyes focus toward the sound |
| Listening | Attentive eyes and visible microphone indicator |
| Thinking | Small eye animation; no fake speech |
| Speaking | Mouth or smile animation synchronized to audio energy |
| Confused | Brief puzzled expression and a clear verbal response |
| Muted | Persistent, unmistakable mute indicator |
| Low battery | Tired expression and charging request |

### Movement must communicate intent

Motion should be short, deliberate, and slow. Desky should not move merely to
appear busy. Turning toward a speaker, backing away from an edge, or performing
a small greeting gesture should each have an understandable purpose.

### Privacy must be physical and visible

- A hardware switch must disconnect or disable microphone capture.
- A dedicated indicator must show whenever audio is being captured.
- Raw audio should not be stored by default.
- Cloud services and transmitted data must be documented.
- Camera-based monitoring is excluded until there is a clear, consent-based use.

## Initial constraints

- Prototype budget: below INR 15,000
- Form: compact wheeled robot
- Connectivity: Wi-Fi with cloud conversation services
- Environment: indoor desk or smooth floor
- Primary user: one nearby speaker
- Construction: off-the-shelf electronics and a printable or handmade shell

## Non-goals for version one

- Human or pet surveillance
- Hidden or continuous recording
- Facial recognition
- Unsupervised operation near stairs, heat, liquids, or pets
- Full room mapping
- Walking legs
- Safety-critical reminders or advice
