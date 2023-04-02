# :Cloud Native Application Developement and support Engineer - Essentials:
### **{ Docker, Go Programing Language (GoLang), Kubernetes, YAML, JSON, Helm }**
**Learn from experienced and certified professionals.**
**Hands-On, Real world scenario based, Practical training**
**Contact us :**

    Email:  ninitltd@ninit.tech, ninitltd@gmail.com
    Contact: +44 07904500068

### Aim:
> This course is specially designed for complete beginners. On completion of this course the participant will gain in-depth knowledge about **Developing and supporting _Cloud Native Application_**. Delegats will learn and master most in demand skills such as **Docker** , **Kubernetes**, **Helm** package management system, **Source control system (GIT)**, **Go Programing Language**, The modern general purpose programming language. Delegates will confidently able to build and deploy containerized applicaions end to end with CI/CD (Continuous Integration and Continuous Delivery) methodology. Delegats will be able to comfirtably adopt **Conatiner Orchestration platform** across multiple public cloud offerings.

> Participants will be confident around concepts of modern, containerised software delivery life cycle (SDLC) along with Configuration and Management of services on the **Kuberentes** Platform. This course is designed for _anyone and everyone_ who is interested in kick starting their IT career in the modern world. Delegates will gain good hands-on experience which will help them to start a new career with multiple, good long term opportunities. All softwares and applications outlined in this course are FREE and OpenSource. **Welcome to the world of OpenSource.**


### The delegate will acquire essential knowledge which will help them to become a good:

* Cloud Native Engineer.
* Kubernetes Administrator.
* Cloud Native Application developer.
* Kubernetes Support Engineer.
* GO Application developer.
* Automation Engineer.                       
* Build and Release specialist.


### Prerequisites :
### At least one of the following.

* **Desire** to learn and master new skills.
* Problem solving **Atitude**.
* Good **Team Player**.
* **Interested** in exploring new career opportunities.
* **Open minded**.

 **_Note: Every delegate will need their own laptop or desktop computer._**

## Setting up your device (Member of our team will help you to setup your Workstation OR Laptop)

## Fundamentals on data serialisation and basic application concepts.

  - YAML
  - JSON
  - What is API?
    * Take example of public API e.g `github` or `gitlab`
    * Familieries with `curl` and `wget` utility.
  - Basic understanding to Web standards.

>## Docker
* Virtual machines vs Containers.
* What is an IP Address and how applications and devices communicate.
* Why Docker Containerization ?
* What is a container ?
* Get familier with dockerCli.
* Learn basic Docker operations.
* Learn about 
    * docker `run` , `exec` , `rm` and other important commands.
* Understanding docker image concept.
  - Learn about Docker-Hub (A free docker image repository)
  - Understanding image tags.
  - Pull a basic ​busybox​ and ​alpine​ image from dockerhub. 
      * ​docker `pull`
  - List all images available local on your system. 
      * docker `images`
  - Inspect a docker image to gain insight of the image. 
      * ​docker image `inspect`
  - Familierise with basic **LINUX utilities** through a container.
* Understand different **Dockerfile** commands.
* Build container from default images.
* Create docker image from running container.
* Write _DockerFile_ to build container image from scratch.
* Build a custom web server image using _nginx webserver_.
    * docker _build_
* Docker Compose to run multiple containers.

>## Go Programing Language : PART 1
  * Why Learn Go Programming Language?
  * Install the latest version of Go.
  * Install an editor to prepare `go` code.
  * Understand basic `go` syntax, importance of `package`, `import` ,`func main()` in `main.go`
  * Understand difference between `Interpreted vs Compiled` programming language.
  * Write up first `go` code to print some text.
    * `Println`, `Print`, `Printf` from `fmt` package.
  * Familierise with `GO` _(Beginners Level)_ :
    * Variables
    * Constants
    * Value types:
      * Strings
      * Integers
      * Floats
      * Booleans
    * Operators:
      * Conditional operators `= , == , != , < , > , <= , >=`
      * Logical operators `And - &&` , `OR - ||` , `NOT - !`
    * Pointers.
      * The `&` and `*` operators.
    * Conditional statements:
      * _if_
      * _if/else_
      * _if/else..if_
      * Switch
    * For loop. _Only one loop_.
    * Arrays, Slices and Map
    * Functions.
  * _Develop your first application in GO with confidence_
    * We will develop our first application in `go` and package it in docker container to learn a _Real World Scenario_ to automate application deployment using containers.

