cxx_library(
  name = 'frozen',
  header_namespace = '',
  exported_headers = [
    'frozen.h',
  ],
  srcs = [
    'frozen.c',
  ],
  visibility = [
    'PUBLIC',
  ],
)

cxx_binary(
  name = 'unit-test', 
  srcs = [
    'unit_test.c',
  ],
  deps = [
    ':frozen',
  ],
)

