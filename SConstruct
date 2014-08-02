env = Environment(
    CC='g++',
    CCFLAGS='-std=c++11 -pedantic -Wall -Wextra -Wno-switch -O3',
    LIBS=['SDL2', 'GL', 'GLEW']
)

source = Glob('src/*.cpp')
source += ['src/lib/tinyobjloader/tiny_obj_loader.cc']

program = env.Program(target='bin/arcball', source=source);
