# AI Solution Decision Matrix · Juno

## The decision

Determine the best approach for implementing Juno's automated prioritization engine that converts customer feedback into ranked product opportunities.

## Options scored

| Option | Cost | Speed | Control | Moat | Risk | Score |
|---|---|---|---|---|---|---|
| Build | 2 | 2 | 5 | 5 | 3 | 3.4 |
| Buy / API | 5 | 5 | 3 | 2 | 4 | 3.8 |
| Fine-tune | 2 | 2 | 4 | 4 | 2 | 2.8 |

## Recommendation

Buy/API + RAG
 
Using an existing LLM API with a RAG architecture provides the fastest path to value while maintaining acceptable control and minimizing implementation effort. Juno can leverage modern foundation models while grounding all recommendations in customer evidence and company documentation.
