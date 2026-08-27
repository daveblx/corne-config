cmake_minimum_required(VERSION 3.20.0)

if(CONFIG_ZMK_DISPLAY_STATUS_SCREEN_CUSTOM)
    target_sources(app PRIVATE src/custom_status_screen.c src/neuromancer_img.c)
endif()
