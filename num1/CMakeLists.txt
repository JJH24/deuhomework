INCLUDE_DIRECTORIES (lib)

ADD_EXECUTABLE ( main main3.c)
ADD_LIBRARY ( _fp_operation STATIC lib/main.c lib/lib_main.h)
TARGET_LINK_LIBRARIES ( main PUBLIC _fp_operation ) 
