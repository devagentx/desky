# Contributing

Desky is currently an early personal robotics project. Contributions,
experiments, component comparisons, and safety improvements are welcome.

## Before proposing a change

- Read the project vision and current roadmap.
- Search existing journey entries and decision records.
- Keep the first prototype below the stated budget.
- Do not weaken movement, electrical, battery, or privacy protections.

## Documentation expectations

- Record measurements instead of relying only on impressions.
- Include exact component names and relevant configuration.
- Document failed experiments and limitations.
- Explain any cloud service, transmitted data, and retention behavior.
- Never commit API keys, Wi-Fi credentials, recordings, or personal data.

## Code expectations

When code is introduced, each change should include focused tests or a documented
hardware validation procedure. Safety logic must fail toward stopped motors and
must not depend solely on cloud connectivity.
