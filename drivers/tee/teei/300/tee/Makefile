# Copyright (c) 2015-2020, MICROTRUST Incorporated
# All Rights Reserved.
#
# This program is free software; you can redistribute it and/or
# modify it under the terms of the GNU General Public License
# version 2 as published by the Free Software Foundation.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
# GNU General Public License for more details.

obj-y += teeiv3.o
teeiv3-objs += tee_core.o
teeiv3-objs += tee_shm.o
teeiv3-objs += tee_shm_pool.o
teeiv3-objs += tee_client_api.o

ifeq ($(CONFIG_MICROTRUST_TEST_DRIVERS),y)
teeiv3-objs += capi_proxy.o
endif

obj-y += soter/
