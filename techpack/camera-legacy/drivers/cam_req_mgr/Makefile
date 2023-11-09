ccflags-y += -I$(srctree)/techpack/camera-legacy/drivers/cam_core/
ccflags-y += -I$(srctree)/techpack/camera-legacy/drivers/cam_req_mgr
ccflags-y += -I$(srctree)/techpack/camera-legacy/drivers/cam_smmu/
ccflags-y += -I$(srctree)/techpack/camera-legacy/drivers/cam_utils

obj-$(CONFIG_LEGACY_CAMERA) += cam_req_mgr_core.o\
				cam_req_mgr_dev.o \
				cam_req_mgr_util.o \
				cam_req_mgr_workq.o \
				cam_mem_mgr.o \
				cam_req_mgr_timer.o \
				cam_req_mgr_debug.o
