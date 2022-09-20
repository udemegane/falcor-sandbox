add_falcor_executable(SandBoxProject)

target_sources(SandBoxProject PRIVATE
    SandBoxProject.cpp
    SandBoxProject.h
)

target_copy_shaders(SandBoxProject Sand/MyFirstProject)

target_source_group(SandBoxProject "Samples")
