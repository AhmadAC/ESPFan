idf_component_register(SRCS "main.cpp" 
                            # Uncomment the files below as you create them in your repository!
                            # "ir_codes.cpp"
                            # "ir_uart.cpp"
                            # "dht_sensor.cpp"
                            # "automation.cpp"
                            # "web_server.cpp"
                            # "wifi_manager.cpp"
                            # "system_utils.cpp"
                       INCLUDE_DIRS "."
                       REQUIRES nvs_flash esp_wifi esp_http_server json driver esp_netif mdns esp_timer lwip)