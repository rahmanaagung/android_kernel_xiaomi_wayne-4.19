# SPDX-License-Identifier: GPL-2.0-only
ccflags-y += -Idrivers/media/platform/msm/camera_v2-oss
ccflags-y += -Idrivers/media/platform/msm/camera_v2-oss/common
ccflags-y += -Idrivers/media/platform/msm/camera_v2-oss/sensor/io
ifeq ($(CONFIG_MSM_ISP_V1),y)
obj-$(CONFIG_MSM_CSID) += msm_ispif_32.o
else
obj-$(CONFIG_MSM_CSID) += msm_ispif.o
endif
