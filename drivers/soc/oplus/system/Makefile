# SPDX-License-Identifier: GPL-2.0-only
# Copyright (C) 2018-2020 Oplus. All rights reserved.

obj-y 	+= platform.o
obj-$(CONFIG_OPLUS_FEATURE_FEEDBACK) 	+= feedback/
obj-$(CONFIG_OPLUS_FEATURE_UBOOT_LOG) 	+= uboot_log/
obj-$(CONFIG_OPLUS_FEATURE_SHUTDOWN_DETECT)    += shutdown_detect/
obj-$(CONFIG_OPLUS_FEATURE_SLABTRACE_DEBUG) +=  slabtrace/
obj-$(CONFIG_OPLUS_FEATURE_OPROJECT) 	+= oplus_project/
obj-$(CONFIG_OPLUS_FEATURE_QCOM_MINIDUMP_ENHANCE) 	+= qcom_minidump/
obj-$(CONFIG_OPLUS_FEATURE_HUNG_TASK_ENHANCE) += hung_task_enhance/
obj-$(CONFIG_OPLUS_FEATURE_PHOENIX)     += oplus_phoenix/
obj-$(CONFIG_OPLUS_FEATURE_HANS) += oplus_hans/
obj-$(CONFIG_OPLUS_FEATURE_PMIC_MONITOR)     += oplus_pmic_monitor/
obj-$(CONFIG_OPLUS_FEATURE_SAUPWK)     += oplus_saupwk/
obj-$(CONFIG_OPLUS_FEATURE_DUMP_DEVICE_INFO)	+=  dump_device_info/
obj-$(CONFIG_OPLUS_FEATURE_RECORD_MDMRST)     += mdmrst/
obj-$(CONFIG_OPLUS_FEATURE_CMDLINE)     += cmdline_parser/
#ifdef OPLUS_FEATURE_DUMP_REASON
#terry.zhong@optimization.Stability, 2020/11/30, Add for dump reason
obj-$(CONFIG_OPLUS_FEATURE_DUMP_REASON)	+=  dump_reason/
#endif /* OPLUS_FEATURE_DUMP_REASON */

ifdef CONFIG_OPLUS_SYSTEM_KERNEL_QCOM
obj-$(CONFIG_OPLUS_FEATURE_PROJECTINFO)	+=  project_info/
endif

#ifdef OPLUS_FEATURE_QCOM_PMICWD
obj-$(CONFIG_OPLUS_FEATURE_QCOM_PMICWD)     += qcom_pmicwd/
#endif /* OPLUS_FEATURE_QCOM_PMICWD */

#ifdef OPLUS_FEATURE_FORCE_SHUTDOWN
obj-$(CONFIG_OPLUS_FEATURE_FORCE_SHUTDOWN) += force_shutdown/
#endif /* OPLUS_FEATURE_FORCE_SHUTDOWN */

#ifdef OPLUS_FEATURE_MM_OSVELTE
#liuhailong@BSP.Kernel.MM, 2021/08/06, Add for osvelte
obj-y += mm_osvelte/
#endif /* OPLUS_FEATURE_MM_OSVELTE */

#ifdef OPLUS_FEATURE_MM_FEEDBACK
#Zhao.Pan@MULTIMEDIA.AUDIODRIVER.KERNEL, 2020/08/08, Add for multimedia kevent feedback driver
obj-$(CONFIG_OPLUS_FEATURE_MM_FEEDBACK)         += oplus_mm_fb/
#endif /* OPLUS_FEATURE_MM_FEEDBACK */

#ifdef OPLUS_FEATURE_QCOM_WATCHDOG
obj-$(CONFIG_OPLUS_FEATURE_QCOM_WATCHDOG)     += qcom_watchdog/
#endif /* OPLUS_FEATURE_QCOM_WATCHDOG */

#ifdef OPLUS_FEATURE_ACM
#Yuwei.Guan@BSP.Kernel.FS,2020/07/08, Add for acm
obj-$(CONFIG_OPLUS_FEATURE_ACM)     += acm/
#endif /* OPLUS_FEATURE_ACM */
#ifdef OPLUS_FEATURE_THEIA
#yanggang@BSP.Kernel.Stability,2020/07/08, Add for theia
obj-$(CONFIG_OPLUS_FEATURE_THEIA)     += theia/
#endif /* OPLUS_FEATURE_THEIA */
#ifdef OPLUS_FEATURE_SELINUX_CONTROL_LOG
#Shuangquan.Du@ANDROID.SELINUX, 2018/01/13, Add for disable selinux denied logs in MP version
obj-$(CONFIG_SECURITY_SELINUX) += selinux/
#endif /* OPLUS_FEATURE_SELINUX_CONTROL_LOG */
#ifdef OPLUS_FEATURE_MISC
#terry.zhong@OPTI.Kernel.Stability, 2020/09/7, enable oplus misc feature
obj-y += misc/
#endif /* OPLUS_FEATURE_MISC */
obj-$(CONFIG_OPLUS_FEATURE_MDMFEATURE)     += mdmfeature/
