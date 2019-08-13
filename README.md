## GSOC - Add Support for Custom Resource Definitions to the Dashboard

Progress tracker for my GSoC project for CNCF &amp; Kubernetes - **Add Support for Custom Resource Definitions to the Dashboard**.

To easier track the progress, I've created a [public Trello board](https://trello.com/b/7jmeonwA) where I'll be providing regular progress updates.

## Abstract

> The Kubernetes dashboard previously supported Third Party Resources (TPR), but these were replaced in Kubernetes by Custom Resource Definitions (CRD). As a result, the original TPR support was removed in Dashboard, but CRD support has not been added yet. This proposal aims at providing a generic support for Custom Resource Definitions to the dashboard, similar to the previous TPR support.

## General Information

Name: Elijah Oyekunle  
E-mail: eloyekunle@gmail.com  
Website and Blog: https://elijahoyekunle.com  
GitHub: [eloyekunle](https://github.com/eloyekunle)  
Slack ([Kubernetes](http://slack.k8s.io/)): eloyekunle  
Twitter: [elijahoyekunle](https://twitter.com/elijahoyekunle)  
Time zone: UTC+01:00 (West Africa Time)  
Mentors: [Marcin Maciaszczyk](https://github.com/maciaszczykm), [Sebastian Florek](https://github.com/floreks)  

## Links

* [Project on GSoC website](https://summerofcode.withgoogle.com/projects/#5700575465832448)
* [Proposal Submitted for GSoC](https://github.com/eloyekunle/gsoc-2019-meta-k8s/raw/master/proposal.pdf)
* [Proposal Draft (Google Doc)](https://docs.google.com/document/d/1YPc5AOO4BciZVrKKi6P1GkdCafZmL14Uy3OFtWyDkQo/edit?usp=sharing)
* [Original Feature Issue](https://github.com/kubernetes/dashboard/issues/2493)
* [Progress Tracker (Trello Board)](https://trello.com/b/7jmeonwA)

## Pull Requests and Issues

The following list is automatically generated using https://github.com/nikhita/github-contrib.

**Repository: kubernetes**

Total Pull Requests Created: 7
1. [kubernetes/kubernetes#81366](https://github.com/kubernetes/kubernetes/pull/81366) - use subtest for table units (pkg/scheduler/internal/cache)
2. [kubernetes/kubernetes#81357](https://github.com/kubernetes/kubernetes/pull/81357) - use subtest for table units (pkg/scheduler/api/compatibility)
3. [kubernetes/kubernetes#81356](https://github.com/kubernetes/kubernetes/pull/81356) - use subtest for table units (pkg/scheduler/algorithmprovider/defaults)
4. [kubernetes/kubernetes#81313](https://github.com/kubernetes/kubernetes/pull/81313) - use subtest for table units (pkg/scheduler/nodeinfo)
5. [kubernetes/kubernetes#81302](https://github.com/kubernetes/kubernetes/pull/81302) - use subtest for table units (pkg/scheduler/util)
6. [kubernetes/kubernetes#75826](https://github.com/kubernetes/kubernetes/pull/75826) - Nit: Fix in deviceplugin api description
7. [kubernetes/kubernetes#73369](https://github.com/kubernetes/kubernetes/pull/73369) - Fixes Golint Errors: staging/src/k8s.io/kube-aggregator

Total Issues Opened: 1
1. [kubernetes/kubernetes#78824](https://github.com/kubernetes/kubernetes/issues/78824) - Field Selector not applied in fake clients List


**Repository: dashboard**

Total Pull Requests Created: 26
1. [kubernetes/dashboard#4189](https://github.com/kubernetes/dashboard/pull/4189) - Improve Namespace-awareness for CRDs
2. [kubernetes/dashboard#4161](https://github.com/kubernetes/dashboard/pull/4161) - CRD - e2e Tests
3. [kubernetes/dashboard#4159](https://github.com/kubernetes/dashboard/pull/4159) - Implement Resource Menu Pinning
4. [kubernetes/dashboard#4156](https://github.com/kubernetes/dashboard/pull/4156) - Show time tooltips for events FirstSeen and LastSeen
5. [kubernetes/dashboard#4155](https://github.com/kubernetes/dashboard/pull/4155) - Implement CRD Objects Events Section
6. [kubernetes/dashboard#4151](https://github.com/kubernetes/dashboard/pull/4151) - Use binary search in getLineIndex method
7. [kubernetes/dashboard#4130](https://github.com/kubernetes/dashboard/pull/4130) - Add context menus in list views for cluster resources
8. [kubernetes/dashboard#4103](https://github.com/kubernetes/dashboard/pull/4103) - Make Resource information card title consistent
9. [kubernetes/dashboard#4030](https://github.com/kubernetes/dashboard/pull/4030) - CRD Support - Frontend
10. [kubernetes/dashboard#4002](https://github.com/kubernetes/dashboard/pull/4002) - Migrate e2e tests to Cypress
11. [kubernetes/dashboard#3995](https://github.com/kubernetes/dashboard/pull/3995) - Add go modules verification and update scripts
12. [kubernetes/dashboard#3994](https://github.com/kubernetes/dashboard/pull/3994) - Nit: Update comment in Github PR template
13. [kubernetes/dashboard#3938](https://github.com/kubernetes/dashboard/pull/3938) - Download golangci-lint via curl
14. [kubernetes/dashboard#3886](https://github.com/kubernetes/dashboard/pull/3886) - Update to client-go kubernetes-1.14.0
15. [kubernetes/dashboard#3885](https://github.com/kubernetes/dashboard/pull/3885) - Update go-restful to the latest version
16. [kubernetes/dashboard#3878](https://github.com/kubernetes/dashboard/pull/3878) - Migrate from dep to go mod
17. [kubernetes/dashboard#3877](https://github.com/kubernetes/dashboard/pull/3877) - Remove redundant namespace filters
18. [kubernetes/dashboard#3843](https://github.com/kubernetes/dashboard/pull/3843) - CRD Support - Backend
19. [kubernetes/dashboard#3810](https://github.com/kubernetes/dashboard/pull/3810) - Update style format message to correct npm script
20. [kubernetes/dashboard#3630](https://github.com/kubernetes/dashboard/pull/3630) - Replace history when the log page appends container param
21. [kubernetes/dashboard#3590](https://github.com/kubernetes/dashboard/pull/3590) - Switch chart engine from nvd3 to c3
22. [kubernetes/dashboard#3586](https://github.com/kubernetes/dashboard/pull/3586) - Fix bug in CPU allocation chart
23. [kubernetes/dashboard#3562](https://github.com/kubernetes/dashboard/pull/3562) - Display query in search bar after namespace change and page reload
24. [kubernetes/dashboard#3561](https://github.com/kubernetes/dashboard/pull/3561) - Logs Auto Scroll
25. [kubernetes/dashboard#3559](https://github.com/kubernetes/dashboard/pull/3559) - Added tooltip for Timestamp icon on Logs page
26. [kubernetes/dashboard#3558](https://github.com/kubernetes/dashboard/pull/3558) - Show light-colored scrollbar in dark logs mode

Total Issues Opened: 10
1. [kubernetes/dashboard#4167](https://github.com/kubernetes/dashboard/issues/4167) - Support 'Scale' subresource for CRDs
2. [kubernetes/dashboard#4153](https://github.com/kubernetes/dashboard/issues/4153) - [Parent Issue]: Add e2e Tests
3. [kubernetes/dashboard#4123](https://github.com/kubernetes/dashboard/issues/4123) - Implement CRD Object Detail Page
4. [kubernetes/dashboard#4027](https://github.com/kubernetes/dashboard/issues/4027) - Enable Angular Ivy
5. [kubernetes/dashboard#3993](https://github.com/kubernetes/dashboard/issues/3993) - Verify vendored modules in pull requests
6. [kubernetes/dashboard#3884](https://github.com/kubernetes/dashboard/issues/3884) - Upgrade go-restful to latest version
7. [kubernetes/dashboard#3631](https://github.com/kubernetes/dashboard/issues/3631) - Show tooltip timestamp on time hover across pages
8. [kubernetes/dashboard#3585](https://github.com/kubernetes/dashboard/issues/3585) - Misplaced labels on the Nodes CPU allocation chart
9. [kubernetes/dashboard#3567](https://github.com/kubernetes/dashboard/issues/3567) - Prevent page exit on the create page when there are unsaved changes
10. [kubernetes/dashboard#3557](https://github.com/kubernetes/dashboard/issues/3557) - Logs scrollbar not showing in dark mode

Total Pull Requests Reviewed: 1
1. [kubernetes/dashboard#3767](https://github.com/kubernetes/dashboard/pull/3767) - Show tooltip timestamp on time hover across pages


**Repository: minikube**

Total Pull Requests Created: 1
1. [kubernetes/minikube#3715](https://github.com/kubernetes/minikube/pull/3715) - Fix code block highlight in README


**Repository: community**

Total Pull Requests Created: 1
1. [kubernetes/community#3797](https://github.com/kubernetes/community/pull/3797) - Update meeting time for SIG-UI Bi-Weekly
