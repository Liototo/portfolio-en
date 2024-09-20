# "Computer science research project": real-time collaboration

Déveloped by Eliott Bell; based on the [jupyter-collaboration](https://github.com/jupyterlab/jupyter-collaboration) project (Jupyter Development Team) and supervised by Zhenyu Cai

Bachelor, semester 6 (feb. 2024 - jul. 2024), EPFL (Ecole Polytechnique Fédérale de Lausanne)

The goal of this semester project was to conceptualise, design and implement an improved version of the jupyter-collaboration extension (allowing real-time collaboration on Jupyter notebooks), aiming to make it a useful tool in educational contexts. This project was divided into two halves:

- The first half of the semester was dedicated to the conception of several small-scale upgrades turning a Jupyter server into a practical, self-sufficient collaboration tool. Said features include a chat system, a poll system and a form of role-based access control.
- The rest of the semester was dedicated to a more complex feature, which is a system allowing Jupyter server moderators to track user activity through the notebook.

The project was supervised by Zhenyu Cai, an assistant teacher at EPFL, to whom I had to give weekly reports on my progress.

### What I did

All of my code is in the jupyter-notebook-collaboration-main/packages/collaboration/src/ folder. The files activitybargraph.tsx, activitydisplay.tsx, activitydotplot.tsx, cellTracker.ts, chatbox.tsx, messageEncoding.ts, ownerdialog.ts, polls.tsx and roles.ts were entirely written by myself, and I also modified several pre-existing files in the same folder. I also added multiple CSS classes to the jupyter-notebook-collaboration-main/packages/collaboration/style/sidepanel.css file to improve the visual presentation of the components I created.

### Developed skills

- Full-stack development

- JavaScript/ programming

- End-to-end feature conception

- Organisation and communication

## Gallery

The chat system that was implemented. The active user's username is underlined for visualisation purposes.
<p align="center"><img src="..\Resources\jup_chat.png" width="30%"></p>

The poll system, allowing to ask multiple-choice questions with two to four answers.
<p align="center"><img src="..\Resources\jup_poll.png" width="30%"></p>

A visualisation of the role-based access control: only users tagged as "teachers" can create polls, others can only participate in them.
<p align="center"><img src="..\Resources\jup_rbac.png" width="30%"></p>

Two visualisations of user activity through a notebook; in the second implementation, each dot represents a user. Each dot is clickable, allowing to directly send a message addressed towards the corresponding user in the chat window.
<p align="center"><img src="..\Resources\jup_track.png" width="30%"></p>
