add_renderpass(tutorialPass)

target_sources(tutorialPass PRIVATE
    tutorialPass.cpp
    tutorialPass.h
)

target_source_group(tutorialPass "RenderPasses")
