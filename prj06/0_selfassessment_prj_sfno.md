## Where can you improve your rubrics?

Take a few minutes to review `rubrics.md`.  Thinking about your draft slides,
write 1-2 sentences reflecting on each rubrics: What specifically can you do to
improve your (potential) score in each category?

**SP, Statement of problem**:
Might need to provide additional context in connecting from physics like the weather phenomena to broad terms like waves in atmopshere/ocean to more specific reason in looking at shallow water equation. 

**ID, Implementation details**:
A little time is needed to discuss the difference between spherical fno and fno - i.e. the spherical harmonics, and the feature of the architecture it entails. Should acknowledge heavy lifting is done with `torch_harmonics`. 

**R, Results**:
Need to finish the sides first. Breifly go over training details when comparing with modified cases control (base) training case to save time. Transition to results leading with why the question(s) are particularly interesting. 

- Currently included Loss function sensitivity - but not the most interesting perhaps? 
- Stability with autoregressive rollout (if we include more dates to regress for more information to predict - would that return better prediction with not much change in drift?) is there a cap? Would it improve and generalize better over time? 
- Compute with GPUs (how long would it take if l degree in spherical harmonics gets very very large - would that return better and/or more finer-scale features that gets closer to trianing data?)? Bottleneck in training - solver in generating the training data, or? 

Maybe just choose one of the above for a simpler story. 

**C, Reflections**:
Can merge learnt and future work as a single slide as summary slide to faciliate audience coming up with questions. Presentation slides need to be done and polished, most importantly practiced. 
