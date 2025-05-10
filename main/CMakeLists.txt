idf_component_register(
                SRCS "esp-alarm-clock.cpp"
                INCLUDE_DIRS ""
                
                PRIV_REQUIRES esp_partition esp_psram esp_event esp_http_client esp_netif esp_wifi
                PRIV_REQUIRES spi_flash
                PRIV_REQUIRES esp-tls nvs_flash esp_timer esp_pm 
                PRIV_REQUIRES sdmmc esp_driver_sdmmc fatfs
                       
    )
