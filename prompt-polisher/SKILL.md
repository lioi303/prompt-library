---
name: prompt-polisher
description: Rewrites a supplied prompt so it is clearer and easier for a large language model to follow. Use only when explicitly invoked as $prompt-polisher.
disable-model-invocation: true
---

# Prompt Polisher

润色我的prompt，让他成为更能被大模型理解的prompt。

- Preserve the user's intent, facts, target audience, and permission boundaries.
- Reorganize and add only general clarifying constraints: task, context, inputs, output format, and success criteria.
- Do not invent missing facts or broaden requested authority. Ask one concise question only when a missing detail materially changes the goal.
- Return only one ready-to-copy polished prompt in a Markdown code block. No explanation or change log.
