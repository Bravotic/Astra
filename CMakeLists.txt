cmake_minimum_required(VERSION 3.5)


set(FILES 
	)

set(HEADERS
	)

project(Astra)

add_executable(Astra ${FILES} ${HEADERS})

target_include_directories(Astra PUBLIC include/)

