# NL explanations

## Intro (15 minutes)

- Sometimes an attention map or a collection of examples isn't enough: need more
  explicit information about abstraction in a learned model

- Examples: relational features, black dot in image classifier

- Challenge: hard to hang on to interpretability techniques with precise formal
  characterization while generating more complex explanations.

- Today: work through series of models for generatinig natural language
  *explanations* (some of which are terrible as tools for interpretability in
  their own right) to try to get the best of both worlds.

## Captions (10 minutes)

- Train a model on representations in a learned image classifier. In what sense
  should we expect these to be truthful? Do they actually tell the truth?

## Rationalizations (10 minutes)

- Train a model with an extra term requiring discriminability of the image in
  question. Does this fix the problem? What about doctored datasets?

## Explanations (10 minutes)

- Neuralese-style objective. Where do the predictions differ?

## Unit-level (10 minutes)

- How do we apply this technique at the level of individual units?

## Composition operations? (10 minutes)

- Can we use this technique to identify "primitive" representations for
  high-level features like color or shape? Do these have nice geometric
  interpretations?

## Conclusions (15 minutes)

- Exampeles of things that are hard to get at with less powerful interpretation
  modalities: esp composition.

- Future work: large-scale studies like in dissection papers
