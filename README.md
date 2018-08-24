# kubernetes-notes
> Kubernetes 学习笔记

# Summary

* [Introduction](README.md)

* [安装与配置]()
    * [使用kubespray安装kubernetes](setup/install-k8s-by-kubespray.md)
    * [使用minikube安装kubernetes](setup/install-k8s-by-minikube.md)
* [基本概念]()
    * [kubernetes架构]()
        * [Kubernetes总架构图](concepts/architecture/kubernetes-architecture.md)
        * [基于Docker及Kubernetes技术构建容器云（PaaS）平台概述](concepts/architecture/paas-based-on-docker-and-kubernetes.md)
    * [kubernetes对象]()
        * [理解kubernetes对象](concepts/object/understanding-kubernetes-objects.md)
        * [kubernetes常用对象说明](concepts/object/kubernetes-basic-concepts.md)
        * [Pod详解](concepts/object/kubernetes-pod-introduction.md)
* [核心原理]()
    * [Api Server](principle/kubernetes-core-principle-api-server.md)
    * [Controller Manager](principle/kubernetes-core-principle-controller-manager.md)
    * [Scheduler](principle/kubernetes-core-principle-scheduler.md)
    * [Kubelet](principle/kubernetes-core-principle-kubelet.md)
    * [网络原理](principle/kubernetes-network.md)
* [资源配额]()
    * [资源配额](resource/resource-quota.md)
    * [Pod限额](resource/limit-range.md)
    * [资源服务质量](resource/quality-of-service.md)   
* [运维指南]()
    * [kubectl命令工具](operation/kubectl.md)
    * [kubernetes集群问题排查](operation/kubernetes-troubleshooting.md)
    * [指定Node调度与隔离](operation/nodeselector-and-taint.md)
* [开发指南]()
    * [client-go的使用及源码分析](develop/client-go.md)
* [监控体系]()
    * [监控体系介绍](monitor/kubernetes-cluster-monitoring.md)
    * [cAdvisor介绍](monitor/cadvisor-introduction.md)
    * [Heapster介绍](monitor/heapster-introduction.md)
    * [Influxdb介绍](monitor/influxdb-introduction.md)
* [第三方应用]()
    * [Etcd]()
        * [Etcd介绍](third/etcd/etcd-introduction.md)
        * [Etcd启动配置参数](third/etcd/etcd-setup-flags.md)
        * [etcdctl命令工具-V2](third/etcd/etcdctl-v2.md)
        * [etcdctl命令工具-V3](third/etcd/etcdctl-v3.md)
    * [Flannel]()
        * [Flannel介绍](third/flannel/flannel-introduction.md)

# 赞赏

> 如果觉得文章有帮助的话，可以打赏一下，谢谢！

<img src="http://ozilwgpje.bkt.clouddn.com/donate/donate.jpg" width="70%"/>
