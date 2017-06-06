[![Codefresh build status]( https://g.codefresh.io/api/badges/build?repoOwner=ClemMahe&repoName=DockerfileAndroidFastlane&branch=master&pipelineName=DockerfileAndroidFastlane&accountName=ClemMahe&type=cf-1)]( https://g.codefresh.io/repositories/ClemMahe/DockerfileAndroidFastlane/builds?filter=trigger:build;branch:master;service:59371c999d2f2000010a45aa~DockerfileAndroidFastlane)

# Dockerfile for Android with Fastlane

Based on openjdk:8 with Android SDK 25, Buildtools 25.0.3 and last version of fastlane (with dependencies such as ruby-dev & gem installed). If asked, i could set a static version of fastlane.

# Pull from Docker Cloud

docker pull clemmahe/gitlabandroid

# Run

docker run -i -t clemmahe/gitlabandroid /bin/bash

# Use as base image

FROM clemmahe/gitlabandroid
