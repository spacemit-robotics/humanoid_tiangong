cmake_minimum_required(VERSION 3.16)
project(humanoid_tiangong)

install(PROGRAMS
    scripts/run_driver_tiangong.sh
    scripts/run_control_tiangong.sh
    scripts/run_hmi_tiangong.sh
    scripts/run_sim2sim_tiangong.sh
    scripts/download_models_tiangong.sh
    DESTINATION bin
)
