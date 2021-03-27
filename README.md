 # Kubernetes Working Group for Multi-Tenancy

This is a working place for multi-tenancy related proposals and prototypes. To
join our biweekly meetings, Slack, mailing list, [please visit our community
page](https://github.com/kubernetes/community/blob/master/wg-multitenancy/README.md).

## Projects

This repo contains the following projects:

* **[Benchmarks](benchmarks/):** a set of benchmarks (i.e., compliance
  tests) to determine if your clusters are well-configured for multitenancy.
* **[Hierararchical namespaces (aka HNC)](incubator/hnc/):** allows
  namespaces to own each other, policy propagation between related namespaces,
  and delegated namespace creation.
* **[Tenant Operator](tenant/):** an opinionated solution to manage tenants
  within a cluster.
* **[Virtual clusters](incubator/virtualcluster):** run multiple virtualized
  cluster on a single underlying cluster, allowing for hard(er) multitenancy.

As these projects mature, they may be adopted by a SIG and moved to their own
repos.

## Resources

The [docs](docs/)  directory contains any documents written in markdown. Some
draft docs which need collaboration are Google docs for better collaboration
experience. The [links](docs/links.md) file contains links to all presentations,
wg-multitenancy minutes, and other docs not directly related to the projects
above.

## Join this repo

File a request at https://github.com/kubernetes/org to be added to
@kubernetes-sigs, using the
[Template](https://github.com/kubernetes/org/issues/new?template=membership.md&title=REQUEST%3A%20New%20membership%20for%20%3Cyour-GH-handle%3E).

Once you've been a member, when you are ready to become a reviewer of other
people's code, file a PR on our [OWNERS
file](https://github.com/kubernetes-sigs/multi-tenancy/blob/master/OWNERS) and
an approver will need to approve you.

Once you've been a reviewer, you can request to become an approver by filling a
PR on our OWNERS file and another approver will need to approve you.

### [Deprecated] PoC directory

The `poc` directory contains *deprecated* _proof-of-concept_ code which is not supported.

### Code of conduct

Participation in the Kubernetes community is governed by the [Kubernetes Code of Conduct](code-of-conduct.md).
