# SPDX-License-Identifier: GPL-2.0
agpgart-y := backend.o generic.o isoch.o

ifeq ($(CONFIG_DRM_LEGACY),y)
agpgart-$(CONFIG_COMPAT)	+= compat_ioctl.o
agpgart-y			+= frontend.o
endif


obj-$(CONFIG_AGP)		+= agpgart.o
obj-$(CONFIG_AGP_ALI)		+= ali-agp.o
obj-$(CONFIG_AGP_ATI)		+= ati-agp.o
obj-$(CONFIG_AGP_AMD)		+= amd-k7-agp.o
obj-$(CONFIG_AGP_AMD64)		+= amd64-agp.o
obj-$(CONFIG_AGP_ALPHA_CORE)	+= alpha-agp.o
obj-$(CONFIG_AGP_EFFICEON)	+= efficeon-agp.o
obj-$(CONFIG_AGP_PARISC)	+= parisc-agp.o
obj-$(CONFIG_AGP_INTEL)		+= intel-agp.o
obj-$(CONFIG_INTEL_GTT)		+= intel-gtt.o
obj-$(CONFIG_AGP_NVIDIA)	+= nvidia-agp.o
obj-$(CONFIG_AGP_SIS)		+= sis-agp.o
obj-$(CONFIG_AGP_SWORKS)	+= sworks-agp.o
obj-$(CONFIG_AGP_UNINORTH)	+= uninorth-agp.o
obj-$(CONFIG_AGP_VIA)		+= via-agp.o
