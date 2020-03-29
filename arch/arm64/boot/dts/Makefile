# SPDX-License-Identifier: GPL-2.0
dtb-$(CONFIG_CAMERA_CROWN) += exynos/exynos9810-crownlte_eur_open_26.dtb

dtb-$(CONFIG_CAMERA_STAR2) += exynos/exynos9810-star2lte_eur_open_26.dtb
dts-dirs += exynos

subdir-y          := $(dts-dirs)

always            := $(DTB_LIST)

targets += dtbs
dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files       := exynos/*.dtb *.dtb*
