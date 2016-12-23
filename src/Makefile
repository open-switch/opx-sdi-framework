LIBRARIES+= sdi_framework
sdi_framework_SRCS=sdi_driver_framework.c sdi_bus_framework.c
sdi_framework_SRCS+=sdi_resource_framework.c
sdi_framework_SRCS+=sdi_i2c_bus_api.c sdi_pin_bus_api.c
sdi_framework_SRCS+=sdi_pin_group_bus_api.c
sdi_framework_SRCS+=sdi_bus_api.c
sdi_framework_SRCS+=sdi_io_port_api.c
sdi_framework_SRCS+=sdi_smartfusion_io_bus_api.c

sdi_framework_LDFLAGS= -ldl -levent_log -ldn_common -z defs
sdi_framework_CFLAGS= -Wall -Werror

include ${MAKE_INC}/workspace.mak
