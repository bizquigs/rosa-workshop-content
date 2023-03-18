## Introduction to the Workshop Environment

In order to streamline the process of this workshop and ensure repeatable steps for associates in the future, we have configured the workshop to run on the [RHPDS](https://demo.redhat.com/catalog){:target="_blank"} demo system. 

In order to do this we will be using documentation, proprietary to Red Hat, known in cool circles as the "ROSA RHPDS Deployment Guide", available [here](https://docs.google.com/document/d/1u9wDEWXlX8r5gJiUcjBoiVllDMCl9KvPyxJ8jOkuwcI/){:target="_blank"}.

In this guide we will cover the following:

- Using RHPDS to deploy an AWS Environment (link available [here](https://docs.google.com/document/d/1u9wDEWXlX8r5gJiUcjBoiVllDMCl9KvPyxJ8jOkuwcI/edit#heading=h.2ym2u1bfh9bh){:target="_blank"})
- Installation and Deployment of an STS ROSA Cluster (link available [here](https://docs.google.com/document/d/1u9wDEWXlX8r5gJiUcjBoiVllDMCl9KvPyxJ8jOkuwcI/edit#){:target="_blank"})
!!! warning "Do not choose the latest version"

    As part of this workshop, we're going to walk through the process of upgrading a cluster. In order to do this, select the next-to-latest version of the 4.11 series during deployment so you have the option to upgrade. This should mean choosing version 4.11.24 at install time so that we can upgrade to 4.11.25.
    
!!! note "Select Multi-AZ "

    During your cluster deployment, select multi-az instead of the default single-az.
- Accessing the ROSA Cluster (link available [here](https://docs.google.com/document/d/1u9wDEWXlX8r5gJiUcjBoiVllDMCl9KvPyxJ8jOkuwcI/edit#heading=h.w1lzwyhnr30q){:target="_blank"})

After these steps, you should have a cluster running in a RHPDS AWS environment and be able to access your cluster, as cluster-admin, from both the UI and the command line.
!!! note

    We will return to this doc later when it's time to delete the cluster and clean up our RHPDS environments. 
