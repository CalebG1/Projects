# Size Limit [![Cult Of Martians][cult-img]][cult]

<img src="https://ai.github.io/size-limit/logo.svg" align="right"
     alt="Size Limit logo by Anton Lovchikov" width="120" height="178">

Size Limit is a performance budget tool for JavaScript. It checks every commit
on CI, calculates the real cost of your JS for end-users and throws an error
if the cost exceeds the limit.

* **ES modules** and **tree-shaking** support.
* Add Size Limit to **GitHub Actions**, **Circle CI** or another CI system
  to know if a pull request adds a massive dependency.
* **Modular** to fit different use cases: big JS applications
  that use their own bundler or small npm libraries with many files.
* Can calculate **the time** it would take a browser
  to download and **execute** your JS. Time is a much more accurate
  and understandable metric compared to the size in bytes.
* Calculations include **all dependencies and polyfills**
  used in your JS.

<p align="center">
  <img src="./img/example.png" alt="Size Limit CLI" width="738">
</p>

With **[GitHub action]** Size Limit will post bundle size changes as a comment
in pull request discussion.

<p align="center">
<img src="https://raw.githubusercontent.com/andresz1/size-limit-action/master/assets/pr.png"
  alt="Size Limit comment in pull request about bundle size changes"
  width="686" height="289">
</p>

With `--why`, Size Limit can tell you *why* your library is of this size
and show the real cost of all your internal dependencies.
We are using [Statoscope] for this analysis.

<p align="center">
  <img src="./img/why.png" alt="Statoscope example" width="650">
</p>

<p align="center">
  <a href="https://evilmartians.com/?utm_source=size-limit">
    <img src="https://evilmartians.com/badges/sponsored-by-evil-martians.svg"
         alt="Sponsored by Evil Martians" width="236" height="54">
  </a>
</p>

[GitHub action]: https://github.com/andresz1/size-limit-action
[Statoscope]:    https://github.com/statoscope/statoscope
[cult-img]:      http://cultofmartians.com/assets/badges/badge.svg
[cult]:          http://cultofmartians.com/tasks/size-limit-config.html







# DarkChess: The first 'Fog of War' chess engine

## Overview
* Fog of War Chess, also known as Dark Chess, is a chess variant of modest popularity where each player's vision is obscured, limiting their view to only the squares reachable by their pieces on the current turn. This comes in stark contrast to the majority of other chess variants that nearly all have engines that play at super-human levels.
* Because the board becomes segmented into a region of known and unknown states, the variation transforms chess from a perfect information to **imperfect information game**. Due to the game tree being intractably large for the majority of game positions as a result of this imperfect information, we investigated using a model-free reinforcement learning algorithm to approach Nash equilibrium to prevent exploitable positions.
* The work applies the implementation of a 2022 DeepMind paper titled ``Mastering the Game of Stratego with Model-Free Multi-agent Reinforcement Learning" with key differences in memory structure, algorithmic and architecture alterations, and game-specific heuristic improvements.

<div style="display: flex; justify-content: space-around; align-items: center; text-align: center;">
    <div>
        <p>Caption 1</p>
        <img src="https://github.com/user-attachments/assets/baff98be-2dce-4418-be90-d3fd8f065616" alt="Image 1" width="300"/>
    </div>
    <div>
        <p>Caption 2</p>
        <img src="https://github.com/user-attachments/assets/baff98be-2dce-4418-be90-d3fd8f065616" alt="Image 2" width="300"/>
    </div>
</div>


<div style="display: flex; justify-content: space-between; align-items: center; text-align: center;">
    <div>
        <p>Caption 1</p>
        <img src="https://github.com/user-attachments/assets/baff98be-2dce-4418-be90-d3fd8f065616" alt="Image 1" width="300"/>
    </div>
    <div>
        <p>Caption 2</p>
        <img src="https://github.com/user-attachments/assets/baff98be-2dce-4418-be90-d3fd8f065616" alt="Image 2" width="300"/>
    </div>
</div>


<div style="display: flex; justify-content: space-around;">
    <img src="https://github.com/user-attachments/assets/baff98be-2dce-4418-be90-d3fd8f065616" alt="Image 1" width="300"/>
    <img src="https://github.com/user-attachments/assets/baff98be-2dce-4418-be90-d3fd8f065616" alt="Image 2" width="300"/>
</div>


<img src="https://github.com/user-attachments/assets/baff98be-2dce-4418-be90-d3fd8f065616" alt="image" width="300"/>
<img src="https://github.com/user-attachments/assets/baff98be-2dce-4418-be90-d3fd8f065616" alt="image" width="300"/>


![image](https://github.com/user-attachments/assets/baff98be-2dce-4418-be90-d3fd8f065616)

![datalusposter-1](https://github.com/user-attachments/assets/81417509-ad3e-46cf-ac27-06f5f7323bff)

## Try Now!
Try it out at https://www.datalus.dev (registration pre-launch so contact to be given trial credentials!)

## Demo
<div style="text-align: center;">
    <a href="https://www.youtube.com/watch?v=PxgdReDr7-c">
        <img src="https://github.com/user-attachments/assets/3f8fcae5-6806-42a1-a85e-61cf16385022" alt="IMAGE ALT TEXT HERE" width="500"/>
    </a>
</div>
