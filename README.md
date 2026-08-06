# Briefly explain the work that you did on this project: What code were you given? What code did you create yourself?

### For this project, I worked on developing and improving an intelligent agent that could navigate an environment and learn the optimal path to reach a goal using reinforcement learning. The project provided the initial framework, including the environment, game logic, state representation, and parts of the agent structure. The provided code handled much of the setup required to run the simulation, including the maze, rewards, movement rules, and training environment.

### The code I created, following the provided pseudocode, focused on implementing the learning process for the intelligent agent. I worked with the Q-learning approach by developing the logic that allowed the agent to make decisions based on previous experiences, update its knowledge through rewards and penalties, and improve its performance over multiple training episodes. Through this process, I gained a better understanding of how artificial intelligence systems learn from interactions with an environment rather than relying only on explicitly programmed instructions.

### The table below shows the results of multiple reinforcement learning experiments using different epsilon values. Epsilon controls the exploration rate of the agent, determining how often it chooses random actions instead of relying on previously learned information. For each epsilon value, the agent was trained three separate times, and the number of epochs required to achieve a 100% win rate was recorded. The average column represents the mean number of epochs across the three experiments and provides a better comparison of overall performance.

<table>
  <tr>
    <th>Epsylon</th>
    <th>Experiment 1</th>
    <th>Experiment 2</th>
    <th>Experiment 3</th>
    <th>Average</th>
  </tr>

  <tr>
    <td>0.05</td>
    <td>
      100% win rate: epoch 400<br>
      <img width="100%" src="https://github.com/user-attachments/assets/c43ff94e-e947-4a32-97cf-aa932ab935d4">
    </td>
    <td>
      100% win rate: epoch 363<br>
      <img width="100%" src="https://github.com/user-attachments/assets/dc045c55-1c7a-41bb-a739-5868daad60ac">
    </td>
    <td>
      100% win rate: epoch 755<br>
      <img width="100%" src="https://github.com/user-attachments/assets/5363c9ac-f1b4-44c6-806e-46a1824e6b97">
    </td>
    <td>506</td>
  </tr>

  <tr>
    <td>0.10</td>
    <td>
      100% win rate: epoch 295<br>
      <img width="100%" src="https://github.com/user-attachments/assets/9804b662-1012-48cd-aa0b-c9568257bf0a" />
    </td>
    <td>
      100% win rate: epoch 130<br>
      <img width="100%" src="https://github.com/user-attachments/assets/d6893118-1bc5-4e9a-b465-d17de6c8a8c2" />
    </td>
    <td>
      100% win rate: epoch 271<br>
      <img width="100%" src="https://github.com/user-attachments/assets/f2e76b3c-0d77-43d1-b22a-b22bb0ad3be6" />
    </td>
    <td>232</td>
  </tr>

  <tr>
    <td>0.25</td>
    <td>
      100% win rate: epoch 445<br>
      <img width="100%" src="https://github.com/user-attachments/assets/b421e629-77d7-4966-bdc1-15d149e4ff23" />
    </td>
    <td>
      100% win rate: epoch 478<br>
      <img width="100%" src="https://github.com/user-attachments/assets/efcd5c1c-6b50-4399-9a67-08cc135f3f4d" />
    </td>
    <td>
      100% win rate: epoch 467<br>
      <img width="100%" src="https://github.com/user-attachments/assets/24cf1c3d-bfb6-43d6-8876-bfcef74e418f" />
    </td>
    <td>463.33</td>
  </tr>

  <tr>
    <td>0.50</td>
    <td>
      100% win rate: epoch 337<br>
      <img width="100%" src="https://github.com/user-attachments/assets/26022508-7920-42c7-bda2-894670aacacf" />
    </td>
    <td>
      100% win rate: epoch 393<br>
      <img width="100%" src="https://github.com/user-attachments/assets/7f01489f-2f53-49c6-ae01-8305cb26c51e" />
    </td>
    <td>
      100% win rate: epoch 432<br>
      <img width="100%" src="https://github.com/user-attachments/assets/5e6d48db-3ed9-40bf-a1b7-8abf066d3921" />
    </td>
    <td>387.33</td>
  </tr>

  <tr>
    <td>0.75</td>
    <td>
      100% win rate: epoch 401<br>
      <img width="100%" src="https://github.com/user-attachments/assets/cbe6eca7-6aad-4ae8-ad84-9c9331cfa2d0" />
    </td>
    <td>
      100% win rate: epoch 449<br>
      <img width="100%" src="https://github.com/user-attachments/assets/8edf7342-5318-400c-b714-c6da0dba411f" />
    </td>
    <td>
      100% win rate: epoch 359<br>
      <img width="100%" src="https://github.com/user-attachments/assets/a5549f87-3b1b-4444-bb3f-a4db562f41c2" />
    </td>
    <td>403</td>
  </tr>

  <tr>
    <td>1.00</td>
    <td>
      100% win rate: epoch 354<br>
      <img width="100%" src="https://github.com/user-attachments/assets/a45354f1-b7ea-42b8-805c-898102cd8d58" />
    </td>
    <td>
      100% win rate: epoch 363<br>
      <img width="100%" src="https://github.com/user-attachments/assets/5823e5cf-86b0-4070-b72f-337b8f36e623" />
    </td>
    <td>
      100% win rate: epoch 398<br>
      <img width="100%" src="https://github.com/user-attachments/assets/e23366f8-5a80-497b-865f-59269848c682" />
    </td>
    <td>371.67</td>
  </tr>

</table>

### The results show that an epsilon value of 0.10 produced the fastest convergence, reaching a 100% win rate in an average of 232 epochs. Lower exploration values, such as 0.05, caused slower learning because the agent did not explore enough possible actions. Higher epsilon values also increased the number of required epochs because the agent spent more time exploring instead of exploiting the knowledge it had already gained. These experiments demonstrate the importance of balancing exploration and exploitation when training reinforcement learning agents.

# Connect your learning from throughout this course to the larger field of computer science:
* # What do computer scientists do and why does it matter?

* # How do I approach a problem as a computer scientist?

* # What are my ethical responsibilities to the end user and the organization?


