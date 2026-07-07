target_sources(rosnehook PRIVATE
	"${CMAKE_CURRENT_LIST_DIR}/astar.h"
	"${CMAKE_CURRENT_LIST_DIR}/CNavFile.h"
	"${CMAKE_CURRENT_LIST_DIR}/nav.h")

target_include_directories(rosnehook PRIVATE "${CMAKE_CURRENT_LIST_DIR}")
