cmake_minimum_required(VERSION 3.5)


set(FILES 
	)

set(HEADERS
	)

project(Astra)

add_executable(crow src/crowlang.c ${FILES} ${HEADERS})

target_include_directories(crow PUBLIC include/)

