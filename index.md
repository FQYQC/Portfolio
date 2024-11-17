# About Me

**I'm now a Master's student at [Electrical and Computer Engineering](https://ece.ucsd.edu/), [UC San Diego](https://ucsd.edu/), majoring in Machine Learning and Data Science.**

**I received my Bachelor's Degree from [Peking University](https://english.pku.edu.cn/) this year. At PKU, I'm a member of the first [Tong Class](https://tongclass.ac.cn/) (an honorary pilot class in AI) at [Yuanpei College](https://yuanpei.pku.edu.cn/), and was also affiliated with [Institute for Artificial Intelligence](https://www.ai.pku.edu.cn/).**

**My research and career interests include but are not limited to**

- **Research:** Machine Learning, (Machine and Human) Cognitive Reasoning, LLMs, Planning.
- **Industry:** Self-driving, Recommendation, Cloud/Distributed Computation, Data-driven Learning, Software Development, especially related to AI and AI products.

**Feel free to contact me through [[Github]](https://github.com/FQYQC)
[[LinkedIn]](https://www.linkedin.com/in/yilue-qian/)
[[Email]](mailto://qianyilue@outlook.com), I'm happy to share ideas and infos.**


# Education

### University of California, San Diego

#### *Sep 2024 - Spring 2026 (Expected)* 

- **Master of Science** at [ECE Dept.](https://ece.ucsd.edu/)
- Major in **Machine Learning and Data Science**


### Peking University

#### *Sep 2020 - Jul 2024*

- **Bachelor of Engineer** at [Yuanpei College](https://yuanpei.pku.edu.cn/)
- Major in **Artificial Intelligence (Computer Science)**
- Member of the first [Tong Class](https://tongclass.ac.cn/).

# Professional Experience

### Megvii Technology Limited

#### *Jun 2023 - Dec 2023*

- **Self-driving software development intern**
- **Models and tools development for self-driving vehicles.**
- Propose **Transformer neural networks** to simulate vehicle trajectories.
- Develop **visualization tools** to better understand vehicle behaviors.
- Build **benchmarks** to evaluate trajectories.

### Beijing Institute for General Artificial Intelligence (BIGAI)

#### *Mar 2022 - Jun 2023*

- **Research Intern**
- **Individual Research in Cognitive Reasoning Lab,** under supervision of [Prof. Wei Wang](https://cognn.com/) and [Dr. Lifeng Fan](https://lifengfan.github.io/).
- Project on **concept disentanglement, causal transition, symbolic reasoning, and visual planning**.
- Project on **3-D spatial reasoning**.
- Member of **Artificial Social Intelligence** group.

# Publications

### Learning Concept-based Causal Transition and Symbolic Reasoning for Visual Planning

- **Yilue Qian**, Peiyu Yu, Ying Nian Wu, Yao Su, Wei Wang, Lifeng Fan
- **Published at IROS 2024 as Oral Pitch.**
- [[Paper]](https://fqyqc.github.io/Portfolio/assets/publications/LearningCCTSRVP/paper.pdf)
[[Web]](https://fqyqc.github.io/ConTranPlan)
[[Video]](https://youtu.be/qWfZV8vI7Q0)
[[Poster]](https://fqyqc.github.io/Portfolio/assets/publications/LearningCCTSRVP/poster.pdf)

### Evaluate and Mitigate Human-like Cognitive Biases in LLMs

- Coming soon.

# Projects

### Efficient Linear Algebra Solver with GPU Acceleration

#### *Oct 2024 - Nov 2024*

- **Keyword: Cuda, Parallel Computation**.
- Developed a high-performance Linear Algebra Solver using C++ and Cuda, with advanced parallel techniques such as blocking, tiling, shared memory, and data shuffling within threads. Achieved 82% of the performance efficiency of NVIDIA cutlass.
- Conducted comprehensive benchmarking and profiling with NVIDIA Nsight, providing detailed insights into memory usage and execution time.

### Efficient Compilation and Scheduling for CNNs on Compute-in-memory Units

#### *Feb 2024 - Mar 2024*

- **Keyword: CNN, Compilation, Compute-in-memory**.
- Designed a highly efficient compilation approach tailored for CNN inference on both single- and multi-unit compute-in-memory chips. The method includes network reconstruction, memory access management, and computational operation scheduling.
- Conducted comprehensive experiments to verify the effectiveness of the proposed methods. The approach achieves 98% reduced memory access and 67% faster inference speed compared to classic compilation techniques.

### Evaluating and Mitigating Human-like Cognitive Biases in LLMs

#### *Feb 2024 - Mar 2024*

- **Keyword: Large Language Models, Cognitive Bias, Benchmarking, Cognitive Hierarchy**.
- Established a comprehensive cognitive bias evaluation system, CoBAL, which includes datasets and evaluation metrics to assess 9 kinds of cognitive biases in large language models. Collected and reported human performance on the CoBAL benchmark.
- Evaluated over 7 cutting-edge language models (GPT-4, Gemini-1.5, Claude-3, etc.) on the CoBAL benchmark, and conducted a thorough analysis and comparison of exist cognitive bias moderation methods across these models.
- Proposed a novel and effective cognitive bias mitigating method, HiTHer, introducing the cognitive hierarchy theory into this field for the first time. It demonstrates 40-85% higher performance on CoBAL benchmark compared to previous methods.

### Playing Brick Breaker with A Robotic Arm System

#### *Feb 2023 - Mar 2023*

- **Keyword: Robotic arms, Game AI, Inverse Kinematics**. Worked as co-author.
- Utilized a polynomial model to plan the trajectory of the robotic arm’s end effector. Controlled it to reach the target hitting point precisely, achieving accuracy in both time and velocities while avoiding collisions with walls.
- Developed a C++ library to solve inverse kinematics problems, resulting in an 82% acceleration of the process.
Utilized Pygame for visualization, showcasing the gameplay with a smooth and consistent 60 fps.

### Playing Hanabi with ToM and Intrinsic Rewards

#### *Sep 2022 - Dec 2022*

- **Keyword: Reinforcement Learning, Theory of Mind**. Worked as co-author.
- Designed a goal-oriented intrinsic reward module for Hanabi agents, which intrinsically rewards the agent for achieving short-term goals. This module improves RainbowDQN-based agent’s average game score by 2.20 and 4.90 for 3- and 4-player games.
- Designed a hand card inference module that inferred other players’ beliefs by observing their actions, imitating human Theory of Mind (ToM). This module enhances performance by 0.47 and 2.62. These modules apply to any RL codebase.