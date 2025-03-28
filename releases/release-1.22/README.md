---
title: "Kubernetes 1.22 Release Information"
weight: 98
slug: "release"
aliases: [ "/release" ]
description: |
  Information regarding the current release cycle including important dates,
  Release Team contact information, tracking spreadsheets and more!
---

# Kubernetes 1.22

#### Links

* [This document](https://git.k8s.io/sig-release/releases/release-1.22/README.md)
* [Release Team](https://github.com/kubernetes/sig-release/blob/master/releases/release-1.22/release-team.md)
* Meeting Minutes: TODO (join [kubernetes-sig-release@] to receive meeting invites)
* [v1.22 Release Calendar][k8s122-calendar]
* Contact: [#sig-release] on slack, [kubernetes-release-team@] on e-mail
* [Internal Contact Info][Internal Contact Info] (accessible only to members of [kubernetes-release-team@])

#### Tracking docs

* Enhancements Tracking Sheet: TODO
* Bug Triage Tracking Sheet: TODO
* CI Signal Report: TODO
* [Retrospective Document][Retrospective Document]
* [kubernetes/sig-release v1.22 milestone](https://github.com/kubernetes/kubernetes/milestone/50)

#### Guides

* [Targeting Issues and PRs to This Milestone](https://git.k8s.io/community/contributors/devel/sig-release/release.md)
* [Triaging and Escalating Test Failures](https://git.k8s.io/community/contributors/devel/sig-testing/testing.md#troubleshooting-a-failure)

## TL;DR

TBD

## Timeline

| **What** | **Who** | **When** | **WEEK** | **CI SIGNAL** |
|---|---|-------|---|---|
| Start of Release Cycle | Lead | Mon April 26 | week 1 | [master-blocking] |
| Start Enhancements Tracking | Enhancements Lead | TBD | TBD | |
| 1.22.0-alpha.1 released | Branch Manager (TBD) | TBD  | TBD | |
| Schedule finalized | Lead | TBD | TBD | |
| Team finalized | Lead | TBD | TBD | |
| 1.22.0-alpha.2 released | Branch Manager (TBD) | TBD | TBD | |
| KubeCon EU + Co-located events | | May 3-7 | | |
| **Begin [Enhancements Freeze]** (Time TBD) | Enhancements Lead | TBD | TBD | [master-blocking], [master-informing] |
| 1.22.0-alpha.3 released | Branch Manager (TBD) | TBD | TBD | |
| 1.22.0-beta.0 released | Branch Manager (TBD) | TBD | TBD | |
| **Begin [Burndown]** (MWF meetings) | Lead | TBD | TBD | [1.22-blocking], [master-blocking], [master-informing] |
| **Call for [Exceptions][Exception]** | Lead | TBD | TBD | |
| Brace Yourself, Code Freeze is Coming | Comms / Bug Triage | TBD | TBD | |
| **Begin Feature blog freeze** | Comms Lead | TBD | TBD | |
| 1.22.0-beta.1 released | Branch Manager (TBD) | TBD | TBD | |
| **Begin [Code Freeze]** (Time TBD) | Branch Manager | TBD | TBD | |
| Burndown Meetings daily| Lead | TBD | TBD | |
| Docs deadline - Open placeholder PRs | Docs Lead | TBD | TBD | |
| **[Test Freeze]** (Time TBD) | Branch Manager | TBD | TBD | |
| Docs deadline - PRs ready for review | Docs Lead | TBD | TBD | |
| 1.22.0-rc.0 released | Branch Manager (TBD) | TBD | TBD | |
| release-1.22 branch created | Branch Manager | TBD | TBD | |
| release-1.22 jobs created | Branch Manager | TBD | TBD | |
| Start final draft of Release Notes | Release Notes Lead | TBD | TBD | |
| Release blog ready to review | Comms / Docs | TBD | TBD | |
| Docs complete - All PRs reviewed and ready to merge | Docs Lead | TBD | TBD | |
| Feature blogs ready to review | Enhancement Owner / SIG Leads | TBD | TBD | |
| Release Notes complete - reviewed & merged to `k/sig-release` | Release Notes Lead | TBD | TBD | |
| **v1.22.0 released** | Branch Manager (TBD) | TBD | TBD | |
| Release blog published | Comms | TBD | TBD | |
| **[Thaw]** | Branch Manager | TBD | TBD | |
| Release retrospective | Community | TBD | TBD | |

## Phases

Please refer to the [release phases document](../release_phases.md).

[k8s122-calendar]: https://bit.ly/k8s-release-cal
[Internal Contact Info]: TBD
[Retrospective Document]: TBD

[Enhancements Freeze]: ../release_phases.md#enhancements-freeze
[Burndown]: ../release_phases.md#burndown
[Code Freeze]: ../release_phases.md#code-freeze
[Exception]: ../release_phases.md#exceptions
[Thaw]: ../release_phases.md#thaw
[Test Freeze]: ../release_phases.md#test-freeze

[kubernetes-release-team@]: https://groups.google.com/a/kubernetes.io/g/release-team
[kubernetes-sig-release@]: https://groups.google.com/forum/#!forum/kubernetes-sig-release
[#sig-release]: https://kubernetes.slack.com/messages/sig-release/
[kubernetes-release-calendar]: https://bit.ly/k8s-release-cal
[kubernetes/kubernetes]: https://github.com/kubernetes/kubernetes

[master-blocking]: https://testgrid.k8s.io/sig-release-master-blocking#Summary
[master-informing]: https://testgrid.k8s.io/sig-release-master-informing#Summary
[1.22-blocking]: https://testgrid.k8s.io/sig-release-1.22-blocking#Summary

[exception requests]: ../EXCEPTIONS.md
[release phases document]: ../release_phases.md
