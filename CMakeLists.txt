cmake_minimum_required(VERSION 3.10)

set(EXE atool)
project(${EXE})


add_executable(${EXE} ohgodatool.c ohgodatool-args.c ohgodatool-utils.c)

