# Implementing BDI Continual Temporal Planning for Robotic Agents

### Alex Zanetti1, Devis Dal Moro, Redi Vreto, Marco Robol, Marco Roveri and Paolo Giorgini

| ![https://ieee-iros.org/](https://ieee-iros.org/wp-content/uploads/2016/05/IROS-LOGO.svg) | [IROS 2023](https://ieee-iros.org/) - The 2023 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS 2023) - October 1–5, 2023 - Huntington Place in Detroit, Michigan, USA. |
|---                                                                        |---                                                        |


Making autonomous agents effective in real-life applications requires the ability to decide at run-time and a high degree of adaptability to unpredictable and uncontrollable events. Reacting to events is still a fundamental ability for an agent, but it has to be boosted up with proactive behaviors that allow the agent to explore alternatives and decide at run-time for optimal solutions. This calls for a continuous planning as part of the deliberation process that makes an agent able to reconsider plans on the base of temporal constraints and changes of the environment. Online planning literature offers several approaches used to select the next action on the base of a partial exploration of the solution space. In this paper, we propose a BDI continuous temporal planning framework, where interleave planning and execution loop is used to integrate online planning with the BDI control-loop. The framework has been implemented with the ROS2 robotic framework and planning algorithms offered by JavaFF.

- Video [https://github.com/RTI-BDI/ijcai2022/blob/main/IJCAI-Video_Presentation.mp4](https://github.com/RTI-BDI/iros2023/raw/main/on_moving_SR_400_LS_800_DC_4.mkv)

- Source code
  - CJFF can be found at https://github.com/RTI-BDI/JavaFF.
  - The extended ROS2-BDI framework is available at https://github.com/RTI-BDI/ROS2-BDI-ONLINE/tree/ojff.
  - The adopted ROS2 planning system, a revised version of PlanSys2, is available at https://github.com/RTI-BDI/ros2_planning_system
