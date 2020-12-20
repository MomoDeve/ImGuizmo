cmake_minimum_required(VERSION 3.2)
project(ImGuizmo)

set(SOURCE_FILES 
	"ImCurveEdit.cpp"
	"ImGradient.cpp"
	"ImGuizmo.cpp"
	"ImSequencer.cpp"
)
set(HEADER_FILES 
   "ImCurveEdit.h"
	"ImGradient.h"
	"ImGuizmo.h"
	"ImSequencer.h"
   "ImZoomSlider.h"
)

add_library(ImGuizmo STATIC ${SOURCE_FILES} ${HEADER_FILES})
include_directories(${CMAKE_CURRENT_SOURCE_DIR})
