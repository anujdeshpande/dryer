idf_component_register(SRCS "main.c" "file_server.c" "mount.c"
                    INCLUDE_DIRS "."
                    EMBED_FILES "favicon.ico" "upload_script.html"
                    REQUIRES console cmd_system esp_event fatfs esp_netif nvs_flash spiffs esp_http_server )
