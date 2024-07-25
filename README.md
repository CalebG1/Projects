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
