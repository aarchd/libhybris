hooks_sources = [
  'atexit.cpp',
]

hooks_lib = static_library(
  'hybris-hooks',
  hooks_sources,
  cpp_args: ['-fvisibility=hidden'],
  include_directories: include_directories('..'),
)
