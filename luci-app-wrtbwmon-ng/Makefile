#
# Copyright (C) 2020 xxx <xxx@xxx.com>
#
# This is free software, licensed under the Apache License, Version 2.0 .
#

include $(TOPDIR)/rules.mk

PKG_NAME:=luci-app-wrtbwmon-ng
PKG_VERSION:=1.0.0
PKG_RELEASE:=1

PKG_LICENSE:=Apache-2.0
PKG_MAINTAINER:=

LUCI_TITLE:=A Luci module that uses a modified version of wrtbwmon to track bandwidth usage
LUCI_DEPENDS:=+wrtbwmon-ng
LUCI_PKGARCH:=all

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
