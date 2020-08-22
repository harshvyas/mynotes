---
title: "aws-cloud-developement-kit"
date: 2020-08-22T00:00:00-04:00
draft: false 
---

## AWS Deployment Options
1. manual in console
2. scripted via aws-cli or aws-sdk
3. declarative JSON/YAML via cloudformation
4. document-obj-model (DOM) via troposphere
5. componentized via aws-cdk 

---

## Workflow
{{< mermaid >}}
graph LR
    A["constructs in stack written in python code"] --> B["cdk-cli compilation"] --> C["cloudformation deployment"]
{{< /mermaid >}}

---

## Pre-Requisites
```bash
harsh.vyas@VYASH-M-6AAE:~/playspace/aws-cdk|⇒  node --version
v12.18.0
harsh.vyas@VYASH-M-6AAE:~/playspace/aws-cdk|⇒  npm --version
6.14.4
harsh.vyas@VYASH-M-6AAE:~/playspace/aws-cdk|⇒  aws --version
aws-cli/2.0.16 Python/3.8.2 Darwin/19.6.0 botocore/2.0.0dev20
harsh.vyas@VYASH-M-6AAE:~/playspace/aws-cdk|⇒  cdk --version
1.60.0 (build 8e3f53a)
harsh.vyas@VYASH-M-6AAE:~/playspace/aws-cdk|⇒  python3 --version
Python 3.7.6
harsh.vyas@VYASH-M-6AAE:~/playspace/aws-cdk|⇒  pip3 --version
pip 19.3.1 from /usr/local/lib/python3.7/site-packages/pip (python 3.7)
```
---
