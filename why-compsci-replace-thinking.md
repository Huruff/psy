Your friend may not be “insane” or incapable—they may be taking the fastest path that feels rewarding: ask AI, paste code, see it run, move on. But if they never test, read, or understand it, they are building a dangerous habit: **using AI as a replacement for thinking instead of as a tool for thinking.**

## Why it happens

AI gives an immediate, confident-looking answer. That creates a shortcut around the uncomfortable parts of programming: reading documentation, debugging, designing logic, and being wrong before becoming right.

Research on CS students finds that heavy reliance on AI-generated code can lead to “premature trust”—accepting output without checking correctness, security, or whether it fits the problem. In one study, many students could not identify missing security controls in AI-suggested code even when asked directly.  Other research finds that students with weaker coding skills are more likely to seek AI assistance, and that removing the tool makes the same tasks feel much harder. [dl.acm](https://dl.acm.org/doi/10.1145/3769694.3771124)

## The psychology behind it

| Behavior | Likely psychological driver |
|---|---|
| “The code runs, so it’s fine” | They are optimizing for immediate completion, not long-term understanding |
| They only know the big flow | They are doing surface learning: recognizing the outline without building the underlying skill  [doi.apa](https://doi.apa.org/doi/10.1037/0022-0663.100.2.443) |
| They avoid trying first | Fear of failure, low confidence, or work-avoidance can make effort feel threatening  [doi.apa](https://doi.apa.org/doi/10.1037/0022-0663.100.2.443) |
| They keep asking AI | Cognitive offloading: the tool absorbs the difficult thinking that would normally build skill  [arxiv](https://arxiv.org/html/2601.20245?ref=cpj.fyi) |
| They defend it as efficiency | They may genuinely believe speed equals competence, especially if they have not yet experienced the cost |

This is not unique to CS majors. Complex skills require repeated effort, practice, and persistence; anxiety, insecurity, and fear of ridicule can reduce motivation and interfere with learning.  If someone repeatedly feels “I can’t do this alone,” they may begin avoiding independent effort altogether—a pattern related to low self-efficacy and learned helplessness. [doi.apa](https://doi.apa.org/doi/10.1037/0022-0663.100.2.443)

## Why “it works” is not enough

Code that compiles or produces the expected output can still be wrong in important ways: it may mishandle edge cases, leak data, break under load, use outdated libraries, or contain logic errors that only appear later. AI can also produce plausible but incorrect explanations—hallucinations—so a confident explanation is not evidence of correctness. [web3.arxiv](https://web3.arxiv.org/pdf/2512.19644)

A responsible workflow is:

1. Understand the problem and break it into small pieces.
2. Attempt a solution or write pseudocode first.
3. Use AI to explain, compare approaches, or generate test cases.
4. Read the code line by line and ask, “What does this actually do?”
5. Run meaningful tests, including unusual inputs and failure cases.
6. Be able to explain the solution without the AI.

## How to talk to them

Instead of calling them lazy or brain-rotted, make the issue concrete:

- “Can you explain what this function does without reading the AI answer?”
- “What happens if this input is empty, negative, or invalid?”
- “Which line handles the error case?”
- “Let’s delete one part and see whether you can rebuild it.”
- “Use AI after you try, then explain the difference between your attempt and its answer.”

A fair boundary is: **AI can help you learn, but it should not do the learning for you.** If they only copy output, they may pass an assignment today but struggle badly in an interview, a real project, debugging production code, or the next course where AI is restricted. Studies suggest that heavy AI reliance can reduce skill formation and leave students unable to apply concepts independently. [arxiv](https://arxiv.org/html/2601.20245?ref=cpj.fyi)

You cannot force them to care. But you can model the better standard: understand first, use AI to accelerate—not replace—your thinking, and always verify with tests and real understanding. [dl.acm](https://dl.acm.org/doi/10.1145/3769694.3771124)
