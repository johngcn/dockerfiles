# loads/kafka:2.2
FROM solsson/kafka:2.2.0 

LABEL maintainer="john@johng.cn"

###############################################################################
#                                INSTALLATION
###############################################################################

ADD ./server.properties /opt/kafka/config/server.properties

###############################################################################
#                                   START
###############################################################################

# 在K8S中使用必须使用command指令执行，docker修改为默认不执行
