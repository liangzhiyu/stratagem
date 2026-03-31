# stratagem

A strategy-analysis AgentSkill for messy human situations: negotiation, competition, positioning, conflict management, power asymmetry, and tactical decision-making.

This skill blends several classic strategy traditions into a single practical framework:
- **Sun Tzu / 孙子兵法**
- **Thirty-Six Stratagems / 三十六计**
- **The Prince / 君主论**
- **Selected Mao-era strategic thinking / 毛选**

The goal is not to flood the user with generic advice.
The goal is to identify **the main contradiction**, choose **one primary stratagem**, and explain **how to execute it**.

## What this skill does

When triggered, `stratagem` helps analyze situations such as:
- negotiation deadlocks
- office politics
- competitive positioning
- signaling and reputation management
- alliance building
- pressure and counter-pressure
- conflict de-escalation or indirect advantage
- turning weakness into leverage

## Output style

This skill is designed to respond with a compact structure:

1. **局势判断** — what is actually happening
2. **核心矛盾** — the main contradiction
3. **主计** — the single best stratagem
4. **为什么是这一计** — why it fits
5. **怎么落地** — concrete next move
6. **风险提醒** — downside / likely counter-move

## References bundled

The skill includes these reference texts under `references/`:
- `孙子兵法.md`
- `36计.md`
- `君主论.md`
- `毛选.md`

They are used selectively depending on the situation.

## Safety boundary

This skill is intended for:
- ordinary negotiation
- competition
- positioning
- strategic judgment
- conflict management

It is **not** intended for:
- violent wrongdoing
- abuse or coercion
- stalking or harassment
- fraud or criminal evasion
- exploitative manipulation of vulnerable people

## Installation

Place this folder under a skills directory, for example:

```bash
skills/stratagem/
```

The required entrypoint is:

```bash
skills/stratagem/SKILL.md
```

## Example prompts

- “帮我分析一下这个局面”
- “这件事用孙子兵法怎么解”
- “36计里哪一计最合适”
- “对方在打什么算盘”
- “给我一个最狠但最稳的策略”
- “这件事的破局点在哪”

## Philosophy

This skill assumes that the best strategy is usually not the loudest move, but the move that:
- sees the board clearly
- acts on the real leverage point
- preserves optionality
- minimizes unnecessary frontal conflict
