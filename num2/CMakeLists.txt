INCLUDE_DIRECTORIES (lib)

ADD_EXCUTABLE ( main main33.c)
ADD_LIBRARY ( _fp_operation STATIC lib/main.c lib/lib_main.h)
TARGET_LINK_LIBRARIES ( main PUBLEC _fp_operation) 
