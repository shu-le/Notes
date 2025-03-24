### LLM for language understanding and generation



1. How to learn image representation?

   To consume visual data, how to learn a strong image backbone

   * 4 approaches: supervised learning, contrastive language-image pre-training, image-only(Non-) contrastive learning, masked image modeling.
   * Contrastive language-image pre-training
     * What matters? Data scale, Batch size, Model size.
     * how to improve CLIP? 
       * data scaling up
       * model design
       * objective functions
     * CLIP combine with other learning approaches
   * three high-level principles: Scaling, Contrasting, Masking
   * Future challenges
     * How to further scale up, from data scale and model scale
     * New model training paradigm, beyond CLIP and MIM
     * How to perform unified image-/region-/pixel-level pre-training?
     * How to extend vision models with more flexible, promptable interfaces?
       * How NLP concepts like in-context learning, chain-of-thoughts, prompting, emerging properties can be exhibited in the CV context
     * How to train vision backbones with more innovative data?

2. How to extend vision models with more flexible, promptable interfaces? 

   * Unique Challenges in Vision: Modeling
     * different type of inputs
     * different granularities of tasks
     * different types of outputs
   * Unique Challenges in Vision: Data: Scales differ significantly across different types of annotations
   * Three attempts direction: Closed-set classification to Open-world recognition, Specialist models to Generalist models, Representation learning to Promptable interface.
   * Towards open-world——Bridge vision with language
     * Intuition: language as the common space to share information
     * Benefit: Zero-shot transfer to novel vocabularies
   * Towards generalist——Unify different granularities
     * Intuition: Vision is multi-task, multi-granularity
     * Benefit: Build synergy across task granularities
   * Towards Interface——Take various prompts
     * Intuition: language, spatial prompts and beyond
     * Benefit: Reduce the ambiguity of expressing human intents