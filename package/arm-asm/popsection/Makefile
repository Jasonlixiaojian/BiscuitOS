################################################
#
# popsection
#
################################################
PK_ARM_ASM_POPSECTION_NAME        := popsection
PK_ARM_ASM_POPSECTION_VERSION     := $(CONFIG_PK_ARM_ASM_POPSECTION_VERSION)
PK_ARM_ASM_POPSECTION_SITE        := $(CONFIG_PK_ARM_ASM_POPSECTION_URL)
PK_ARM_ASM_POPSECTION_GITHUB      := $(CONFIG_PK_ARM_ASM_POPSECTION_GITHUB)
PK_ARM_ASM_POPSECTION_SUBNAME     :=
PK_ARM_ASM_POPSECTION_BUILDARCH   := $(CONFIG_PK_ARM_ASM_POPSECTION_BUILDARCH)
PK_ARM_ASM_POPSECTION_DIR         := $(srctree)/package/arm-asm/popsection
PK_ARM_ASM_POPSECTION_PATCH       := $(PK_ARM_ASM_POPSECTION_DIR)/patch
PK_ARM_ASM_POPSECTION_BSBIT       := popsection-$(PK_ARM_ASM_POPSECTION_VERSION).bsbit
PK_ARM_ASM_POPSECTION_OUT         :=
PK_ARM_ASM_POPSECTION_SCRIPTS     := $(srctree)/scripts/package/package-module.sh
PK_ARM_ASM_POPSECTION_TAR         := $(CONFIG_PK_ARM_ASM_POPSECTION_TAR)
PK_ARM_ASM_POPSECTION_PACKAGE     :=
PK_ARM_ASM_POPSECTION_CONFIG      := $(CONFIG_PK_ARM_ASM_POPSECTION_CONFIG)
SUB_TARGET                  += $(PK_ARM_ASM_POPSECTION_DIR)/build

PK_ARM_ASM_POPSECTION_sh = $(CONFIG_SHELL) $(PK_ARM_ASM_POPSECTION_SCRIPTS) \
                 $1X \
                 $(PK_ARM_ASM_POPSECTION_NAME)X \
                 $(PK_ARM_ASM_POPSECTION_VERSION)X \
                 $(PK_ARM_ASM_POPSECTION_SITE)X \
                 $(PK_ARM_ASM_POPSECTION_GITHUB)X \
                 $(PK_ARM_ASM_POPSECTION_PATCH)X \
                 $(CONFIG_LINUX_KERNEL_VERSION)X \
	         $(CONFIG_MAIN_PROJ_NAME)X \
                 $(PK_ARM_ASM_POPSECTION_TAR)X \
                 $(CONFIG_LINUX_KERNEL_CROSS_COMPILE)X \
                 $(PK_ARM_ASM_POPSECTION_SUBNAME)X \
                 $(CONFIG_PK_ARM_ASM_POPSECTION_CONFIG)X \
                 $(CONFIG_PK_ARM_ASM_POPSECTION_LIBPATH)X \
                 $(CONFIG_PK_ARM_ASM_POPSECTION_CPPFLAGS)X \
                 $(CONFIG_PK_ARM_ASM_POPSECTION_DPKCONFIG)X \
                 $(CONFIG_PK_ARM_ASM_POPSECTION_CFLAGS)X \
                 $(CONFIG_PK_ARM_ASM_POPSECTION_LDFLAGS)X \
                 $(CONFIG_PK_ARM_ASM_POPSECTION_CXXFLAGS)X \
                 $(CONFIG_PK_ARM_ASM_POPSECTION_ASFLAGS)X \
                 $(PK_ARM_ASM_POPSECTION_BSBIT)X \
                 $(PK_ARM_ASM_POPSECTION_BUILDARCH)X \
		 $(PK_ARM_ASM_POPSECTION_CSRCFILE)X \
                 $(CONFIG_PK_ARM_ASM_POPSECTION_SRCFILE)X \
                 $(CONFIG_PK_ARM_ASM_POPSECTION_CSRCFILE)

$(PK_ARM_ASM_POPSECTION_DIR)/build: FORCE
	$(Q)$(call PK_ARM_ASM_POPSECTION_sh,$(srctree))
