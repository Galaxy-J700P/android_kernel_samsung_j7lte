#
# Makefile for the QCOM spcific video device drivers
# based on V4L2.
#

obj-$(CONFIG_MSM_VIDC_V4L2)     += vidc/
obj-y += broadcast/
obj-$(CONFIG_DVB_MPQ) += dvb/
ifeq ($(CONFIG_SEC_J7_PROJECT),y)
obj-$(CONFIG_MSMB_CAMERA) += camera_v2_j7lte/
else
obj-$(CONFIG_MSMB_CAMERA) += camera_v2/
endif
obj-$(CONFIG_MSM_VPU) += vpu/
