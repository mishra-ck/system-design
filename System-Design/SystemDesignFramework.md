## How to effectively design system ?
NOTE: A great system design interview is open-ended and there is no one fixed solution.

#### 1. Understand the problem and establish design scope:
```
Ask below questions to understand the exact requirements:
1. List of specific features are we going ot build ? 
2. Number of users expected using product ?
3. Anticipated scaling timeline-3 months, 6 months or else.
4. Company's technology stack, What existing service can be recommended to simplify the design?
```

#### 2. Propose High-Level-Design and reach an agreement:
```
After understanding scope of design, come up with a High-Level-Desgn,
collaborate and seek feedbacks.
1. Come up with an intial blueprint for the design, ask for feedback.
2. Draw box-diagram with key components on paper or white-board. This may inclue 
   API design, clients(WEB/Mobile), data stores, cache, CDN, message queue, etc.
3. Do back-of-envelop estimnation to evaluate if your blueprint fits the scale constraints.
   Also understand if it is really necessary or not during design process.
4. If possible, go through some use cases, this will help frame high-level design,
    and it also helps to discover edge cases might not covered yet.
```

#### 3. Deep dive into design:
```
Once you achieved High-Level-Design feedback, deep dive into each components:
1. Reaching agreement on overall goals and features scope.
2. Draw high-level blurprint for overall design and seek fedback on it.
3. Focus on deep-dive based on feedback on your ideas.
4. Identify and priortize components in the architecture like high-level design.
5. For someone at senior level, discusson should be on system performance characteristics like 
   bottleneck and resource estimations.
6. Dig deep as per design requirement, ex: for URL shortner, hash fucntion design that converts
   long URL into short one.
7. Time management is essential, in case of system design interviews.
```

### 4. Wrap up and seek final feedbacks:
```
Asking follow-up questions gives freedom to discuss other additional points:
1. Identify the system bottlenecks and discuss potential improvements.There will always be scope of improvement.
2. Share a final recap of design and suggest few solutions.
3. Error cases(server failure, network loss..etc) could be discussed.
4. How to  monitor metrices and error logs ?
5. How to handle next scale curve ?
```