INCLUDE_DIRECTORIES( ${LIBZIP_INCLUDE_DIR} )

SET(TARGET_SRC 
    ReaderWriterWorldWind.cpp)
    
SET(TARGET_H WorldWindOptions)
	
SET(LIB_PUBLIC_HEADERS ${TARGET_H} )
SET(TARGET_LIBRARIES_VARS LIBZIP_LIBRARY )

SETUP_PLUGIN(osgearth_worldwind)

