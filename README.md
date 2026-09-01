# Awesome Space Robotics [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Robotic systems designed for space environments.

## Contents

- [Hardware Platforms](#hardware-platforms)
- [Software Frameworks](#software-frameworks)
- [Simulation Environments](#simulation-environments)
- [Verification & Validation](#verification--validation)
- [Perception](#perception)
- [Navigation](#navigation)
- [Manipulation](#manipulation)
- [Human-Robot Interaction](#human-robot-interaction)
- [Robot Learning](#robot-learning)
- [Space Exploration](#space-exploration)
- [Assembly & Servicing](#assembly--servicing)
- [Education](#education)
- [Demos](#demos)
- [Datasets](#datasets)
- [Competitions](#competitions)
- [Organizations](#organizations)
- [Recurring Events](#recurring-events)

## Hardware Platforms

### Surface Vehicles

- [CADRE](https://www.jpl.nasa.gov/missions/cadre) - Cooperative Autonomous Distributed Robotic Exploration, a NASA JPL project deploying a team of shoebox-sized rovers to the Moon.
- [Curiosity](https://science.nasa.gov/mission/msl-curiosity/) - NASA's car-sized Mars rover powered by a radioisotope thermoelectric generator.
- [ExoMy](https://esa-prl.github.io/ExoMy) - Open source build-it-yourself rover developed by ESA.
- [JPL Open Source Rover](https://jplopensourcerover.com) - Open source build-it-yourself rover developed by JPL.
- [LEMUR](https://www.jpl.nasa.gov/robotics-at-jpl/freeclimber-lemur-3) - Limbed Excursion Mechanical Utility Robot developed by JPL.
- [Mars Exploration Rovers (Spirit & Opportunity)](https://mars.nasa.gov/mer/) - NASA's twin solar-powered rovers with rocker-bogie suspension and a five-degree-of-freedom instrument arm.
- [MASCOT](https://en.wikipedia.org/wiki/Mobile_Asteroid_Surface_Scout) - Mobile Asteroid Surface Scout developed by DLR and CNES.
- [Perseverance](https://science.nasa.gov/mission/mars-2020-perseverance/) - NASA's Mars rover that landed in Jezero Crater in 2021.
- [RASSOR](https://technology.nasa.gov/patent/KSC-TOPS-7) - Regolith Advanced Surface Systems Operations Robot developed by NASA Kennedy Space Center.
- [RoboSimian](https://www-robotics.jpl.nasa.gov/how-we-do-it/systems/robosimian) - Four-limbed robot developed by JPL with seven degrees of freedom per limb.
- [Sojourner](https://en.wikipedia.org/wiki/Sojourner_(rover)) - NASA's first Mars rover, a 10.6 kg six-wheeled microrobot that landed in 1997 as part of the Mars Pathfinder mission.

### Aerial Vehicles

- [Dragonfly](https://science.nasa.gov/mission/dragonfly/) - NASA dual-quadcopter rotorcraft designed to fly on Saturn's moon Titan.
- [Ingenuity](https://en.wikipedia.org/wiki/Ingenuity_(helicopter)) - NASA's 1.8 kg coaxial-rotor helicopter that achieved the first powered, controlled flight on another planet.

### Free-Flying Robots

- [Astrobee](https://nasa.gov/astrobee) - Free-flying robotic system developed by NASA to assist astronauts inside the ISS.
- [Int-Ball2](https://doi.org/10.1109/MRA.2024.3505776) - Second-generation free-flying camera robot developed by JAXA for the ISS Kibo module.

### Robotic Manipulators

- [Canadarm2](https://www.asc-csa.gc.ca/eng/iss/canadarm2/about.asp) - Robotic arm on the ISS built by MDA for the Canadian Space Agency.
- [Canadarm3](https://www.asc-csa.gc.ca/eng/canadarm3/about.asp) - Next-generation robotic system being developed by MDA for the Lunar Gateway.
- [Dextre](https://www.asc-csa.gc.ca/eng/iss/dextre/about.asp) - Two-armed dexterous manipulator on the ISS that serves as a robotic handyman for delicate maintenance tasks.
- [ERA](https://www.esa.int/Science_Exploration/Human_and_Robotic_Exploration/International_Space_Station/European_Robotic_Arm) - European Robotic Arm installed on the Russian segment of the ISS.
- [GITAI Inchworm Robot](https://gitai.tech/inchworm-robot) - Robotic arm developed by GITAI for in-orbit and lunar surface operations.
- [JEM-RMS](https://iss.jaxa.jp/en/kibo/about/kibo/rms) - Japanese Experiment Module Remote Manipulator System on the ISS Kibo module.

### Humanoids

- [Robonaut 2 (R2)](https://nasa.gov/robonaut2) - Humanoid robot developed by NASA to assist astronauts onboard the ISS.
- [Rollin' Justin](https://www.dlr.de/en/rm/research/robotic-systems/humanoids/rollin-justin) - Mobile humanoid robot developed by DLR with two torque-controlled arms and dexterous hands mounted on a wheeled platform.
- [Valkyrie (R5)](https://www.nasa.gov/technology/r5) - NASA's bipedal humanoid robot designed for disaster response and space exploration.

## Software Frameworks

### Robotics Middleware

- [Robot Operating System (ROS)](https://www.ros.org) - Open source middleware framework widely used in space robotics for development and ground testing.
- [Space ROS](https://space.ros.org) - Fork of ROS 2 that aims to align with the safety and reliability requirements of space missions.

### Flight & Ground Software

- [core Flight System (cFS)](https://cfs.gsfc.nasa.gov) - NASA's platform-independent and mission-independent flight software framework.
- [F´ (F-Prime)](https://fprime.jpl.nasa.gov) - Component-driven framework for spaceflight applications and embedded systems with limited resources.

- [Yamcs](https://yamcs.org) - Open source mission control framework for command and control of spacecraft, satellites, payloads, and ground equipment.

### Mission Planning

- [GMAT](https://gmat.atlassian.net/wiki/spaces/GW/overview) - General Mission Analysis Tool, NASA's open source space mission design tool for trajectory optimization and mission planning.
- [SPICE Toolkit](https://naif.jpl.nasa.gov/naif/toolkit.html) - NASA's observation geometry system used for space science mission planning and data analysis.

## Simulation Environments

### General Purpose

- [Gazebo](https://gazebosim.org) - Open source robotics simulator that provides accurate physics simulation, sensor models, and 3D visualization.
- [Isaac Sim](https://developer.nvidia.com/isaac-sim) - NVIDIA's robotics simulation platform built on Omniverse.
- [Project Chrono](https://projectchrono.org) - Open source multi-physics simulation engine handling rigid and flexible body dynamics, collision detection, and vehicle-terrain interaction.

### Space Robotics

- [DARTS](https://www-robotics.jpl.nasa.gov/how-we-do-it/facilities/the-darts-simulation-laboratory) - Dynamics Algorithms for Real-Time Simulation developed by JPL.
- [PANGU](https://pangu.software) - Planet and Asteroid Natural Scene Generation Utility developed by the University of Dundee for ESA.
- [Space Robotics Bench (SRB)](https://andrejorsula.github.io/space_robotics_bench) *(Disclosure: Created by the author of this list)* - Collection of environments and tasks for space robotics research built on NVIDIA Isaac Sim.
- [Space ROS Demos](https://github.com/space-ros/demos) - Collection of Space ROS simulation examples featuring Canadarm2, Curiosity rover, and lunar terrain environments.

### Spacecraft Dynamics

- [42](https://github.com/ericstoneking/42) - NASA Goddard's general-purpose spacecraft simulation environment.
- [Basilisk](https://avslab.github.io/basilisk) - Astrodynamics simulation framework developed at the University of Colorado Boulder.

- [Trick](https://github.com/nasa/trick) - NASA's simulation development framework that provides common simulation capabilities for rapid prototyping of space vehicle simulations.

## Verification & Validation

### Assurance Resources

- [Awesome Assured Autonomy](https://github.com/sylvesterkaczmarek/awesome-assured-autonomy) - Curated research, tools, benchmarks, standards, and open-source systems for assuring autonomous and learning-enabled systems.

### Terrestrial Analogue Sites

- [Atacama Desert](https://en.wikipedia.org/wiki/Atacama_Desert) - Chile: One of the driest places on Earth, used as a Mars analogue for testing rover autonomy and astrobiology experiments.
- [Devon Island](https://en.wikipedia.org/wiki/Devon_Island) - Canada: The largest uninhabited island on Earth, hosting the Haughton-Mars Project for testing rover operations.
- [Iceland](https://en.wikipedia.org/wiki/Iceland) - Volcanic island used extensively by NASA and ESA as a planetary analogue.
- [Lanzarote](https://en.wikipedia.org/wiki/Lanzarote) - Spain: Volcanic island in the Canary Islands used by ESA as an analogue site for lunar and planetary exploration testing.
- [Mount Etna](https://en.wikipedia.org/wiki/Mount_Etna) - Italy: Active volcano with fresh volcanic soils and lava flows, serving as a lunar and Martian analogue.

### Laboratory Facilities

- [ESA Orbital Robotics Laboratory](https://www.esa.int/Education/ESA_Academy_Experiments_programme/Orbital_Robotics_Laboratory) - Netherlands: Testbed at ESA's ESTEC featuring Europe's largest 2D free-floating platform with air-bearing systems that simulate microgravity.
- [JPL Mars Yard](https://www-robotics.jpl.nasa.gov/how-we-do-it/facilities/marsyard-iii) - USA: Outdoor test facility at JPL designed to emulate the Martian surface. It is used for testing rover mobility on terrain representative of Mars.
- [LUNA](https://luna-analog-facility.de/en) - Germany: ESA-DLR LUNA analogue facility at the European Astronaut Centre in Cologne. It features a large regolith testbed for testing lunar surface operations.
- [LunaLab](https://www.uni.lu/snt-en/facilities/lunalab) - Luxembourg: Moon analogue facility at the University of Luxembourg. It features an indoor basalt gravel area to simulate the lunar surface.
- [Spaceport Rostock](https://testingfor.space) - Germany: Testing facility at Rostock-Laage Airport featuring a test track for lunar and space vehicles and microgravity testing infrastructure for space research.
- [TRON](https://www.dlr.de/en/research-and-transfer/research-infrastructure/testbed-for-robotic-optical-navigation-tron) - Germany: Testbed for Robotic Optical Navigation at the DLR Institute of Space Systems in Bremen. A hardware-in-the-loop facility for validating optical navigation sensors.
- [Zero-G Lab](https://www.uni.lu/snt-en/facilities/zero-g-lab) - Luxembourg: Facility at the University of Luxembourg designed for testing 2D and 3D free-floating robotic systems in microgravity conditions.

### Runtime Verification

- [Copilot](https://github.com/Copilot-Language/copilot) - NASA's runtime verification framework that generates constant-time, constant-memory C99 monitors from high-level Haskell specifications.
- [OGMA](https://github.com/nasa/ogma) - NASA tool for generating safe runtime monitors for flight and robotic applications.

## Perception

- [Ames Stereo Pipeline (ASP)](https://github.com/NeoGeographyToolkit/StereoPipeline) - NASA's open source suite for generating digital terrain models, orthoimages, and 3D point clouds from satellite, rover, and aerial stereo imagery.
- [VICAR](https://github.com/NASA-AMMOS/VICAR) - Video Image Communication And Retrieval, JPL's open source image processing system developed since 1966.

## Navigation

### Planetary Navigation

- [Enhanced Autonomous Navigation (ENav)](https://doi.org/10.1109/TFR.2025.3636366) - Enhanced Navigation system used on NASA's Perseverance rover.
- [Terrain Relative Navigation (TRN)](https://www.nasa.gov/space-technology-mission-directorate/tdm/terrain-relative-navigation-trn) - NASA's Lander Vision System developed for Mars 2020.

### Orbital Navigation

- [dSGP4](https://github.com/esa/dSGP4) - ESA's differentiable SGP4 orbital propagation library reimplemented with PyTorch automatic differentiation support.
- [Orekit](https://www.orekit.org) - Open source low-level space dynamics library written in Java.

## Manipulation

### Motion Planning

- [MoveIt](https://moveit.ros.org) - Open source general-purpose motion planning framework built on top of ROS.
- [OMPL](https://ompl.kavrakilab.org) - Open Motion Planning Library, a collection of sampling-based motion planning algorithms.

### Dynamics & Control

- [Drake](https://drake.mit.edu) - Model-based design and verification toolbox for robotics developed at MIT and now maintained by Toyota Research Institute.
- [Pinocchio](https://github.com/stack-of-tasks/pinocchio) - Fast and flexible C++ library for rigid body dynamics algorithms.

## Human-Robot Interaction

- [METERON](https://www.esa.int/Enabling_Support/Space_Engineering_Technology/Automation_and_Robotics/METERON_Project) - Multi-purpose End-To-End Robotic Operation Network, an ESA project for teleoperation of robots on Earth from the ISS.

- [OpenMCT](https://nasa.github.io/openmct) - Open source mission control framework developed by NASA Ames.

## Robot Learning

- [Space Robotics Bench (SRB)](https://github.com/AndrejOrsula/space_robotics_bench) *(Disclosure: Created by the author of this list)* - Suite of GPU-accelerated environments for space robotics reinforcement learning built on NVIDIA Isaac Lab.

## Space Exploration

### Lunar

- [Astrobotic Peregrine](https://www.astrobotic.com/lunar-delivery/landers/peregrine-lander) - First mission under NASA's Commercial Lunar Payload Services program, launched in January 2024.
- [Blue Ghost](https://fireflyspace.com/blue-ghost) - Firefly Aerospace's lunar lander selected under NASA's CLPS program.
- [Chandrayaan-3](https://www.isro.gov.in/Chandrayaan3.html) - ISRO's lunar mission that successfully soft-landed the Vikram lander and Pragyan rover near the lunar south pole in 2023.
- [Chang'e Program](https://en.wikipedia.org/wiki/Chinese_Lunar_Exploration_Program) - China's lunar exploration program operated by CNSA.
- [Lunokhod Program](https://en.wikipedia.org/wiki/Lunokhod_programme) - Soviet robotic lunar rover program that deployed the first remote-controlled rovers on another world.
- [LUPEX](https://global.jaxa.jp/activity/pr/jaxas/no092/02.html) - Lunar Polar Exploration mission jointly developed by JAXA and ISRO.
- [Nova-C (Odysseus)](https://www.intuitivemachines.com/im-1) - Intuitive Machines' IM-1 lunar lander that became the first commercial spacecraft to soft-land on the Moon in February 2024.
- [SLIM](https://global.jaxa.jp/projects/sas/slim) - Smart Lander for Investigating Moon, JAXA's precision lunar landing demonstrator that touched down in January 2024.
- [VIPER](https://science.nasa.gov/mission/viper) - Volatiles Investigating Polar Exploration Rover, a NASA lunar rover designed to map water ice deposits at the Moon's south pole.

### Mars

- [ExoMars](https://www.esa.int/Science_Exploration/Human_and_Robotic_Exploration/Exploration/ExoMars) - ESA's mission to search for signs of past life on Mars.
- [Mars 2020](https://mars.nasa.gov/mars2020) - NASA mission that landed the Perseverance rover and Ingenuity helicopter in Jezero Crater in 2021.
- [Mars Exploration Rovers](https://science.nasa.gov/mission/mars-exploration-rovers-spirit-and-opportunity) - NASA's twin-rover mission that landed Spirit and Opportunity on Mars in 2004 to search for evidence of past water activity.
- [Mars Pathfinder](https://science.nasa.gov/mission/mars-pathfinder) - NASA's first rover mission to Mars, which landed in 1997.
- [Mars Science Laboratory](https://mars.nasa.gov/msl) - NASA mission that landed the Curiosity rover in Gale Crater in 2012.
- [Tianwen-1](https://en.wikipedia.org/wiki/Tianwen-1) - China's first Mars mission, which landed the Zhurong rover in Utopia Planitia in 2021.

### Saturn

- [Dragonfly](https://dragonfly.jhuapl.edu) - NASA rotorcraft lander planned for Saturn's moon Titan.

### Small Bodies

- [Hayabusa2](https://www.hayabusa2.jaxa.jp/en) - JAXA's asteroid sample-return mission to Ryugu.
- [MMX](https://www.mmx.jaxa.jp/en) - Martian Moons eXploration, JAXA's mission to return samples from Mars's moon Phobos.
- [OSIRIS-REx](https://science.nasa.gov/mission/osiris-rex) - NASA's asteroid sample-return mission to Bennu.
- [Rosetta](https://www.esa.int/Science_Exploration/Space_Science/Rosetta) - ESA's Rosetta spacecraft orbited comet 67P/Churyumov-Gerasimenko and deployed the Philae lander in November 2014, achieving the first-ever landing on a comet.
- [Tianwen-2](https://en.wikipedia.org/wiki/Tianwen-2) - CNSA mission launched in 2025 to collect samples from near-Earth asteroid Kamoʻoalewa and return them to Earth.

## Assembly & Servicing

### On-Orbit Servicing

- [ADRAS-J](https://astroscale.com/missions/adras-j) - Active Debris Removal by Astroscale-Japan, a JAXA-contracted mission launched in 2024.
- [ClearSpace-1](https://clearspace.today/missions/clearspace-1) - ESA-commissioned mission to remove a piece of space debris from orbit, planned as the first active debris removal mission.
- [Mission Extension Vehicle (MEV)](https://www.northropgrumman.com/space/space-logistics-services) - Northrop Grumman's satellite life-extension spacecraft.
- [Mission Robotic Vehicle (MRV)](https://en.wikipedia.org/wiki/Mission_Extension_Vehicle#Mission_Robotic_Vehicle) - Northrop Grumman's next-generation servicing spacecraft designed to perform hands-on satellite maintenance in GEO.
- [RSGS](https://www.darpa.mil/program/robotic-servicing-of-geosynchronous-satellites) - Robotic Servicing of Geosynchronous Satellites, a DARPA program to develop a robotic servicing vehicle for GEO satellites.

## Education

### Learning Resources

- [Awesome Space Autonomy](https://github.com/sylvesterkaczmarek/awesome-space-autonomy) - Curated research, flight demonstrations, software, tools, and guidance for autonomous spacecraft and space robots.

### Study Programmes

- [Erasmus Mundus — SpaceMaster](https://spacemaster.eu) - Joint European master's degree in space science and technology offered by a consortium of European universities.
- [University of Luxembourg — Master in Space Technologies and Business](https://www.uni.lu/fstm-en/study-programs/master-in-space-technologies-and-business) - A two-year program pairing space technology with space business.

## Demos

### Web

- [Eyes on the Solar System](https://eyes.nasa.gov/apps/solar-system) - NASA's real-time 3D visualization of the solar system.
- [JPL Open Source Rover (Homepage)](https://github.com/nasa-jpl/open-source-rover) - Simulated Mars rover that can be controlled through a simple teleoperation interface.
- [KeepTrack](https://app.keeptrack.space) - Open source web application for visualizing satellites and space debris in real time.
- [LeoLabs Visualization](https://platform.leolabs.space/visualization) - Interactive 3D visualization of tracked objects in low Earth orbit.
- [Mars Trek](https://trek.nasa.gov/mars) - NASA's web-based portal for exploring the surface of Mars using data from multiple missions.
- [Moon Trek](https://trek.nasa.gov/moon) - NASA's web-based portal for interactive exploration of the lunar surface.

## Datasets

### Assets

- [ESA Planetary Science Archive (PSA)](https://psa.esa.int/psa/#/pages/home) - ESA's central repository for data from all planetary science missions.
- [NASA-3D-Resources](https://github.com/nasa/NASA-3D-Resources) - Collection of copyright-free 3D models, textures, and images from NASA.

### Imagery & Terrain

- [HiRISE](https://www.uahirise.org) - High Resolution Imaging Science Experiment aboard NASA's Mars Reconnaissance Orbiter.
- [Lunar Reconnaissance Orbiter Camera (LROC)](https://www.lroc.asu.edu) - Camera system aboard NASA's LRO that has imaged the lunar surface at resolutions up to 50 cm/pixel.
- [Planetary Data System (PDS)](https://pds.nasa.gov) - NASA's archive of data from planetary missions.

### Spacecraft Pose & Proximity

- [SPARK](https://cvi2.uni.lu/spark-spades) - SPAcecraft Recognition leveraging Knowledge dataset from the University of Luxembourg.
- [SPEED+](https://zenodo.org/records/6327547) - Spacecraft Pose Estimation Dataset, providing synthetic and real images of satellites with ground truth 6-DOF pose labels.

## Competitions

### Robotic Challenges

- [ESA ESRIC Space Resources Challenge](https://src.esa.int) - ESA challenge focused on developing robotic technologies for lunar resource prospecting and in-situ resource utilization.
- [European Rover Challenge (ERC)](https://roverchallenge.eu) - Annual competition in planetary exploration where student teams design and test rovers.
- [University Rover Challenge (URC)](https://urc.marssociety.org) - Mars Society's annual competition held in the Utah desert.

## Organizations

### Governmental

- [ASI](https://www.asi.it/en) - Italy: Italian Space Agency.
- [CNES](https://cnes.fr/en) - France: Centre National d'Études Spatiales.
- [CNSA](https://www.cnsa.gov.cn) - China: China National Space Administration.
- [CSA](https://www.asc-csa.gc.ca/eng) - Canada: Canadian Space Agency.
- [DLR](https://www.dlr.de/en/rm) - Germany: German Aerospace Center, Institute of Robotics and Mechatronics.
- [ESA](https://www.esa.int) - Europe: European Space Agency.
- [ISRO](https://www.isro.gov.in) - India: Indian Space Research Organisation.
- [JAXA](https://global.jaxa.jp) - Japan: Japan Aerospace Exploration Agency.
- [KASA](https://www.kasa.go.kr/eng/index.do) - South Korea: Korea AeroSpace Administration.
- [NASA](https://www.nasa.gov) - USA: National Aeronautics and Space Administration.
- [NASA ARC](https://www.nasa.gov/ames) - USA: NASA Ames Research Center.
- [NASA GSFC](https://www.nasa.gov/goddard) - USA: NASA Goddard Space Flight Center.
- [NASA JPL](https://www.jpl.nasa.gov) - USA: NASA Jet Propulsion Laboratory.
- [NASA JSC](https://www.nasa.gov/johnson) - USA: NASA Johnson Space Center.
- [UKSA](https://www.gov.uk/government/organisations/uk-space-agency) - United Kingdom: UK Space Agency.

### Academic

- [AAU Space Robotics](https://spacerobotics.es.aau.dk) - Denmark: Aalborg University.
- [Space Robotics Group (SRG)](https://www.srg.mech.keio.ac.jp/en) - Japan: Keio University.
- [Space Robotics Lab (SRL)](https://astro.mech.tohoku.ac.jp/e/index.html) - Japan: Tohoku University.
- [Space Robotics Research Group (SpaceR)](https://www.spacer.lu) - Luxembourg: University of Luxembourg.
- [The Laboratory for Autonomous Systems in Exploration and Robotics (LASER)](https://usclaser.github.io) - USA: University of Southern California.

### Corporate

- [Astrobotic](https://www.astrobotic.com) - USA: Lunar logistics and delivery services.
- [Astroscale](https://astroscale.com) - Japan/UK: On-orbit servicing and debris removal.
- [ClearSpace](https://clearspace.today) - Switzerland: Space debris removal and in-orbit servicing.
- [GITAI](https://gitai.tech) - Japan/USA: Space robotics and labor automation.
- [Honeybee Robotics (Blue Origin)](https://www.blueorigin.com/exploration-systems) - USA: Spacecraft mechanisms and planetary drilling systems, now a subsidiary of Blue Origin.
- [Intuitive Machines](https://www.intuitivemachines.com) - USA: Lunar landers and space infrastructure.
- [ispace](https://ispace-inc.com) - Japan: Lunar exploration and resource development.
- [MDA](https://mda.space) - Canada: Canadarm, robotics, and satellite systems.
- [Motiv Space Systems](https://motivss.com) - USA: Robotic arms and actuators for space.
- [Northrop Grumman](https://www.northropgrumman.com/space) - USA: Satellite servicing and space logistics.
- [Redwire Space](https://redwirespace.com) - USA: In-space manufacturing and robotics.
- [Starfish Space](https://www.starfishspace.com) - USA: Satellite servicing and space sustainability.

## Recurring Events

### Conferences

- [ASTRA](https://www.esa.int/Enabling_Support/Space_Engineering_Technology/Automation_and_Robotics/Proceedings_of_ASTRA) - Advanced Space Technologies for Robotics and Automation, ESA's symposium on space robotics held biennially at ESTEC.
- [i-SAIRAS](https://www.esa.int/Enabling_Support/Space_Engineering_Technology/Automation_and_Robotics/i-SAIRAS) - International Symposium on Artificial Intelligence, Robotics and Automation in Space.
- [IAC](https://www.iafastro.org/events/iac) - International Astronautical Congress, the world's largest annual gathering of space professionals.
- [ICRA](https://www.ieee-ras.org/conferences-workshops/fully-sponsored/icra) - IEEE International Conference on Robotics and Automation.
- [IROS](https://www.ieee-ras.org/conferences-workshops/financially-co-sponsored/iros) - IEEE/RSJ International Conference on Intelligent Robots and Systems.
- [iSpaRo](https://isparo.space) - International Conference on Space Robotics.
- [SPAICE](https://spaice.esa.int) - ESA academic conference on AI in and for space.

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) before submitting a pull request.
