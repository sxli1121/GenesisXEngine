cmake_minimum_required(VERSION 3.30 FATAL_ERROR)

project(GenesisX)

add_executable(WindowsPlayer platforms/windows/windows_player.h
                             platforms/windows/windows_player.cpp)