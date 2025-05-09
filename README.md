This repo is for my frontend projects — both old and new. I’ll be deploying a few demos here first, just to get things rolling. The source code will be added later, once i clean things up a bit.
## City 
[Link](city.harrypham.dev)

A randomly generated city you can rotate and zoom around. Supports light/dark mode.
Built with plain old HTML/CSS/JS and three.js — nothing fancy.
Mainly an experiment with shaders.

**Why it’s exciting**

This has a ton of potential. I’m planning to:
- add nature, people, vehicles — and animate them (already done, will be release soon)
- include sky, water, and other shaders (not the common one). these are hard but look incredible.
- maybe let users upload 3d models and render them in the same architecture-drawing style. allow them to place the model.
- try building an algorithm to place buildings randomly in a way that looks good and realistic (hard because object sizes vary a lot).
- any suggestions?

**Limitation**
  
Performance. The current scene has ~800–900 buildings and already eats ~1GB of memory. It’s not laggy yet, but scaling this up is a serious problem. And i haven’t figured out how to fix it yet.
