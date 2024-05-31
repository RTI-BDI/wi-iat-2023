# Implementing BDI Continual Temporal Planning for Robotic Agents

### Alex Zanetti, Devis Dal Moro, Redi Vreto, Marco Robol, Marco Roveri and Paolo Giorgini

| ![https://www.wi-iat.com/](https://www.wi-iat.com/wi-iat2023/images/wi-iat-logo.png) | [WI-IAT 2023](https://www.wi-iat.com/wi-iat2023/) - The 22nd IEEE/WIC International Conference on Web Intelligence and Intelligent Agent Technology (WI-IAT 2023) - October 26-29, 2023 - Venice, Italy |
|---                                                                        |---                                                        |


Making autonomous agents effective in real-life applications requires the ability to decide at run-time and a high degree of adaptability to unpredictable and uncontrollable events. Reacting to events is still a fundamental ability for an agent, but it has to be boosted up with proactive behaviors that allow the agent to explore alternatives and decide at run-time for optimal solutions. This calls for a continuous planning as part of the deliberation process that makes an agent able to reconsider plans on the base of temporal constraints and changes of the environment. Online planning literature offers several approaches used to select the next action on the base of a partial exploration of the solution space. In this paper, we propose a BDI continuous temporal planning framework, where interleave planning and execution loop is used to integrate online planning with the BDI control-loop. The framework has been implemented with the ROS2 robotic framework and planning algorithms offered by JavaFF.

- Video [https://github.com/RTI-BDI/iros2023/raw/main/on_moving_SR_400_LS_800_DC_4.mkv](https://github.com/RTI-BDI/wi-iat-2023/blob/main/on_moving_SR_400_LS_800_DC_4.mkv)

- Source code
  - CJFF can be found at https://github.com/RTI-BDI/JavaFF.
  - The extended ROS2-BDI framework is available at https://github.com/RTI-BDI/ROS2-BDI-ONLINE/tree/ojff.
  - The adopted ROS2 planning system, a revised version of PlanSys2, is available at https://github.com/RTI-BDI/ros2_planning_system
  - The implementation of the validation scenario based on Webots is available at https://github.com/RTI-BDI/Redi-Webots-scenarios

- How to run
  - Docker and building instructions at https://github.com/RTI-BDI/ros2bdi_build_workspace
    - Branch humble https://github.com/RTI-BDI/ros2bdi_build_workspace/tree/humble
    - Branch humble-online https://github.com/RTI-BDI/ros2bdi_build_workspace/tree/humble-online
