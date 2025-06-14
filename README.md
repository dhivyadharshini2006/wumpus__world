<h1>ExpNo 9: Solve Wumpus World Problem using Python demonstrating Inferences from Propositional Logic</h1> 
<h3>Name: Dhivya Dharshini B </h3>
<h3>Register Number:  212223240031 </h3>
<H3>Aim:</H3>
<p>
    To solve  Wumpus World Problem using Python demonstrating Inferences from Propositional Logic
</p>
<h1>Problem Description</h1>
<hr>
<h2>Wumpus World</h2>
<hr>
The Wumpus world is a simple world example to illustrate the worth of a knowledge-based agent and to represent knowledge representation.

The figure below shows a Wumpus world containing one pit and one Wumpus. There is an agent in room [1,1]. The goal of the agent is to exit the Wumpus world alive. The agent can exit the Wumpus world by reaching room [4,4]. The wumpus world contains exactly one Wumpus and one pit. There will be a breeze in the rooms adjacent to the pit, and there will be a stench in the rooms adjacent to Wumpus.

![image](https://github.com/natsaravanan/19AI405FUNDAMENTALSOFARTIFICIALINTELLIGENCE/assets/87870499/cd6b68dc-c79f-4dcb-8126-04da90d65912)

<center>Wumpus World Representation</center>
<p>
This is a python program that uses propositional logic sentences to check which rooms are safe. 

It is assumed that there will always be a safe path that the agent can take to exit the Wumpus world. The logical agent can take four actions: Up, Down, Left and Right. These actions help the agent move from one room to an adjacent room. The agent can perceive two things: Breeze and Stench.
</p>

<hr>
<h1>Sample Input and Output:</h1>
<hr>

![image](https://github.com/natsaravanan/19AI405FUNDAMENTALSOFARTIFICIALINTELLIGENCE/assets/87870499/8696111a-a4a7-47cb-ba4b-43a4ef88573f)
![image](https://github.com/natsaravanan/19AI405FUNDAMENTALSOFARTIFICIALINTELLIGENCE/assets/87870499/4be5bf06-79fa-4fa0-9334-38a33f06060b)

<hr>
<h1>Algorithm:</h2>
<hr>

1. Initialize variables: row, column, arrow, player, score, and wumpus.

2. While player is True: Prompt for movement direction (u, d, l, r).

3. Update position: Adjust row or column based on input; check boundaries.

4. Print current location.

5. Handle special tiles: "Smell" with arrow, "WUMPUS", "GOLD", "PIT".

6. End game: Upon reaching "GOLD", "WUMPUS", or "PIT".

<hr>
<h1>Verified Input and Output:</h1>
<hr>

![image](https://github.com/user-attachments/assets/aa71c6df-1d8b-4b48-bc44-24572664c106)
<br>

<hr>
<h1>Result:</h1>
<hr>

<p>Thus, the Wumpus World Problem is solved using Python demonstrating Inferences from Propositional Logic successfully.
