# SPDX-License-Identifier: BSD-3-Clause
# Copyright(c) 2018 Intel Corporation

sources = files('main.c',
		'test_bbdev.c',
		'test_bbdev_perf.c',
		'test_bbdev_vector.c')
allow_experimental_apis = true
deps += ['bbdev', 'bus_vdev']
if dpdk_conf.has('RTE_LIBRTE_PMD_FPGA_LTE_FEC')
	deps += ['bbdev_fpga_lte_fec']
endif