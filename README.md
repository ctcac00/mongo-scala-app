# Simple MongoDB Scala App

## Introduction

This is a very simple skeleton of a scala app that connects to a MongoDB database, inserts one document and reads all documents in the database.

It is intended to be a starting point and so it has limited features/functionality.

## Dependencies

Install the required dependencies (instructions below for Mac OS X using homebrew)

* Java

```bash
brew install java
```

* Scala

```bash
brew install scala
```

* SBT

```bash
brew install sbt
```

## Run

Start the docker containers:

```bash
./run.sh
```

Check the app logs:

```bash
docker logs -f app
```

Stop a mongodb node:

```bash
docker stop mongo1
```
