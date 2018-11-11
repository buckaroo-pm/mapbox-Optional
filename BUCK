prebuilt_cxx_library(
  name = 'optional', 
  header_namespace = '', 
  header_only = True, 
  exported_headers = [
    'optional.hpp', 
  ], 
  licenses = [
    'LICENSE', 
  ], 
  visibility = [
    'PUBLIC', 
  ], 
)

cxx_binary(
  name = 'test-optional', 
  srcs = [
    'test_optional.cpp', 
  ], 
  deps = [
    ':optional', 
  ], 
)

cxx_binary(
  name = 'test-type-traits', 
  srcs = [
    'test_type_traits.cpp', 
  ], 
  deps = [
    ':optional', 
  ], 
)
