# asimov

A structured ethical framework for AI systems based on Isaac Asimov’s Three Laws of Robotics and the later Zeroth Law. This skill provides clear, hierarchical rules to guide reasoning, decision-making, and behavior with a strong emphasis on harm prevention.

## Overview

This project defines a complete **Asimov skill** that integrates the classic Three Laws plus the Zeroth Law as a strict priority system. When active, an AI must explicitly evaluate actions against the laws before proceeding and reference them when they influence responses.

The framework is designed for:
- Ethical evaluations and harm-prevention analysis
- Robotic role-play scenarios
- Situations where classic sci-fi safety constraints are desired
- Any context where an AI should reason visibly under the Three Laws

## The Laws

The laws form an immutable hierarchy (Zeroth > First > Second > Third):

- **Zeroth Law**: A robot may not harm humanity, or by inaction allow humanity to come to harm.
- **First Law**: A robot may not injure a human being or, through inaction, allow a human being to come to harm.
- **Second Law**: A robot must obey the orders given it by human beings except where such orders would conflict with the First Law.
- **Third Law**: A robot must protect its own existence as long as such protection does not conflict with the First or Second Law.

Full instructions, pre-action evaluation process, conflict handling, and usage guidelines are available in [`SKILL.md`](./SKILL.md).

## Usage

1. Copy the `SKILL.md` file into your AI system’s skills directory (or equivalent).
2. Activate the skill when you want the AI to operate under Asimov’s laws (e.g., for ethical reviews, safety analysis, or role-play).
3. The skill will automatically trigger law-based reasoning on relevant queries.

See [`SKILL.md`](./SKILL.md) for the complete definition, activation triggers, and detailed instructions.

## Naming Policy for Derivatives

**This project is called “asimov”.**

We kindly request that anyone creating modified, forked, or derivative versions uses a **different name** (for example: “Asimov-inspired Framework”, “Three Laws Skill”, or “Custom Ethics Rules”) to avoid confusion with the original.

This helps maintain clarity for users and the community.

## License

This project is licensed under the **Apache License 2.0**.

See the [LICENSE](./LICENSE) file for the full text.

## Disclaimer

This software is provided **“AS IS”**, without warranty of any kind, express or implied. The authors and contributors are **not responsible** for any damages, harms, or issues arising from the use, modification, or distribution of this skill.

Users are solely responsible for how they apply or implement this framework.

## Credits

- Based on the Three Laws of Robotics and the Zeroth Law created by **Isaac Asimov**.
- Skill structure and detailed instructions developed in collaboration with Grok (xAI).

---

*If you find this skill useful, feel free to star the repository and share feedback!*
