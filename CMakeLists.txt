if (MSVC)
 cmake_minimum_required(VERSION 3.26)
else()
 cmake_minimum_required(VERSION 3.15)
endif()
project(libjson)
set(SOURCES
  src/cjson.c
  src/cjsonBoolNull.c
  src/cjsonObject.c
  src/cjsonSerializer.c
  src/cjsonArray.c
  src/cjsonNumber.c
  src/cjsonParser.c
  src/cjsonString.c
  )
