ccflags-y += -I$(srctree)/techpack/camera-legacy/drivers/cam_utils
ccflags-y += -I$(srctree)/techpack/camera-legacy/drivers/cam_req_mgr
ccflags-y += -I$(srctree)/techpack/camera-legacy/drivers/cam_core
ccflags-y += -I$(srctree)/techpack/camera-legacy/drivers/cam_cpas/include
ccflags-y += -I$(srctree)/techpack/camera-legacy/drivers/cam_cpas/cpas_top
ccflags-y += -I$(srctree)/techpack/camera-legacy/drivers/cam_cpas/camss_top

obj-$(CONFIG_LEGACY_CAMERA) += cpas_top/
obj-$(CONFIG_LEGACY_CAMERA) += camss_top/
obj-$(CONFIG_LEGACY_CAMERA) += cam_cpas_soc.o cam_cpas_intf.o cam_cpas_hw.o