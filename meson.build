project('prboom-plus', 'C')


cmake = import('cmake') # prboom-plus uses CMake, and so do several deps

sdl2_base = cmake.subproject('sdl2')
sdl2_net = cmake.subproject('sdl2-net')
sdl2_image = cmake.subproject('sdl2-image')
sdl2_mixer = cmake.subproject('sdl2-mixer')

libsdl2 = sdl2_base.dependency('SDL2')
libsdl2mixer = sdl2_mixer.dependency('SDL2_mixer')
libsdl2image = sdl2_image.dependency('SDL2_image')
libsdl2net = sdl2_image.dependency('SDL2_net')