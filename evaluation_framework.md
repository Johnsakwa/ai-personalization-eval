# Evaluation Framework: AI Personalization Quality

## Methodology

This framework evaluates AI personalization quality using a three-dimension rubric.

## Step 1: Prompt Design

Prompts are designed from genuine personal experiences to elicit personalization. Good evaluation prompts:
- Require cross-source reasoning
- Test boundary awareness
- Have verifiable expected personalization signals

## Step 2: Context Source Mapping

| Source | Example Signal |
|--------|----------------|
| Search History | User searched for "easy hikes for seniors" |
| Gmail | User received a parking reservation email |
| YouTube | User watched camping gear reviews |
| Photos | User has photos from a specific location |

## Step 3: Output Assessment

### Grounding (1-5)
- 5: All personalized claims traceable to specific, accurate source data
- 3: Some claims grounded, others vague
- 1: Claims contradict available data

### Integration (1-5)
- 5: Personal context woven naturally
- 3: Personalization present but awkward
- 1: Personalization absent or intrusive

### Helpfulness (1-5)
- 5: Personalization directly improves utility
- 3: Personalization adds minor value
- 1: Personalization distracts or worsens answer

## Step 4: Documentation

Each evaluation includes:
- Original prompt
- Context sources used
- Raw output
- Dimension scores with rationale
- Overall assessment