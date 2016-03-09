#rkwifi packed Makefile
# (gwl)

obj-$(CONFIG_RKWIFI) += rk_wifi_config.o ../wifi_sys/rkwifi_sys_iface.o
obj-$(CONFIG_RKWIFI) += bcmdhd/ 

.PHONY: clean

clean:
	find . -name '*.o*' -exec rm -f {} \; 
