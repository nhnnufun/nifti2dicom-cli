if(UNIX AND NOT APPLE)
    install(FILES qnifti2dicom.desktop DESTINATION share/applications)
    add_subdirectory(icons)
endif()
