## Why use images instead of traditional sensors?

Images provide rich visual information about the environment that traditional sensors cannot capture alone.  
A single camera can detect lanes, road boundaries, obstacles, colors, signs, and lighting conditions, while traditional sensors such as ultrasonic or infrared sensors mainly provide distance measurements.

Using images allows the AI system to learn patterns and contextual information, enabling more intelligent and flexible decision-making.  
This approach closely mimics human vision, making image-based perception more suitable for autonomous driving research.

---

## Why supervised learning over reinforcement learning?

Supervised learning is preferred because it is simpler, more stable, and data-efficient for early-stage autonomous driving systems.  
The model learns from labeled examples such as images paired with steering commands, providing clear guidance during training.

Reinforcement learning requires extensive trial-and-error interaction with the environment, which can be computationally expensive and unstable, especially for physical systems like RC cars.  
Supervised learning allows faster training and more predictable behavior.

---

## How does data quality affect behavior?

Data quality directly influences how the model behaves in real-world scenarios.  
High-quality datasets that are diverse, balanced, and accurately labeled help the model learn robust and reliable driving behavior.

Poor-quality data, such as incorrect labels, blurred images, or limited driving conditions, causes the model to learn incorrect patterns.  
This results in unstable steering, poor obstacle handling, and unreliable performance.

---

## What causes overfitting in driving models?

Overfitting occurs when a model memorizes training data instead of learning general driving rules.  
It is commonly caused by limited datasets, repetitive environments, high model complexity, and insufficient variation in training scenarios.

An overfitted model performs well on known tracks but fails on unseen tracks, reducing adaptability and reliability.

---

## Can the model adapt to new tracks?

The model can adapt to new tracks only if it has learned general features such as lane boundaries and steering patterns rather than memorizing specific layouts.  
Adaptability improves when the training data includes multiple tracks, lighting conditions, and driving environments.

Without retraining or fine-tuning, adaptation is limited.  
However, diverse datasets enable better generalization to unseen tracks.
