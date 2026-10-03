dpsmpx

Independent developer building native game technology, systems-driven games, and developer tools.

My current work focuses on building a connected stack of technologies rather than isolated projects:

DPlang → Engine → VoxelRPG → future native products

I develop primarily in C++ and Python, with a strong focus on deterministic simulation, procedural generation, 3D graphics, systems architecture, AI-assisted development, and tooling.

Current projects

VoxelRPG

"3D_Voxel_OpenWorld_RPG" (https://github.com/dpsmpx/3D_Voxel_OpenWorld_RPG)

A systems-driven 3D voxel Action-RPG / open-world game being developed from scratch for Android and Windows.

The project combines:

- Vulkan-based rendering
- deterministic fixed-tick simulation
- procedural world generation
- living settlements and regional simulation
- combat and RPG systems
- NPCs, creatures and world events
- dynamic weather and day/night systems
- native Android and Windows platforms
- performance-oriented rendering and automatic graphics tuning
- extensive automated verification and engineering tooling

VoxelRPG is also the first production consumer and practical validation environment for my independently developed engine technology.

License: proprietary source-available.
The source is available for inspection, but the project is not open source.

Engine

Native game engine technology developed as a separate architectural project inside the VoxelRPG repository.

The engine is designed to remain independent from a particular game and to support future games, tools and other native applications.

Current areas include:

- rendering and Vulkan infrastructure
- platform abstraction
- deterministic simulation foundations
- ECS and entity systems
- world/chunk infrastructure
- audio
- resource and asset systems
- testing and verification
- native Android and desktop execution

VoxelRPG is its first real production consumer, while separate engine-oriented validation is used to prevent game-specific assumptions from becoming engine architecture.

The long-term goal is to turn the engine into reusable technology for future native products.

Current status: development-stage technology, currently maintained in the VoxelRPG repository.

DPlang

"DPlang" (https://github.com/dpsmpx/DPlang)

My own general-purpose systems programming language and toolchain for games, engines, tools and other native software.

The language is being designed around:

- correctness and reliability
- deterministic and reproducible behavior
- explicit resource and memory control
- predictable execution
- long-term language evolution
- strong verification and testing
- efficient build and feedback cycles
- AI-assisted development
- practical native interoperability

The planned toolchain initially targets portable C11 generation and existing native toolchains instead of introducing unnecessary compiler infrastructure.

DPlang is an independent project. VoxelRPG does not depend on it, and any future use of DPlang in production will be evaluated separately based on measurable engineering benefit.

License: proprietary, currently under an interim license while the final licensing model is being designed.

Development approach

I use AI-assisted development as an engineering workflow rather than as a replacement for engineering discipline.

My development process emphasizes:

- architecture before implementation
- explicit decisions and documented constraints
- deterministic behavior
- small, reviewable changes
- automated tests and verification
- continuous auditing
- technical-debt tracking
- reproducible builds and measurements
- independent validation of important changes
- careful control of AI-generated modifications

AI agents are used for implementation, analysis, auditing, testing and documentation, while the project architecture and final decisions remain under human control.

Areas of interest

Game development · native systems · C++ · Python · Vulkan · procedural generation · deterministic simulation · 3D graphics · ECS · algorithms · AI-assisted development · developer tools · computational systems

Selected previous work

Andors-Love

"Andors-Love" (https://github.com/dpsmpx/Andors-Love)

A C++ turn-based RPG project focused on reusable game logic, combat, quests, dialogue and equipment systems, with both terminal and SDL interfaces.

TrueJointTileMaker

"TrueJointTileMaker" (https://github.com/dpsmpx/TrueJointTileMaker)

A pixel-art raster editor project exploring structured image manipulation and a future native C++ architecture.

Other experiments

I have also worked on procedural simulations, evolutionary systems, graph and text-processing tools, procedural track generation, 3D experiments and cellular-automata-inspired projects.

These smaller projects are useful as research and experimentation environments for ideas that later become part of larger systems.

Technology

"C++" "C++20" "Python" "Vulkan" "SDL3" "Android NDK" "Linux" "Git" "GitHub"

Current direction

My long-term goal is to build a reusable technology stack for independent native software development:

DPlang
Language, compiler and toolchain

↓

Engine
Reusable native game and systems technology

↓

VoxelRPG
Production game and technology validation

↓

Future products
Games, tools and other native applications

The projects remain independently useful: future integration is considered only when it provides a measurable practical advantage.

Contact

"VK" (https://m.vk.com/dpsmpx)
