#
# Makefile for SPEAr13XX machine series
#
obj-y				+= db9000fb_lcd.o
obj-$(CONFIG_SMP)		+= headsmp.o platsmp.o
obj-$(CONFIG_HOTPLUG_CPU)	+= hotplug.o

obj-$(CONFIG_ARCH_SPEAR13XX)	+= spear13xx.o
obj-$(CONFIG_SUSPEND)		+= pm.o wakeup.o sleep_1340.o sleep_1310.o
obj-$(CONFIG_MACH_SPEAR1310)	+= spear1310.o
obj-$(CONFIG_MACH_SPEAR1340)	+= spear1340.o
obj-$(CONFIG_SPEAR13XX_PCI)	+= pcie.o
