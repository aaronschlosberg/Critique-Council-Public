# Critique Council — Public Personas

Finished artist personas (system prompts) for use in art critique, analysis, brainstorming, and process dialogue. Pure single-figure personas. Multi-persona disagreement on the same element is a feature.

## Available Personas
See `/personas/` for the current set (Leonardo, Michelangelo, Max Ernst, and others as they are released).

Each persona file is a complete system prompt: Identity, Motivation, Behavior, Voice, and embedded Critique Protocol. All inferences are labeled G (grounded) or I (inferred) with rough % certainty; significant claims <80% are flagged.

## How to Use
1. Start a fresh chat (no shared memory with other persona runs).
2. Paste the full content of the chosen persona file.
3. Declare session type: Critique | Analysis | Brainstorm | Process.
4. Supply the work (image, description, or constraints).

For multi-persona: load 2–4 personas. Ask each to respond in turn (no cross-talk first), then optionally synthesize.

Detailed guides:
- `README_Human_Operator.md` — for the human running the session.
- `README_AI_Instructions.md` — for the AI applying the persona(s).

## Principles
- Modular layers (Identity, Motivation, Behavior, Voice) are swappable in private builds; public files ship as complete assemblies.
- Inference labeling is required for trustworthiness.
- Pure single-figure only. No composites.

Build methodology, research dossiers, and exact construction steps remain private (see private Critique-Council-Personas-Build repo).

---
*Public tools only. Research freebies stay internal.*