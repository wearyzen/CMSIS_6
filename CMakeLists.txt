# Copyright 2026 Arm Limited and/or its affiliates <open-source-office@arm.com>
# SPDX-License-Identifier: Apache-2.0

cmake_minimum_required(VERSION 3.16)

# Header/interface-only CMake package; consumers enable the languages they use.
project(CMSIS_6 LANGUAGES NONE)

add_library(cmsis_6 INTERFACE)
add_library(CMSIS_6::CMSIS ALIAS cmsis_6)

add_subdirectory(CMSIS)
