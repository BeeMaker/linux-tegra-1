GCOV_PROFILE := y
ccflags-y += -Invidia/nvhost/drivers/video/tegra/host
ccflags-y += -Idrivers/video/tegra/host
ccflags-y += -Idrivers/media/platform/tegra/

ifdef CONFIG_TEGRA_CAMERA_PLATFORM
obj-y += tegra_camera_platform.o
obj-y += tegra_camera_dev_mfi.o
endif
