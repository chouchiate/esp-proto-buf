set(component_srcs main.c amessage.pb-c.c)

idf_component_register(SRCS "main.c" "amessage.pb-c.c" "${component_srcs}"
                       INCLUDE_DIRS ".")



