
ifneq ($(CONFIG_LTO),)
# Increase frame size to 3136 because of 'sha3_256_hmac' exceed stack size
ccflags-y += -Wframe-larger-than=3136
endif

obj-$(CONFIG_ONEWIRE_GPIO) += onewire_gpio.o
obj-$(CONFIG_BATT_VERIFY_BY_DS28E16) += onewire_gpio.o ucl_sha3.o sha384_software.o ds28e16.o
