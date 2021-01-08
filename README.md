# Auto-healer using Zookeeper


In cloud computing, auto-healing is a feature used to monitor a cluster and detect faulty application instances.

If a faulty instance is detected, the node is shut down and a new node is created with a healthy application instance.

In this practical assignment we will implement a very basic auto healer which will monitor a group of worker instances.


You are given a worker application

The worker instances are running a very complex computation that tends to crash in a particular edge case that the author did not account for.

Our mission is to maintain at least N worker nodes at any given moment.

If a worker crashes, we need to start a new worker.


## Instructions

Please download the attached resources.

(The solution is also provided, please try your best before looking at the solution)

In the downloaded resources you will find

    1. The flaky worker. This is a program that emulates a worker that randomly dies due to an exception

    2. The Auto-healer. This is only a partially complete project, your task is to complete the unimplemented methods

Once the implementation is complete.

    1. Run Zookeeper by running the zkServer.XX start command in the bin directory

    2. Build the worker project using the  mvn clean install command

    3. Following the Autohealer README for building and running the autohealer to launch and maintain any number of workers

Please follow the "Zookeeper Server and Client (Download and Setup)" lecture for instructions on how to download, install and configure Zookeeper.

Good luck!:)