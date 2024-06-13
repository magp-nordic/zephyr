# Copyright (c) 2024 Nordic Semiconductor ASA
# SPDX-License-Identifier: Apache-2.0

if(CONFIG_NRFE)
    zephyr_library()

    zephyr_include_directories(${ZEPHYR_CURRENT_MODULE_DIR}/nrfe)

endif()
