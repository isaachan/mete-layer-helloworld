CMAKE_MINIMUM_REQUIRED(VERSION 3.16)

PROJECT(HelloWorldCM C)

ADD_EXECUTABLE(HelloWorldCM
	src/helloworld.c
)

INSTALL(TARGETS HelloWorldCM DESTINATION ${CMAKE_INSTALL_PREFIX}/bin)
