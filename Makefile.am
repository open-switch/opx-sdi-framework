ACLOCAL_AMFLAGS=-I m4

SUBDIRS = inc

#The sdi-framework library
lib_LTLIBRARIES = libopx_sdi_framework.la

libopx_sdi_framework_la_SOURCES = src/sdi_driver_framework.c src/sdi_bus_framework.c \
                                    src/sdi_resource_framework.c src/sdi_pin_bus_api.c src/sdi_i2c_bus_api.c \
                                    src/sdi_pin_group_bus_api.c src/sdi_bus_api.c\
                                    src/sdi_io_port_api.c src/sdi_smartfusion_io_bus_api.c

libopx_sdi_framework_la_LDFLAGS = -ldl -lopx_common -lopx_logging -lpthread -lrt -version-info 1:1:0
libopx_sdi_framework_la_CFLAGS =  -I$(top_srcdir)/inc/opx  -I$(includedir)/opx  

