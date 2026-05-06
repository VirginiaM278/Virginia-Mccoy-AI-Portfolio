mplemented and compared two agents in the classic CartPole-v1 environment — a random agent and a Q-Learning agent — to explore how reinforcement learning enables an AI to improve purely through trial and error. This project builds a direct conceptual bridge between classical RL and modern RLHF-trained LLMs.
Problem Statement
Can an AI agent learn to balance a pole on a moving cart without being explicitly programmed how to do it? This project demonstrates the power of the reinforcement learning loop: perceive the state → take an action → receive a reward → improve over time.
Approach & Methodology

Used the CartPole-v1 environment from the Gymnasium library
First ran a random agent to establish a baseline — average score of ~20 out of 500
Implemented a Q-Learning agent that learns from experience across multiple training episodes
Tracked and visualized performance improvements episode by episode
Connected RL principles to RLHF (Reinforcement Learning from Human Feedback) used in LLMs like GPT-4

Technologies Used

Python
Gymnasium (OpenAI Gym)
NumPy
Matplotlib

Environment Details

Environment: CartPole-v1
State space: Cart position, cart velocity, pole angle, pole angular velocity
Actions: Push cart LEFT or RIGHT
Reward: +1 for every timestep the pole stays upright
Goal: Keep the pole balanced for as long as possible (max score = 500)

Results

Random Agent Average Score: ~20 out of 500
Q-Learning Agent: Significantly improved scores after training episodes

Key Concepts Covered

The RL loop: state → action → reward → next state
Exploration vs. exploitation tradeoff (epsilon-greedy strategy)
Q-Learning and policy improvement over episodes
Episode-based training and performance tracking visualization
Connection between classical RL and RLHF in modern LLMs

How to Run

Open the .ipynb file in Google Colab or Jupyter Notebook
Run all cells in order from top to bottom
All dependencies are installed in the first cell
Estimated time: under 30 minutes

Dependencies
pip install gymnasium matplotlib numpy
Learning Outcomes

Built real intuition for how the RL reward loop drives agent improvement
Observed firsthand the dramatic difference between random failure and learned competence
Connected classical Q-Learning to RLHF training used in production LLMs like GPT-4
Gained hands-on experience with Gymnasium, the industry-standard RL environment library
