project('sml','cpp', 
        license : 'boost',
        version: run_command('cat', files('version.txt')).stdout().strip(),
        default_options : ['cpp_std=c++14']
      )

libsml_inc = include_directories('include')
libsml_dep = declare_dependency(include_directories: libsml_inc)
