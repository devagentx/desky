# Roadmap

## Phase 0: define and de-risk

- Confirm interaction principles and privacy requirements.
- Select the compute, audio, display, and motion components.
- Validate the power budget before purchasing batteries.
- Define measurable latency, audio, and movement targets.

**Exit criteria:** a reviewed parts list, power estimate, and experiment plan fit
within the INR 15,000 budget.

## Phase 1: expressive face

- Render eyes and a smile on the selected display.
- Implement idle, listening, thinking, speaking, happy, confused, and muted states.
- Drive speaking animation from audio amplitude.

**Exit criteria:** animations run smoothly for one hour without a crash.

## Phase 2: voice conversation

- Add microphone capture and speaker output.
- Implement local wake-word and voice-activity detection.
- Connect to a cloud conversational voice service.
- Support interruption while Desky is speaking.
- Measure end-of-speech to response-audio latency.

**Exit criteria:** ten consecutive conversations complete with clear state
indication and no stored raw audio.

## Phase 3: safe movement

- Assemble the two-wheel drive base.
- Add motor control, watchdog, obstacle sensing, and desk-edge detection.
- Implement a low-speed test mode.
- Separate safety commands from expressive motion.

**Exit criteria:** Desky stops safely on communication loss and passes repeated
edge and obstacle tests.

## Phase 4: personality integration

- Turn toward sound.
- Coordinate expressions, speech, and gestures.
- Add greetings, acknowledgements, and low-battery behavior.
- Tune motor and speaker noise interaction.

**Exit criteria:** a five-minute interaction feels coherent and all movement has
an observable trigger.

## Phase 5: enclosure and daily use

- Design a serviceable enclosure with accessible switches and charging.
- Perform thermal, battery-runtime, stability, and long-duration tests.
- Document assembly, setup, operation, and known limitations.

**Exit criteria:** a repeatable prototype build and a complete safety checklist.
