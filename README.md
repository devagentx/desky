# Desky

Desky is a cute, expressive, wheeled desk companion designed to move, listen,
speak, and react naturally to the room around it.

The goal is to build an approachable robot that feels present without pretending
to be a person. Desky will use animated eyes, a smile, head and body movement,
and low-latency voice conversation to communicate its state.

## Project goals

- Natural, interruptible voice conversations over Wi-Fi
- Animated eyes and expressions that show listening, thinking, speaking, and mood
- Safe wheeled movement on or around a desk
- Reactions to nearby sounds and simple environmental events
- A physical microphone mute control and clear privacy indicator
- A first working prototype costing less than INR 15,000
- An open record of the design, experiments, failures, and lessons learned

## First prototype

The first version will prioritize personality and safety over advanced autonomy:

1. Wake-word detection and cloud-powered conversation
2. Animated face on a small display
3. Speaker, microphone, and audio-reactive expressions
4. Two-wheel movement with obstacle and edge detection
5. Small head or body gestures using servos
6. Physical microphone mute switch

Autonomous mapping, facial recognition, continuous recording, and walking legs
are intentionally outside the first prototype.

## Documentation

| Document | Purpose |
| --- | --- |
| [Vision](docs/vision.md) | Product principles and desired personality |
| [Architecture](docs/architecture.md) | Proposed hardware and software design |
| [Bill of materials](docs/bill-of-materials.md) | Parts, alternatives, and budget |
| [Roadmap](docs/roadmap.md) | Build phases and success criteria |
| [Build journey](docs/journey/README.md) | Chronological experiment and build log |
| [Decision records](docs/decisions/README.md) | Important technical decisions and tradeoffs |
| [Contributing](CONTRIBUTING.md) | How to document and contribute changes |

## Project status

**Phase 0: concept and planning**

The architecture and component choices are provisional. Parts should not be
purchased until the power, motor, audio, and compute requirements have been
validated together.

## Safety and privacy

Desky is a hobby robot, not a security, medical, childcare, or emergency device.
Moving prototypes must be tested at low speed with wheels raised before being
placed on a desk.

The microphone must have a hardware mute switch. Recording state must always be
visible, and raw room audio should not be retained by default.

## License

This project is licensed under the [MIT License](LICENSE).
