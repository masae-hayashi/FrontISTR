###############################################################################
# Copyright (c) 2019 FrontISTR Commons
# This software is released under the MIT License, see License.txt
###############################################################################
cmake_minimum_required(VERSION 2.8.11)

list(APPEND hecmw_SOURCES
  ${CMAKE_CURRENT_LIST_DIR}/hecmw_precond_11.f90
  ${CMAKE_CURRENT_LIST_DIR}/hecmw_precond_DIAG_11.f90
  ${CMAKE_CURRENT_LIST_DIR}/hecmw_precond_SSOR_11.f90
)

