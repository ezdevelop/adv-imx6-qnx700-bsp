
EXTRA_SRCVPATH += $(PROJECT_ROOT)/../codecs/sgtl5000/
EXTRA_INCVPATH += $(PRODUCT_ROOT)/../codecs/sgtl5000/

SDMA_LIB=dma-sdma-imx6x
LIBS_mx += $(SDMA_LIB)

include ../../../../common.mk

#weilun@adv - begin
include ../../../../../../../../adv.mk
ifeq ($(CONFIG_ADV_BOARD), rom7420)
CCFLAGS += -DCONFIG_MACH_MX6Q_ROM_7420
endif
ifeq ($(CONFIG_ADV_BOARD), rom5420)
CCFLAGS += -DCONFIG_MACH_MX6Q_ROM_5420
endif
ifeq ($(CONFIG_ADV_BOARD), rsb4410)
CCFLAGS += -DCONFIG_MACH_MX6Q_RSB_4410
endif
ifeq ($(CONFIG_ADV_BOARD), dmsba16)
CCFLAGS += -DCONFIG_MACH_MX6Q_DMS_BA16
endif
#weilun@adv - begin
