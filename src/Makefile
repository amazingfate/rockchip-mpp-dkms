# SPDX-License-Identifier: (GPL-2.0+ OR MIT)

EXTRA_CFLAGS += -DCONFIG_ROCKCHIP_MPP_PROC_FS

EXTRA_CFLAGS += -DCONFIG_ROCKCHIP_MPP_RKVENC2

rk_vcodec-objs := mpp_service.o mpp_common.o mpp_iommu.o

rk_vcodec-$(CONFIG_ROCKCHIP_MPP_RKVENC2) += mpp_rkvenc2.o

obj-$(CONFIG_ROCKCHIP_MPP_SERVICE) += rk_vcodec.o
