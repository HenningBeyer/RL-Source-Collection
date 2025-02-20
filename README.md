# RL-Source-Collection
A relevant collection of RL research and general sources (ranging from 2018 -2024) [is provided here](https://drive.google.com/drive/folders/1nefw5FQm6zTuMbPGvaM67fKIJJ6Yu-uV).

# Depictions

New to RL? Here are a few self-made RL depictions, showing major research areas and practical approaches with their connections. The depictions are generally available as a shared [Google Slides presentation](https://docs.google.com/presentation/d/1rUTgfJ1dmDprwdEZaN-7dcyWc7nw73MpmQmUY44LPXY/edit?usp=sharing). And there are still a few more slides in there.

## A General Overview of RL

Most RL applications employ a classic model-free online RL with agents like PPO, SAC, or TD3. However, many real-world applications require more specific approaches, including methods from model-based RL, offline RL, and simulations. 

The two following depictions are provided for general decision-making for real-world RL projects:

<img src="https://github.com/user-attachments/assets/784f6f3f-c945-43d4-88bf-129ac08d335d" alt="Description" width="800">
<br>


Once one grows a better understanding of RL, the decision-making will look more detailed like this:

<img src="https://github.com/user-attachments/assets/ea072635-6b39-488b-b0e3-2b7e4f24589a" alt="Description" width="1000">

And eventually, it will look even more detailed and worked out.


## Additional Depictions:

## Preparing Simulation Code

Simulations play a crucial role in training RL agents for deployment, and in conducting the necessary testing while allowing full flexibility for research. To enable a seamless sim2real transfer with good downstream performance, one can employ the following techniques:

<img src="https://github.com/user-attachments/assets/aadd753c-47c3-4111-b306-35f6bb9cd5f2" alt="Description" width="900">

## An Overview of Offline RL

Alternatively, one can leverage offline data via offline RL to train RL agents without a dedicated simulation, when online data is sparse or expensive/risky to collect.

Another way of leveraging offline data is to train a full simulation world model from available offline data, or a residual model on top of the analytical simulation. This approach can be seen as model-based offline RL and can be more accurate than simply using the analytical simulation alone.

### Planning Offline Data Collection

Collecting offline data for RL needs expertise in RL to be done correctly. Generally, one leverages the available data sources and tries to collect as much high-quality data with good coverage of different policy behaviors, environment transitions, and rewards. A more careful data preparation follows later.

<img src="https://github.com/user-attachments/assets/d2350145-7376-4831-b4d9-f57a93535bb7" alt="Description" width="900">

### Preparing an Offline Dataset

<img src="https://github.com/user-attachments/assets/77a5c046-c04f-4151-9af7-270e6abf3a85" alt="Description" width="900">

## Multi-Agent RL (MARL)

Many RL control applications involve more than just one agent, transforming the task to a MARL problem. In general, one can choose between the three MARL paradigms of CTCE, DTDE, and CTDE, based on the problem, and further maintain scalability through an effective MARL communication ruleset or protocol.

<img src="https://github.com/user-attachments/assets/e6166ab2-1757-4345-aa11-6d3de5cb96cf" alt="Description" width="900">


One may further divide MARL into collaborative, coorperative, competetive, and individualistic tasks.

<img src="https://github.com/user-attachments/assets/323b5f17-6ae5-4ee8-aead-e8e4688898ef" alt="Description" width="900">

MARL will allow for controlling more complex and large-scale systems, making it a highly relevant topic in research. Yet scalably coding and deploying multi-agent systems (MAS) can be very challanging.

## Further Reading

There are a lot more topics to explore in RL and MARL research. At best, one also checks out books like [the MARL Book](https://www.marl-book.com/download/marl-book.pdf) or [Deep Reinforcement Learning (price-worthy German version)](https://www.amazon.de/Deep-Reinforcement-Learning-Praxis-Handbuch-Professional/dp/3747500366), and goes into a personal project with it.

Furthermore, going extensively through the latest research papers in my [source collection](https://drive.google.com/drive/folders/1nefw5FQm6zTuMbPGvaM67fKIJJ6Yu-uV), and [open-source research projects and frameworks](https://github.com/HenningBeyer?tab=stars) helps a lot too. 

Some initial areas to begin with are: 
- online RL
- offline RL
- offline-to-online RL
- Model-based online RL
- Model-based offline RL
- Multi-agent RL (MARL)
- Graph neural networks (GNNs)
- RL and MARL algorithms
- Computational aspects of RL and MARL




