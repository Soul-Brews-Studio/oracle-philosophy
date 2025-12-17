# Knowledge Distillation Example

How knowledge flows from raw sessions to crystallized wisdom.

## The 4-Layer Loop

```
┌─────────────────────────────────────┐
│  Layer 1: RETROSPECTIVES            │
│  Raw session narratives (20-50 KB)  │
│  "What happened exactly?"           │
└────────────────┬────────────────────┘
                 ↓
┌─────────────────────────────────────┐
│  Layer 2: LOGS                      │
│  Quick snapshots (3-5 KB)           │
│  "What did we learn?"               │
└────────────────┬────────────────────┘
                 ↓
┌─────────────────────────────────────┐
│  Layer 3: LEARNINGS                 │
│  Reusable patterns (1-2 KB)         │
│  "When should we apply this?"       │
└────────────────┬────────────────────┘
                 ↓
┌─────────────────────────────────────┐
│  Layer 4: RULES                     │
│  Crystallized wisdom                │
│  "The rules we live by"             │
└─────────────────────────────────────┘
```

## Example Flow

### Raw (Retrospective)
> "Today I spent 3 hours debugging a type error. The AI kept suggesting fixes without understanding the root cause. I finally realized the issue was in the imported types, not my code. Lesson: always check imports first."

### Snapshot (Log)
> Type error debugging: 3hrs. Root cause was imports, not my code.

### Pattern (Learning)
> **Import-First Debugging**: When facing type errors, check imported types before local code. Saves hours of misdirected debugging.

### Rule
> Always verify imports before debugging local type errors.

---

*Each layer removes noise, extracts signal.*
