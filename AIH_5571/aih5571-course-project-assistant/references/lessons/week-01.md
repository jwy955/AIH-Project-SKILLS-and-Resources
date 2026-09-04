# Week 1 — Course introduction; What is AI and Generative AI

Sources:

- `AIH5571_L1a - Course Introduction.pdf`, slides 1–8
- `AIH5571_L1b - What is AI & Generative AI v2.pdf`, slides 1–46

## Scope boundary

Despite the Lecture 1b title, the supplied slides primarily cover AI, machine learning, and deep learning. Slide 45 says Generative AI will be covered in coming lessons. Do not attribute a detailed GenAI mechanism or definition to Week 1 unless a later supplied lesson explicitly provides it.

## Course introduction

Lecture 1a states the delivery information, teaching team, objectives, learning outcomes, and assessment weights. The instructor invites students to learn, ask questions, and enjoy the course. Students are asked about their previous GenAI-tool use, expectations, and suggestions.

## Artificial intelligence

The slides define AI as systems performing tasks that normally require human intelligence. They associate human intelligence with thinking and reasoning, recognition and judgment, natural-language understanding, sensory interpretation, pattern recognition, problem solving, and decision-making.

The stated fundamental idea is simulating intelligent behavior with algorithms, with human-level artificial general intelligence presented as a long-term vision.

AI is framed as important to daily life, enterprises, academic research, and many industries. An in-class activity asks each student to name one AI tool used in the preceding 24 hours, one example, and the situation of use.

## Traditional AI methods introduced

The lecture emphasizes that AI is not limited to neural networks:

- **Search algorithms:** explore a state space or search tree to reach a goal. A representation contains a root node, edges/actions, and a goal node. Examples include sliding-tile puzzles and route optimization, where intersections are nodes and road segments are weighted edges.
- **Two-person games / adversarial search:** account for an opponent's countermoves using game trees. Chess, Go, checkers, and tic-tac-toe are examples. Deep Blue's 1997 match victory over Garry Kasparov is presented as a historical milestone.
- **Automated reasoning:** uses formal logic and rule-based systems. Its steps can be traced to premises or production rules. Applications mentioned include medical decision support and credit/compliance checking.
- **Genetic algorithms:** evolutionary computation inspired by natural selection. Example uses include timetabling, factory schedules, and airline crew or route planning.

## Machine learning

Machine learning is introduced as a branch of AI that uses data and algorithms to mimic learning from recorded experience.

### Supervised learning

Learns from labeled input-output pairs to predict targets for unseen inputs.

- **Regression:** predicts a continuous numerical value, such as price, temperature, or sales.
- **Classification:** predicts a category from a fixed set, such as spam/not spam, disease/no disease, or a digit class.

### Unsupervised learning

Uses unlabeled data to discover clusters, associations, or structure. Clustering groups similar data points without supplied labels. Examples include customer segmentation, topic grouping, and grouping similar images or student comments.

### Reinforcement learning

Learns through trial and error using feedback, rewards, or punishment, with the goal of mastering dynamic strategies. The slides use game AI and self-driving vehicles as examples.

## Deep learning

Deep learning is presented as part of machine learning based on artificial neural networks and suited to complex nonlinear relationships in large datasets.

The biological analogy describes neurons receiving signals through connections of differing importance. In an artificial neural network:

- input values enter through input nodes;
- connections carry weights representing importance;
- a unit combines weighted inputs and a bias;
- an activation/transfer function determines its output;
- hidden layers receive outputs from preceding layers;
- the output layer performs the final prediction or classification.

The slides state that binary prediction can use one output node, while multiclass classification uses multiple output nodes, such as ten for digits 0–9. Applications named are computer vision, natural-language processing, and autonomous vehicles. TensorFlow Playground is offered as an interactive illustration.

## Important precision notes

- The slides' statement that rule-based reasoning has “no hallucinations or probabilistic errors” is a course-slide claim in the context of deterministic formal logic; do not generalize it to all expert systems or all implementations without external verification.
- Numerical statements and historical claims used in assessed work or presentation slides require external verification before reuse.

