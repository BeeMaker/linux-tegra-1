#
# Makefile for the usb common parts.
#

obj-$(CONFIG_USB_COMMON)	  += usb-common.o
usb-common-y			  += common.o
usb-common-$(CONFIG_USB_LED_TRIG) += led.o

obj-$(CONFIG_USB_ULPI_BUS)	+= ulpi.o
ifeq ($(CONFIG_USB_OTG),y)
usbotg-y		:= usb-otg.o usb-otg-fsm.o
obj-$(CONFIG_USB_OTG_CORE)	+= usbotg.o
endif
