liri_add_executable(useraccount
    SOURCES
        main.cpp
        useraccount.qml
    RESOURCES
        resources.qrc
    LIBRARIES
        Qt5::Core
        Qt5::Gui
        Qt5::Qml
    NO_TARGET_INSTALLATION
)

liri_finalize_executable(useraccount)
