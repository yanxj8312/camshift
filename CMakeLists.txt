
CMAKE_MINIMUM_REQUIRED(VERSION 2.8) 

project( main  )

FIND_PACKAGE( OpenCV REQUIRED )		

ADD_EXECUTABLE( main main.cpp )		

TARGET_LINK_LIBRARIES( main  ${OpenCV_LIBS} )	
