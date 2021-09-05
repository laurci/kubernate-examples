# Kubernate Basics

This repository showcases the resources features of Kubernate.

To execute any of the examples run `kubernate <name>`. Make sure you have ran `yarn` in this directory and have Kubernate insalled globally before attempting running any of these examples.

## hello-world

Run `kubernate hello-world`.

This example uses Kubernate to create a namespace, a pod template and a deployment for every demo/v1/HelloWorld you create. The outputs are written to a single yaml file in `output/hello-world.yaml`.

If you update the spec of the resource, make sure to run `kubernate generate` to update the generated code.
