# Introduction to Apache Nifi

The purpose of this walkthrough is to a be simple introduction to Apache Nifi and how to build data flows using the UI. In the walkthrough, we will cover how we can take a CSV file, break it up, and convert the individual records into JSON format. Again, this walkthrough is mainly for getting accustomed to Apache Nifi and we will cover more complex data flows in future walkthroughs.

We will be using Gitpod for this walkthrough so that anyone can follow along without having to worry about OS incompatibilities. Hit the button below to get started!

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/Anant/example-introduction-to-nifi) 

# Walkthrough


## 1. Download Apache Nifi
```bash
curl -L -s https://mirrors.advancedhosters.com/apache/nifi/1.13.2/nifi-1.13.2-bin.tar.gz | tar xvz -C /workspace/example-introduction-to-nifi
```

## 2. Start Apache Nifi
```bash
./nifi-1.13.2/bin/nifi.sh start
```

## 3. Open Port 8080 in Browser
