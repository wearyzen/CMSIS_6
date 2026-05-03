# Copyright 2026 Arm Limited and/or its affiliates <open-source-office@arm.com>
# SPDX-License-Identifier: Apache-2.0

add_subdirectory(Core)

target_link_libraries(cmsis_6 INTERFACE CMSIS_6::Core)
