project('meson-boilerplate', 'c', version : '1.1.0')

# includes
include = include_directories('include')
priv_includes = [include]
priv_sources = ['source/main.c']

# build the executable
exe = executable('boilerplate', [priv_sources],
        include_directories : priv_includes)

