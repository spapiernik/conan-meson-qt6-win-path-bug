project(
  'my_qt6_app',
  'cpp',
  default_options: ['default_library=static', 'cpp_std=c++20']
)

qt6_dep = dependency('qt6', modules: ['Core', 'Widgets'])

executable(
  'my_qt6_app',
  'main.cpp',
  dependencies: [qt6_dep],
)
