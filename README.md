# Projects

## 1.) Datalus - Synthetic Tabular Data Generator
* Generates realistic development data to streamline ML model fine-tuning, product debugging, and privacy compliance. Capacity for neurosymbolic data generation and relational reasoning as well as integration with plug-and-play language models.
* Won **“Best Technical Innovation”** for Senior Design among 250+ graduating UPenn Computer Science students

<div style="text-align: center;">
    <a href="https://www.youtube.com/watch?v=PxgdReDr7-c">
        <img src="Datalus - Synthetic Data Generation/img/DatalusPoster.png" alt="IMAGE ALT TEXT HERE" width="1000"/>
    </a>
</div>

## 2.) DarkChess: The first 'Fog of War' chess engine

<a href="img/fog_of_war_chess-writeup.pdf" target="_blank">
    <img src="Fog of War Chess Engine/img/FogOfWarPaperFirstPage.png" align="right"
         alt="Size Limit logo by Anton Lovchikov" width="300" height="423">
</a>

Fog of War Chess, or Dark Chess, is a chess variant where players can only see the squares their pieces can move to on the current turn, turning it into an imperfect information game. Despite its modest popularity, there are currently no high-level engines for this variant, unlike other chess games with advanced AI. Fog6200 is the first Fog of War Chess engine, developed using model-free reinforcement learning to approximate Nash equilibrium and address the challenges of imperfect information. This engine is inspired by the 2022 DeepMind paper “Mastering the Game of Stratego with Model-Free Multi-agent Reinforcement Learning,” with adaptations in memory structure, algorithm, architecture, and game-specific heuristics.

### Overview
* **Popularity**: One of the more popular chess variants and is available for online play at platforms like Chess.com.
* Fog of War Chess comes in stark contrast to the majority of other chess variants that nearly all have engines that play at super-human levels.
* Because the board becomes segmented into a region of known and unknown states, the variation transforms chess from a perfect information to **imperfect information game**. Due to the game tree being intractably large for the majority of game positions as a result of this imperfect information, we investigated using a model-free reinforcement learning algorithm to approach Nash equilibrium to prevent exploitable positions.
* The work applies the implementation of a 2022 DeepMind paper titled ``Mastering the Game of Stratego with Model-Free Multi-agent Reinforcement Learning" with key differences in memory structure, algorithmic and architecture alterations, and game-specific heuristic improvements.


## 3.) Minecraft Implementation
<a href="https://www.youtube.com/watch?v=OOhRqecWjTQ&t=1s" target="_blank">
    <img src="Minecraft Implementation/img/MountainBiome.jpg" align="right" alt="Size Limit logo by Anton Lovchikov" width="40%">
</a>

Built a first-person and interactive 3D World from scratch (no game engine) using C++ and the OpenGL pipeline. The game implements the key features of Minecraft as is described below in the expandable tabs. This includes a diverse landscape with different biomes and terrains, artificial intelligence in the non-playable characters, inventory/crafting systems, and much more. The final product included over 30 pairs of C++ header and source files as well as over a dozen glsl vertex and fragment shader files with over 10,000 total lines of written code. 

For Video overview, click on image to the right



## 4.) Adapting Interpretability Techniques to Generative Diffusion Models

<div style="text-align: center;">
    <a href="Interpretability of Diffusion Models/img/trustworthymachinelearning_diffusion.pdf">
        <img src="Interpretability of Diffusion Models/img/TrustworthyML.png" alt="IMAGE ALT TEXT HERE" width=40% align="right"/>
    </a>
</div>

Interpretable models are crucial for understanding complex black box models. Techniques like LIME and SHAP are well-known for their effectiveness, yet their use with generative diffusion models is still developing, especially in linking text prompts to generated images. Identifying which parts of an image relate to specific tokens can help address semantic misrepresentations. This project adapts SHAP and LIME for diffusion models to highlight imagery linked to each term. We aim to map words to objects in images by analyzing diffusion process steps using open-source models or state-of-the-art image segmentation. This method identifies the significance of words and their related image concepts, advancing explainable generative models by enhancing token and image shape interpretability.


## 5.) DigiNotes: Comprehensive Lecture Note Digitization Tool
<a href="DigiNotes - Lectureboard Synthesizer/img/DigiNotes-FirstPage.png" target="_blank">
    <img src="DigiNotes - Lectureboard Synthesizer/img/DigiNotes-FirstPage.png" align="right" alt="Size Limit logo by Anton Lovchikov" width="40%">
</a>

When it comes to capturing notes, whether they're from a professor's lecture on a chalkboard or a friend's handwritten notes on paper, the easiest method is often to snap a quick photo with your phone. These images usually contain a mix of text, numerous equations, and some diagrams.

Our project delves into the innovative process of transforming these handwritten elements into a digital format that is both accessible and easy to understand. By leveraging advanced recognition techniques, we aim to identify and process words, equations, and diagrams, converting them into a structured digital representation.

This approach not only preserves the content for future reference but also enhances its usability by making it searchable and editable. Our goal is to bridge the gap between physical and digital note-taking, providing a seamless experience that maximizes the utility of captured notes. Through this project, we hope to make information more accessible and user-friendly, supporting learning and productivity.

https://github.com/a-cowlagi/DigiNotes
