CFLAGS_devfreq_trace.o		:= -I$(src)

obj-$(CONFIG_PM_DEVFREQ)	+= devfreq.o
obj-$(CONFIG_PM_DEVFREQ)	+= devfreq_trace.o
obj-$(CONFIG_DEVFREQ_GOV_SIMPLE_ONDEMAND)	+= governor_simpleondemand.o
obj-$(CONFIG_DEVFREQ_GOV_PERFORMANCE)	+= governor_performance.o
obj-$(CONFIG_DEVFREQ_GOV_POWERSAVE)	+= governor_powersave.o
obj-$(CONFIG_DEVFREQ_GOV_USERSPACE)	+= governor_userspace.o
obj-$(CONFIG_DEVFREQ_GOV_CPUFREQ)	+= governor_cpufreq.o
obj-$(CONFIG_DEVFREQ_GOV_MSM_ADRENO_TZ)	+= governor_msm_adreno_tz.o
obj-$(CONFIG_DEVFREQ_GOV_MSM_CPUFREQ)	+= governor_msm_cpufreq.o
obj-$(CONFIG_ARCH_MSM_KRAIT)		+= krait-l2pm.o
obj-$(CONFIG_MSM_BIMC_BWMON)		+= bimc-bwmon.o
obj-$(CONFIG_ARMBW_HWMON)		+= armbw-pm.o
obj-$(CONFIG_DEVFREQ_GOV_MSM_BW_HWMON)	+= governor_bw_hwmon.o
obj-$(CONFIG_DEVFREQ_GOV_MSM_CACHE_HWMON)	+= governor_cache_hwmon.o
obj-$(CONFIG_DEVFREQ_GOV_MSM_GPUBW_MON)	+= governor_gpubw_mon.o
obj-$(CONFIG_DEVFREQ_GOV_MSM_GPUBW_MON)	+= governor_bw_vbif.o
obj-$(CONFIG_DEVFREQ_GOV_SPDM_HYP) 	+= governor_spdm_bw_hyp.o
obj-$(CONFIG_ADRENO_IDLER)		+= adreno_idler.o

# DEVFREQ Drivers
obj-$(CONFIG_ARM_EXYNOS4_BUS_DEVFREQ)	+= exynos4_bus.o
obj-$(CONFIG_MSM_DEVFREQ_DEVBW)		+= devfreq_devbw.o
obj-$(CONFIG_DEVFREQ_SIMPLE_DEV)	+= devfreq_simple_dev.o
obj-$(CONFIG_DEVFREQ_SPDM) 		+= devfreq_spdm.o devfreq_spdm_debugfs.o

# DEVFREQ Boost
obj-$(CONFIG_DEVFREQ_BOOST)		+= devfreq_boost.o
