idf_component_register(
                SRCS "esp-alarm-clock.cpp"
                INCLUDE_DIRS ""
                
                PRIV_REQUIRES esp_psram 
                PRIV_REQUIRES esp_http_client esp_netif esp_wifi esp-tls
                PRIV_REQUIRES spi_flash nvs_flash esp_partition
                PRIV_REQUIRES esp_timer esp_event
                PRIV_REQUIRES esp_pm 
                PRIV_REQUIRES sdmmc esp_driver_sdmmc fatfs
                       
    )
