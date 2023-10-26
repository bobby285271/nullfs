project('nullfs', 'cpp', version : '1.0.0')

fuse_dep = dependency('fuse3')

project_target = executable(
  meson.project_name(),
  [ 'nullfs.cpp' ],
  dependencies: [ fuse_dep ],
  install : true,
)
