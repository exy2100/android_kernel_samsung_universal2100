# SPDX-License-Identifier: GPL-2.0

# Projects
dtbo-$(CONFIG_SEC_O1S_PROJECT) += samsung/o1s/o1s_eur_openx_w01_r02.dtbo
dtbo-$(CONFIG_SEC_O1S_PROJECT) += samsung/o1s/o1s_eur_openx_w01_r16.dtbo
dtbo-$(CONFIG_SEC_O1S_PROJECT) += samsung/o1s/o1s_eur_openx_w01_r22.dtbo
dtbo-$(CONFIG_SEC_O1S_PROJECT) += samsung/o1s/o1s_eur_openx_w01_r18.dtbo
dtbo-$(CONFIG_SEC_O1S_PROJECT) += samsung/o1s/o1s_eur_openx_w01_r19.dtbo
dtbo-$(CONFIG_SEC_O1S_PROJECT) += samsung/o1s/o1s_eur_openx_w01_r21.dtbo
dtbo-$(CONFIG_SEC_O1S_PROJECT) += samsung/o1s/o1s_eur_openx_w01_r20.dtbo
dtbo-$(CONFIG_SEC_O1S_PROJECT) += samsung/o1s/o1s_eur_openx_w01_r17.dtbo

dtbo-$(CONFIG_SEC_T2S_PROJECT) += samsung/t2s/t2s_eur_openx_w01_r18.dtbo
dtbo-$(CONFIG_SEC_T2S_PROJECT) += samsung/t2s/t2s_eur_openx_w01_r16.dtbo
dtbo-$(CONFIG_SEC_T2S_PROJECT) += samsung/t2s/t2s_eur_openx_w01_r22.dtbo
dtbo-$(CONFIG_SEC_T2S_PROJECT) += samsung/t2s/t2s_eur_openx_w01_r17.dtbo
dtbo-$(CONFIG_SEC_T2S_PROJECT) += samsung/t2s/t2s_eur_openx_w01_r20.dtbo
dtbo-$(CONFIG_SEC_T2S_PROJECT) += samsung/t2s/t2s_eur_openx_w01_r19.dtbo
dtbo-$(CONFIG_SEC_T2S_PROJECT) += samsung/t2s/t2s_eur_openx_w01_r02.dtbo
dtbo-$(CONFIG_SEC_T2S_PROJECT) += samsung/t2s/t2s_eur_openx_w01_r21.dtbo

dtbo-$(CONFIG_SEC_P3S_PROJECT) += samsung/p3s/p3s_eur_openx_w01_r16.dtbo
dtbo-$(CONFIG_SEC_P3S_PROJECT) += samsung/p3s/p3s_eur_openx_w01_r02.dtbo
dtbo-$(CONFIG_SEC_P3S_PROJECT) += samsung/p3s/p3s_eur_openx_w01_r17.dtbo
dtbo-$(CONFIG_SEC_P3S_PROJECT) += samsung/p3s/p3s_eur_openx_w01_r21.dtbo
dtbo-$(CONFIG_SEC_P3S_PROJECT) += samsung/p3s/p3s_eur_openx_w01_r18.dtbo
dtbo-$(CONFIG_SEC_P3S_PROJECT) += samsung/p3s/p3s_eur_openx_w01_r19.dtbo
dtbo-$(CONFIG_SEC_P3S_PROJECT) += samsung/p3s/p3s_eur_openx_w01_r22.dtbo
dtbo-$(CONFIG_SEC_P3S_PROJECT) += samsung/p3s/p3s_eur_openx_w01_r20.dtbo

dtbo-$(CONFIG_SEC_R9S_PROJECT) += samsung/r9s/r9s_eur_openx_w01_r18.dtbo
dtbo-$(CONFIG_SEC_R9S_PROJECT) += samsung/r9s/r9s_eur_openx_w01_r17.dtbo
dtbo-$(CONFIG_SEC_R9S_PROJECT) += samsung/r9s/r9s_eur_openx_w01_r00.dtbo

# Platform
dtb-y += exynos/vendor/exynos2100.dtb

targets += dtbs
DTB_LIST  := $(dtb-y) $(dtbo-y)
always    := $(DTB_LIST)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := *.dtb*
