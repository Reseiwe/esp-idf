idf_component_register(SRCS "transport.c"
                            "transport_ssl.c"
                            "transport_tcp.c"
                            "transport_ws.c"
                            "transport_utils.c"
                            "transport_strcasestr.c"
                    INCLUDE_DIRS include
                    REQUIRES lwip esp-tls)