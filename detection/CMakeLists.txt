FIND_PACKAGE(OpenCV REQUIRED)
ADD_LIBRARY(harris_detector harris_detector.cpp)
TARGET_LINK_LIBRARIES(harris_detector ${OpenCV_LIBS})
ADD_LIBRARY(surf_detector surf_detector.cpp)
TARGET_LINK_LIBRARIES(surf_detector ${OpenCV_LIBS})
ADD_LIBRARY(sift_detector sift_detector.cpp)
TARGET_LINK_LIBRARIES(sift_detector ${OpenCV_LIBS})
