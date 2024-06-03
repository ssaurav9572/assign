Cow wisdom web server
Prerequisites

sudo apt install fortune-mod cowsay -y

How to use?

    Run ./wisecow.sh
    Point the browser to server port (default 4499)

What to expect?

wisecow
Problem Statement

Deploy the wisecow application as a k8s app
Requirement

    Create Dockerfile for the image and corresponding k8s manifest to deploy in k8s env. The wisecow service should be exposed as k8s service.
    Github action for creating new image when changes are made to this repo
    [Challenge goal]: Enable secure TLS communication for the wisecow app.

Expected Artifacts

    Github repo containing the app with corresponding dockerfile, k8s manifest, any other artifacts needed.
    Github repo with corresponding github action.
    Github repo should be kept private and the access should be enabled for following github IDs: nyrahul, SujithKasireddy
