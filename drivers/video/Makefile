# SPDX-License-Identifier: GPL-2.0

obj-$(CONFIG_APERTURE_HELPERS)    += aperture.o
obj-$(CONFIG_VGASTATE)            += vgastate.o
obj-$(CONFIG_HDMI)                += hdmi.o

obj-$(CONFIG_VT)		  += console/
obj-$(CONFIG_FB_STI)		  += console/
obj-$(CONFIG_LOGO)		  += logo/
obj-y				  += backlight/

obj-y				  += fbdev/
obj-$(CONFIG_DVI_TFP410)	  += tfp410.o
obj-$(CONFIG_SN65DSI83)		  += sn65dsi83.o
obj-$(CONFIG_TC358778)		  += tc358778.o
obj-$(CONFIG_LT8912)		  += lt8912.o

obj-$(CONFIG_VIDEOMODE_HELPERS) += display_timing.o videomode.o
ifeq ($(CONFIG_OF),y)
obj-$(CONFIG_VIDEOMODE_HELPERS) += of_display_timing.o of_videomode.o
endif
