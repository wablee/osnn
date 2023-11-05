add_library (
    osnn
    dummy.h
    dummy.cpp
)

install (TARGETS osnn DESTINATION bin)
install (FILES dummy.h DESTINATION include)
