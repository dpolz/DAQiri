add_library(DAQIRILIB_FILES STATIC)

target_sources(DAQIRILIB_FILES PUBLIC
        ${DAQIRILIB_DIR}/DAQiriEthernet.c
        )

target_include_directories(DAQIRILIB_FILES PUBLIC
        ${DAQIRILIB_DIR}
        )