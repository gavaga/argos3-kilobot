add_library(kilobot_phototaxis SHARED kilobot_phototaxis.h kilobot_phototaxis.cpp)
target_link_libraries(kilobot_phototaxis
  argos3core_simulator
  argos3plugin_simulator_kilobot
  argos3plugin_simulator_genericrobot)
