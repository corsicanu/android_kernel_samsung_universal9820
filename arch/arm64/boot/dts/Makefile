# SPDX-License-Identifier: GPL-2.0
dtb-y += exynos/exynos9820.dtb
dtbo-$(CONFIG_CAMERA_BSS_V00) += \
    samsung/exynos9820-beyond0lte_eur_open_24.dtbo \
    samsung/exynos9820-beyond0lte_eur_open_20.dtbo \
    samsung/exynos9820-beyond0lte_eur_open_17.dtbo \
    samsung/exynos9820-beyond0lte_eur_open_18.dtbo \
    samsung/exynos9820-beyond0lte_eur_open_22.dtbo \
    samsung/exynos9820-beyond0lte_eur_open_19.dtbo \
    samsung/exynos9820-beyond0lte_eur_open_25.dtbo

dtbo-$(CONFIG_CAMERA_BSS_V01) += \
    samsung/exynos9820-beyond1lte_eur_open_24.dtbo \
    samsung/exynos9820-beyond1lte_eur_open_20.dtbo \
    samsung/exynos9820-beyond1lte_eur_open_19.dtbo \
    samsung/exynos9820-beyond1lte_eur_open_23.dtbo \
    samsung/exynos9820-beyond1lte_eur_open_17.dtbo \
    samsung/exynos9820-beyond1lte_eur_open_18.dtbo \
    samsung/exynos9820-beyond1lte_eur_open_26.dtbo \
    samsung/exynos9820-beyond1lte_eur_open_22.dtbo \
    samsung/exynos9820-beyond1lte_eur_open_21.dtbo

dtbo-$(CONFIG_CAMERA_BSS_V02) += \
    samsung/exynos9820-beyond2lte_eur_open_23.dtbo \
    samsung/exynos9820-beyond2lte_eur_open_18.dtbo \
    samsung/exynos9820-beyond2lte_eur_open_16.dtbo \
    samsung/exynos9820-beyond2lte_eur_open_17.dtbo \
    samsung/exynos9820-beyond2lte_eur_open_04.dtbo \
    samsung/exynos9820-beyond2lte_eur_open_25.dtbo \
    samsung/exynos9820-beyond2lte_eur_open_24.dtbo \
    samsung/exynos9820-beyond2lte_eur_open_20.dtbo \
    samsung/exynos9820-beyond2lte_eur_open_26.dtbo \
    samsung/exynos9820-beyond2lte_eur_open_19.dtbo

dtbo-$(CONFIG_CAMERA_BSS_V00X) += \
    samsung/exynos9820-beyondx_eur_open_07.dtbo \
    samsung/exynos9820-beyondx_eur_open_00.dtbo \
    samsung/exynos9820-beyondx_eur_open_01.dtbo \
    samsung/exynos9820-beyondx_eur_open_03.dtbo \
    samsung/exynos9820-beyondx_eur_open_04.dtbo \
    samsung/exynos9820-beyondx_eur_open_05.dtbo \
    samsung/exynos9820-beyondx_eur_open_06.dtbo \
    samsung/exynos9820-beyondx_eur_open_08.dtbo \
    samsung/exynos9820-beyondx_eur_open_02.dtbo

targets += dtbs
DTB_LIST  := $(dtb-y) $(dtbo-y)
always    := $(DTB_LIST)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := *.dtb*
