set(srcs "test_app_main.c"
         "test_flash_encryption.c")

idf_component_register(SRCS ${srcs}
                       WHOLE_ARCHIVE)
