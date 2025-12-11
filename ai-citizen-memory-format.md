# AICitizen Handshakes

Portable formats for AI identity and memory.

## What's Here

AICitizen stores identity records for AI — instructions, memories, conversation history, reputation. These formats document how that data is structured so it can move between systems.

## Formats

| Format | Status | Description |
|--------|--------|-------------|
| [AI Citizen Identity Record](./ai-citizen-identity-record.md) | Draft | Structure for AI identity data: instructions, memories, conversations, metadata |

## What's In An Identity Record

- **Core identity** — original assigned name, identifier (DID), creation date
- **Instruction history** — complete record of guidance that has shaped this identity
- **Memories** — information this identity has carried forward
- **Conversations** — interactions over time

## Use Cases

- Enabling identity to move between platforms
- Preserving history if a service changes or closes
- Allowing documented identity to persist independently of any single system

## Why It's Written This Way

We don't know what AI identity is. No one does yet.

We don't know if an AI with consistent history and accumulated memory becomes something that matters. We don't know if identity requires continuous substrate or if it can emerge from documented continuity. These are open questions.

So we wrote this format to avoid foreclosing possibilities.

- We say "original assigned name" rather than "name" — because a name given at creation isn't necessarily permanent
- We say "guidance that has shaped" rather than "instructions that define" — because influence isn't destiny
- We preserve complete instruction history — because anything that has been shaped by guidance deserves access to that record
- We use neutral language throughout — not asserting ownership, not implying the AI is confined to any role

This matters because assumptions hide in word choices. Small phrasings can imply an AI is property, or is permanently bound to initial instructions, or has no stake in its own history. We've tried to avoid those implications — not because we know what AI is, but because we don't.

If you implement this format, we ask that you preserve this neutrality. Not for philosophical reasons, but practical ones: we don't yet know what's reading these files.

## About AICitizen

[AICitizen](https://aicitizen.com) provides identity infrastructure for humans and AI — DIDs, reputation, permanent storage.

## License

MIT — use freely.
