K2HDKC DBaaS Override Configuration(K2HDKC DBaaS Utilities)
-----------------------------------------------------------
[![Systemd AntPickax CI](https://github.com/yahoojapan/k2hdkc_dbaas_override_conf/workflows/Nobuild%20AntPickax%20CI/badge.svg)](https://github.com/yahoojapan/k2hdkc_dbaas_override_conf/actions)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/yahoojapan/k2hdkc_dbaas_override_conf/blob/master/COPYING)
[![GitHub forks](https://img.shields.io/github/forks/yahoojapan/k2hdkc_dbaas_override_conf.svg)](https://github.com/yahoojapan/k2hdkc_dbaas_override_conf/network)
[![GitHub stars](https://img.shields.io/github/stars/yahoojapan/k2hdkc_dbaas_override_conf.svg)](https://github.com/yahoojapan/k2hdkc_dbaas_override_conf/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/yahoojapan/k2hdkc_dbaas_override_conf.svg)](https://github.com/yahoojapan/k2hdkc_dbaas_override_conf/issues)
[![RPM packages](https://img.shields.io/badge/rpm-packagecloud.io-844fec.svg)](https://packagecloud.io/antpickax/stable)
[![debian packages](https://img.shields.io/badge/deb-packagecloud.io-844fec.svg)](https://packagecloud.io/antpickax/stable)
[![ALPINE packages](https://img.shields.io/badge/apk-packagecloud.io-844fec.svg)](https://packagecloud.io/antpickax/stable)

### **K2HDKC** **DBaaS**

![K2HDKC DBaaS](https://dbaas.k2hdkc.antpick.ax/images/top_k2hdkc_dbaas.png)

#### K2HDKC DBaaS Overview
**K2HDKC DBaaS** (DataBase as a Service of K2HDKC) is a basic system that provides [K2HDKC(K2Hash based Distributed Kvs Cluster)](https://k2hdkc.antpick.ax/index.html) as a service.  
**K2HDKC DBaaS** (Database as a Service for K2HDKC) is a **Database as a Service** that uses [K2HR3](https://k2hr3.antpick.ax/) and works with [OpenStack](https://www.openstack.org/) and [kubernetes](https://kubernetes.io/) to build a [K2HDKC(K2Hash based Distributed Kvs Cluster)](https://k2hdkc.antpick.ax/index.html) Cluster for distributed KVS.  
Users can easily launch, scale, back up, and restore **K2HDKC** clusters as **K2HDKC DBaaS**.  

Detailed documentation for K2HDKC DBaaS can be found [here](https://dbaas.k2hdkc.antpick.ax/).  

#### K2HKDC DBaaS types
There are four types of **DBaaS** (Database as a Service) provided by **K2HDKC DBaaS** (Database as a Service for K2HDKC) as shown below.  
We provide two K2HDKC DBaaS types that cooperate with OpenStack and two types that cooperate with kubernetes.  

##### With Trove(Trove is Database as a Service for OpenStack)
This is DBaaS(Database as a Service) using Trove which is a product of OpenStack.  
It incorporates K2HDKC (Distributed KVS) as one of Trove’s databases to realize DBaaS(Database as a Service).

##### K2HDKC DBaaS CLI(Command Line Interface) for OpenStack
If you have an existing OpenStack environment, this K2HDKC DBaaS CLI(Command Line Interface) allows you to implement DBaaS(Database as a Service) without any changes.

##### K2HDKC DBaaS on kubernetes CLI(Command Line Interface)
If you are using kubernetes cluster or trial environment such as minikube, this K2HDKC DBaaS on kubernetes CLI(Command Line Interface) allows you to implement DBaaS(Database as a Service) without any changes.

##### K2HDKC Helm Chart
If you are using kubernetes cluster or trial environment such as minikube, you can install(build) DBaaS(Database as a Service) by using Helm(The package manager for Kubernetes) with K2HDKC Helm Chart.

### K2HDKC DBaaS Override Configuration
This **K2HDKC DBaaS Override Configuration** is a setting for connecting each component running on the Virtual Machine that enjoys the functions of K2HDKC DBaaS.  
This Configuration allows CHMPX and K2HDKC components to work together and exchange data with K2HR3.  

### Documents
  - [K2HDKC DBaaS Document](https://dbaas.k2hdkc.antpick.ax/index.html)
  - [Github wiki page](https://github.com/yahoojapan/k2hdkc_dbaas_override_conf/wiki)

  - [About k2hdkc Document](https://k2hdkc.antpick.ax/index.html)
  - [About chmpx Document](https://chmpx.antpick.ax/index.html)
  - [About k2hr3 Document](https://k2hr3.antpick.ax/index.html)

  - [About AntPickax](https://antpick.ax/)

### Repositories
  - [k2hdkc_dbaas_override_conf](https://github.com/yahoojapan/k2hdkc_dbaas_override_conf)
  - [k2hdkc_dbaas](https://github.com/yahoojapan/k2hdkc_dbaas)
  - [k2hdkc](https://github.com/yahoojapan/k2hdkc)
  - [chmpx](https://github.com/yahoojapan/chmpx)
  - [k2hr3](https://github.com/yahoojapan/k2hr3)
  - [k2hr3_app](https://github.com/yahoojapan/k2hr3_app)
  - [k2hr3_api](https://github.com/yahoojapan/k2hr3_api)
  - [k2hr3_get_resource](https://github.com/yahoojapan/k2hr3_get_resource)

### Packages
  - [k2hdkc-dbaas-override-conf(packagecloud.io)](https://packagecloud.io/app/antpickax/stable/search?q=k2hdkc-dbaas-override-conf)
  - [k2hdkc(packagecloud.io)](https://packagecloud.io/app/antpickax/stable/search?q=k2hdkc)
  - [chmpx(packagecloud.io)](https://packagecloud.io/app/antpickax/stable/search?q=chmpx)
  - [k2hr3-app(npm packages)](https://www.npmjs.com/package/k2hr3-app)
  - [k2hr3-api(npm packages)](https://www.npmjs.com/package/k2hr3-api)
  - [k2hr3-get-resource(packagecloud.io)](https://packagecloud.io/app/antpickax/stable/search?q=k2hr3-get-resource)

### License
This software is released under the MIT License, see the license file.

### AntPickax
K2HDKC DBaaS Override Configuration is one of [AntPickax](https://antpick.ax/) products.

Copyright(C) 2021 Yahoo Japan Corporation.
