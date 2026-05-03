# Copyright 2026 Arm Limited and/or its affiliates <open-source-office@arm.com>
# SPDX-License-Identifier: Apache-2.0

add_library(cmsis_6_core INTERFACE)
add_library(CMSIS_6::Core ALIAS cmsis_6_core)

target_include_directories(cmsis_6_core
  INTERFACE
    ${CMAKE_CURRENT_LIST_DIR}/Include
)