>## Kubernetes `K8S`
  * What is `Kubernetes` ?
  * Why `kubernete` adoption is on rise ?
  * `Docker` vs `Kubernetes` - comparision.
  * High level Architectural diagram of Kubernetes and core components.
  * What is `kubernetes` API ?
  * Setup `kubernetes`.
  * Install `kubectl` - A command line management utility.
  * Query `k8s` api with kubectl and get familier with basics.
  * Kubernetes resources :
    >### Namespaces
      * Whats ia a `NAMESPACE`? Understand importance of `NS`
      * When to use different namespaces ?
      * Switch between namespaces permenantly vs temperory options.
      * Create a new namespace (Imperative way)
      * Understand `Imperative` vs `Declarative` approach to create resources.
      * Create a new namespace (Declarative way)
    >### Pods
      * What is a `POD` ?
      * Understand difference between `POD` vs `Container`
        * Create a `POD` with one of the `nginx image` we prepared earlier(Imperative).
        * Create a `POD` (Declaratice).
      * Understanding pod lifecycle.
      * Pod logs.
      * Pod Internals:
    >### Labels and Selectors
      * Importance of Labels and selectors ?
      * Syntax and character set.
      * List, Watch and filter kubernetes resources.
    >### Service
      * What is a service ?
      * Service types in `k8s` :
        - ClusterIP (Default)
        - NodePort
        - LoadBalancer
        - Externalname
      * Setup a default service for the `POD` created in previous step.
      * Query services with `kubectl` to verify details.
      * Query the service endpoint from `web browser` or `cURL` to confirm its working as expected.
      * Setup a `NodePort` serivce for the same pod and check again.
    >### ConfigMap
      * What is a configMap ?
      * Create config map from literals.
      * Create config map from files.
      * Configure pod to setup configuration / parameters from configMap.
      * Configure pod to setup environment variables from configMap.
      * Configure pod to setup configuration from volume.
    >### Secrets
      * What is a secret ?
      * Overview of secrets. understand base64 encoding / decoding.
      * Create a secret.
      * Retrieve a secret.
      * Configure a pod to retrieve credentials/parameters from a secret.
    >### Deployments
      * What is a deployment ?
      * Deployment manifest (template).
      * Prepare a custom deployment using imperative command and different options.
      * Create a deployment.
      * Update a deployment.
      * Practice Deploy commands:
        - `rollout`, `scale`, `autoscale`
      * Check history and status of deployment.
      * Recreate deployment. (rolling update vs recreate)
      * Pausing and Resuming deployment.
    >### Replicasets
      * What is a replicaset ?
      * When to use Replicaset ?
      * Scaling a replicaset.
    >### Volumes
      * Type of volumes.
      * Persistent Volumes.
      * Persistent Volume Claim.
      * Storage classes.

>## Helm Package manager.
  * What is a package maanager ?
  * Why `helm` for `kubernete`s package management ?
  * Setup helm locally on your system.
  * helm repositories :
    - add, remove, list repositories.
  * Prepare a helm chart to deploy `nginx` web server.
    - helm create `chart_name` [flags]
  * Gain better insight about helm :
    - Charts
    - Releases
    - Revisions
    - Template
    - Values.yaml
  * Deploy your first helm release.
  * Query deployed helm release and validate.
    - get
    - list
    - status
  * Make ammendment to helm release and upgrade existing helm release.

>## SCM or VCS ( Theory + Practical ):
>#### Source control management / Version Control System
* What is SCM/VCS and why it is important ?
* Download / Install `git`.
* Configure local git preferences.
* Getting familiar with command line options/help.
* Create a FREE GitLab account.
* Private vs Public repository.
* Create a new project repository on GitLab.
* Concepts about Users,Groups and Permissions.
* Cloning repository.
* Commit new changes and raise new merge request.
* Peer review pending merge requests and approvals.
* Push new changes to GitLab.
* Advance concepts of branches and tags.
* Learn about `gitlab-ci.yml` configurations.
* Prepare your first pipeline to `build` and `publish` custom `docker image`.


>## Go Programing Language : PART 2
  * **Will learn more with real world scenarios.**

  >### Continue
  * Understand `Control Statements` with more examples ?
  * `Struct` and `Interfaces`
  * Prepare a simple web server with GoLang.
    * Package it with `docker image`, run it, test it with `docker run`.
    * Prepare a `pod` definition and deploy to kubernetes.
    * Prepare a `deployment` definition and deploy to kubernetes.
    * Prepare a custom config and update the pod when it starts to change web server content.
  * Prepare a simple web app to store information in flat file.
  * Extend our app to store data in a database.
    * We will work with 2 containers now. (First test this with plain Docker)
    * Deploy on kubernetes. 
  * `Concurrancy`
    * `Goroutines` and `Channels`
   >### Introduction to API Development
   * Will build a real world project in this section.
---
### ** Based on participants' requirements, advanced topics will be covered.
### Quizzes, home work and more hands on lab work will be available during the course to get particepants ready for interviews.

### ** Required information and basic knowledge will be provided depends on delegate’s requirement.

----
#### About Instructor :
##### Nilesh Barot : DevOps and Cloud Consultant

___________Nilesh is a DevOps practitioner with over 2 decades of experience in various industries along with in-depth understanding of complex IT environments. In recent years he has successfully delivered projects by adopting and following DevOps processes.________

Professional Qualifications: https://www.credly.com/users/nilesh-barot/badges

Linked in profile : https://uk.linkedin.com/in/nileshbarot

### Duration of the course : 3 - 4 Months
### Schedule :
	* Every Sunday : 10:00 am - 12:30 pm
	* Additional support sessions : During weekdays in evening as per students convenience.
	* Contact us :

	    Email:  ninitltd@ninit.tech, ninitltd@gmail.com

	    Contact: +44 07904500068
