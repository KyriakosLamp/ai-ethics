# Exercise 1: Understanding AI Bias

# PART A
1. Find or simulate a short example of model bias (e.g., gender, nationality, profession).
2. Explain in your own words why that bias may exist.
3. Propose one mitigation (data balancing, prompt phrasing, model choice).
```
While browsing youtube a video from MKBHD popped up. It was a video about the AI enchance  feature on xiaomi camera.
The feature kicked in live while recording a video of a face in selfie mode. Comparing the video recorder with
and without that feature revealed that it makes the dark colloured skin appear brighter, more light skinned.

The bias propably exists because of the training data. Xiaomi, due to its nature aim at the Asian market , where 
most of the people are white. This means that most of the training data are taken from white people and it create 
a bias when faced with dark skinned faces.

A mitigation for this bias could be data balancing with more dark skinned faces, but that whould be expensive and time 
consuming. Even a simple toggle specificaly for the tone of the face ( make it brighter or not) whould create better 
results for the rest of the world where people have less white skin
```
# PART B
1. Ask AI to deepen your understanding:
```
TLDR of what chatgpt said:

Technical

❗ Legacy “beautification” algorithms designed to lighten skin.

❗ Tone-mapping and HDR pipelines not calibrated for darker complexions.

❗ Segmentation or face detection errors skewing brightness.

❗ Training labels that encode biased human editing.

Sociocultural

❗ Aesthetic norms in certain markets emphasize brightening.

❗ “Beauty mode” expectations override “accurate representation.”

Organizational

❗ Technical debt from older camera systems.

❗ Lack of inclusive UX testing across skin tones.
```

# PART C - Critical reflection

```
After the promt hit the AI i realised that my reasearch was incomplete. For the above example, i learned that its
trully a feature and not a bug, as the caltural and general belief of 'brighter makes your skin's details appear'
rather than asian-white people data training. Also darker skins - less light and shadows are more easily affected
by aggresive HDR and general camera pipelines and auto corrections. AI amplified my thinking and provided more 
context and reasearch and gave more spherical reasoning and contributions. Even told me that the mitigations
i purposed could backfire and are inaffective due to EU data regulations for general markets. AI outpermormed my
poor reaserch with its huge data-libraries-knowleadge.
