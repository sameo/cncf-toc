# Confidential Containers 2022 Annual Review

## Background

Goals:
- Allow cloud native application owners to enforce application security requirements
- Transparent deployment of unmodified containers
- Support for multiple TEE and hardware platforms
- A trust model which separates Cloud Service Providers (CSPs) from guest applications
- Least privilege principles for the Kubernetes Cluster administration capabilities which impact delivering Confidential Computing for guest application or data inside the TEE.

## DevStats

The Confidential Containers project is a collection of logically and
programatically bound sub-projects, hosted across multiple git repositories
under the Confidential Containers GitHub organization.

Below is a chart of all GitHub activities across all Confidential Containers
repositories, since it's acceptance as a CNCF project:
* [Confidential Containers GithHub Contributions per repository (2022-03-08 to Now)](https://confidentialcontainers.devstats.cncf.io/d/1/activity-repository-groups?orgId=1&from=1646694000000&to=1686261599000)

The following chart is an aggregating view of all contributions to the
Confidential Containers project as whole, for the same time period:
* [Confidential Containers GithHub Contributions (2022-03-08 to Now)](https://confidentialcontainers.devstats.cncf.io/d/74/contributions-chart?orgId=1&var-period=d7&var-metric=contributions&var-repogroup_name=All&var-country_name=All&var-company_name=All&var-company=all&from=1646694000000&to=now-1h)

The project hourly activity for the same period is shown in the below chart:
* [Confidential Containers GitHub Hourly Activity (2022-03-08 to Now)](https://confidentialcontainers.devstats.cncf.io/d/8/dashboards?orgId=1&from=1646694000000&to=now-1h&viewPanel=2&refresh=15m)

Confidential Containers new Contributors:
* [Confidential Containers New Contributors (2022-03-08 to Now)](https://confidentialcontainers.devstats.cncf.io/d/52/new-contributors-table?orgId=1&from=1646694000000&to=now-1h)

These charts and statistics show a few interesting points:

* Since its acceptance as a CNCF project, the project has seen a steady stream
  of contributions.
* A very important metric for Confidential Containers: More than 40 new
  contributors have joined the project over the past year.
* Contributions are spread over different repositories, showing the width of the
  project:
  * On the client side, the `enclave-cc`, `attestation-agent`, `td-shim` and
    `image-rs` projects take the bulk of the contributions.
  * On the attestation part of the project, most of the contributions went to
    the `kbs` and `attestation-service` repositories.
  * The `cloud-api-adaptor` and `operator` sub-projects merged most of the
    infrastructure related contributions to Confidential Containers.

## Maintainers

The Confidential Containers project maintainership structure is defined as
follows:

* Each sub-project has its own list of maintainers, tracked through both a
  per-repo MAINTAINERS file and a corresponding GitHub team. We have multiple
  instances of individuals maintaining several sub-projects.
* A Technical Steering Committee (TSC) provides decision-making and strategic
  oversight for the project.

The [TSC](https://github.com/confidential-containers/community/blob/main/MAINTAINERS)
is composed of individuals from multiple companies (Alibaba, AMD, IBM, Intel,
Red Hat and Rivos):

- [@ariel-adam](https://github.com/ariel-adam), Ariel Adam, RedHat
- [@bpradipt](https://github.com/bpradipt), Pradipta Banerjee, IBM
- [@dcmiddle](https://github.com/dcmiddle), Dan Middleton, Intel
- [@fitzthum](https://github.com/fitzthum), Tobin Feldman-Fitzthum, IBM
- [@jiazhang0](https://github.com/jiazhang0), Zhang Jia, Alibaba
- [@jiangliu](https://github.com/jiangliu), Jiang Liu, Alibaba
- [@larrydewey](https://github.com/larrydewey), Larry Dewey, AMD
- [@magowan](https://github.com/magowan), James Magowan, IBM
- [@peterzcst](https://github.com/peterzcst), Peter Zhu, Intel
- [@sameo](https://github.com/sameo), Samuel Ortiz, Rivos

## Adoption

_What do you know about adoption, and how has this changed since your last review / since you joined Sandbox? If you can list companies that are adopters of your project, please do so._

Cloud Providers (Microsoft, Alibaba, IBM) are pusuring offerings which will include Confidential Containers, they are actively engaged in the community. At recent KubeCon EU Microsoft invited early adopters to sign up to try out confidential containers in Azure.

## Project Goals

### Performance

_How has the project performed against its goals since the last review?_
Taking our last Review as the point we were granted sandbox status we now have a release schedule with release that do deliver enable the use of multiple TEE and hardware platforms to enforce application security requirements with transparent deployment of unmodified containers. 



### Current Goals

_What are the current goals of the project? For example, are you working on major new features? Or are you concentrating on adoption or documentation?_

Current Focus on 

- improving CI/CD and release process
- remove dependance on forks from upstream projects and upstream our requirements
- focus on delivering Use Case solutions


## How Can CNCF Help the Project?

## Incubation Criteria

_Do you think that your project meets the criteria for [incubation](https://github.com/cncf/toc/blob/main/process/graduation_criteria.md#incubating-stage)?_

We have further work to do to reach the adopter threshold for incubation which we would currently expect to achieve

Clearly documented security processes explaining how to report security issues to the project, and describing how the project provides updated releases or patches to resolve security vulnerabilities
