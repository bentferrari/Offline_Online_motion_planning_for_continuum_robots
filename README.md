# Offline-Online-motion-planning-for-continuum-robots
This is the open-source code for submission of Mechanism and Machine Theory Journal.
The motion planner is divided into two parts: 
  1. Offline_planner 2. Online_replanner
In the offline_planner folder, we have two sub-folders:
    1.1 final_configuration_planning and 1.2 insertion_planning.
Tasks:
1. Find the final configuration in an environment→
   Run \offline_planner\final_configuration_planning\shape_optimization.m
3. Find the insertion motions in an environment→
   Run \offline_planner\insertion_planning\insertion_planner.m
   To see the demo, you can run \offline_planner\insertion_planning\plot_insertion.m
4. Online replanning with moving obstacles→
   Run \online_replanner\clf_cbf_qp_main.m