obj-y				+= clock.o
obj-y				+= clock-dummy.o
obj-y				+= clock-generic.o
obj-y				+= clock-local2.o
obj-y				+= clock-pll.o
obj-y				+= clock-alpha-pll.o
obj-y				+= clock-rpm.o
obj-y				+= clock-voter.o

obj-$(CONFIG_MSM_CLK_CONTROLLER_V2)	+= msm-clock-controller.o

obj-$(CONFIG_DEBUG_FS)		+= clock-debug.o

# MSM 8996
obj-$(CONFIG_ARCH_MSM8996)	+= clock-gcc-8996.o
obj-$(CONFIG_ARCH_MSM8996)	+= clock-mmss-8996.o
obj-$(CONFIG_ARCH_MSM8996)	+= clock-cpu-8996.o

# MDMCALIFORNIUM
obj-$(CONFIG_ARCH_MDMCALIFORNIUM)	+= clock-gcc-californium.o

# MDMFERMIUM
obj-$(CONFIG_ARCH_MDMFERMIUM)	+=clock-gcc-mdmfermium.o

# ACPU clock
obj-$(CONFIG_ARCH_MDM9640)      += clock-a7.o
obj-$(CONFIG_ARCH_MDMCALIFORNIUM)	+= clock-a7.o
obj-$(CONFIG_ARCH_MDMFERMIUM)	+= clock-a7.o
obj-$(CONFIG_ARCH_MSM8916)	+= clock-a7.o
obj-$(CONFIG_ARCH_MSM8916)	+= clock-cpu-8939.o
obj-$(CONFIG_ARCH_MSM8916)	+= clock-gcc-8952.o
obj-$(CONFIG_ARCH_MSM8916)	+= clock-gcc-titanium.o


obj-y				+= gdsc.o
obj-y				+= mdss/
