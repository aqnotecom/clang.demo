
#     Title: 
#    Author: "Peng Li"<aqnote@aqnote.com>
#     CDate: 20190325
#     MDate:
# Copyright: http://aqnote.com/LICENSE
#
#

# Constant
MODULE_NAME 		= json-c.lifecycle
MODULE_INTRODUCE 	=

# Depends
## 说明：由于/opt/aqnote不是ld标准路径库，因此在运行时需要设置链接库路径
## 在环境变量中添加 `export LD_LIBRARY_PATH=/opt/aqnote/lib`，这样才能运行
DEPEND_MODULE_LIST 	=
DEPEND_THIRD_LIST	=
DEPEND_NONSTD_LIST 	= JSON-C
DEPEND_NONSTD_JSON-C_HOME 	= /opt/aqnote/json-c
DEPEND_NONSTD_JSON-C_LIB 	= json-c
DEPEND_PKG			= gtk+-2.0 gtk+-3.0
DEPEND_STD			=

# Compile
MODULE_LINK 	=
MODULE_BUILD 	= DEBUG
MODULE_TARGET 	= $(MODULE_NAME).app

include ../../mk/config.mk
include ${PROJECT_MAKEFILE_HOME}/global.mk


