add_executable(test test.cc)
target_link_libraries (test ${CRAB_LIBS})

install(TARGETS test
  RUNTIME DESTINATION tests/cfg
  )

