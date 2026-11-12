# Technical Charter for the E2BGateway Open Source Project

<!-- toc -->
- [1. Mission and Scope of the Project](#1-mission-and-scope-of-the-project)
- [2. Technical Steering Committee](#2-technical-steering-committee)
- [3. TSC Voting](#3-tsc-voting)
- [4. Compliance with Policies](#4-compliance-with-policies)
- [5. Community Assets](#5-community-assets)
- [6. Intellectual Property Policy](#6-intellectual-property-policy)
- [7. Amendments](#7-amendments)
<!-- /toc -->

This Charter sets forth the responsibilities and procedures for technical contribution to, and
oversight of, the e2bgateway open source project (the "Project"). All contributors (including
committers, maintainers, and other technical positions) and other participants in the Project
(collectively, "Collaborators") must comply with the terms of this Charter.

## 1. Mission and Scope of the Project

a. The mission of the Project is to provide a unified gateway that enables the official E2B
client to interoperate with multiple agent runtimes, delivering standardized sandbox APIs
for AI agents across runtimes and environments.

b. The scope of the Project includes collaborative development under the Project License
(as defined herein) supporting the mission, including documentation, testing, integration
and the creation of other artifacts that aid the development, deployment, operation or
adoption of the open source project.

## 2. Technical Steering Committee

a. The Technical Steering Committee (the "TSC") will be responsible for all technical
oversight of the open source Project.

b. The TSC voting members are initially the Project's Maintainers, as set forth in the
[MAINTAINERS.md](MAINTAINERS.md) file within this repository. The TSC may choose an
alternative approach for determining the voting members of the TSC, and any such
alternative approach will be documented in this repository. Any meetings of the Technical
Steering Committee are intended to be open to the public, and can be conducted
electronically, via teleconference, or in person.

c. TSC projects generally will involve Contributors and Maintainers. The TSC may adopt or
modify roles so long as the roles are documented in the [CONTRIBUTOR_LADDER.md](CONTRIBUTOR_LADDER.md)
file. Unless otherwise documented:

- Contributors include anyone in the technical community that contributes code,
  documentation, or other technical artifacts to the Project;
- Reviewers are established Contributors who regularly participate in the project and have
  been granted review privileges in project repositories;
- Maintainers are Contributors who have earned the ability to modify ("commit") source
  code, documentation or other technical artifacts in a project's repository; and
- A Contributor may become a Reviewer or Maintainer following the process documented in
  the [CONTRIBUTOR_LADDER.md](CONTRIBUTOR_LADDER.md) file. A Maintainer may be removed by
  a majority approval of the TSC.

d. Participation in the Project through becoming a Contributor and Maintainer is open to
anyone so long as they abide by the terms of this Charter.

e. The TSC may (1) establish work flow procedures for the submission, approval, and
closure/archiving of projects, (2) set requirements for the promotion of Contributors to
Reviewer or Maintainer status, as applicable, and (3) amend, adjust, refine and/or
eliminate the roles of Contributors, Reviewers, and Maintainers, and create new roles, and
publicly document any TSC roles, as it sees fit.

f. The TSC may elect a TSC Chair, who will preside over meetings of the TSC and will serve
until their resignation or replacement by the TSC.

g. Responsibilities: The TSC will be responsible for all aspects of oversight relating to
the Project, which may include:

- coordinating the technical direction of the Project;
- approving project or system proposals (including, but not limited to, incubation,
  deprecation, and changes to a sub-project's scope);
- organizing sub-projects and removing sub-projects;
- creating sub-committees or working groups to focus on cross-project technical issues and
  requirements;
- appointing representatives to work with other open source or open standards communities;
- establishing community norms, workflows, issuing releases, and security issue reporting
  policies;
- approving and implementing policies and processes for contributing (to be published in
  the [CONTRIBUTION.md](CONTRIBUTION.md) file);
- discussions, seeking consensus, and where necessary, voting on technical matters
  relating to the code base that affect multiple projects; and
- coordinating any marketing, events, or communications regarding the Project.

## 3. TSC Voting

a. While the Project aims to operate as a consensus-based community, if any TSC decision
requires a vote to move the Project forward, the voting members of the TSC will vote on a
one vote per voting member basis.

b. Quorum for TSC meetings requires at least fifty percent of all voting members of the
TSC to be present. The TSC may continue to meet if quorum is not met but will be prevented
from making any decisions at the meeting.

c. Except as provided in Sections 3.d and 6.c, decisions by vote at a meeting require a
majority vote of those in attendance, provided quorum is met. Decisions made by electronic
vote without a meeting require a majority vote of all voting members of the TSC.

d. In the event a vote cannot be resolved by the TSC, the TSC Chair (or, if no Chair has
been elected, any voting member of the TSC) may seek assistance from the community in
reaching a resolution.

## 4. Compliance with Policies

a. The TSC may adopt a code of conduct ("CoC") for the Project. The current CoC is
published at [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).

b. All Collaborators must allow open participation from any individual or organization
meeting the requirements for contributing under this Charter and any policies adopted for
all Collaborators by the TSC, regardless of competitive interests. Put another way, the
Project community must not seek to exclude any participant based on any criteria,
requirement, or reason other than those that are reasonable and applied on a
non-discriminatory basis to all Collaborators in the Project community.

c. The Project will operate in a transparent, open, collaborative, and ethical manner at
all times. The output of all Project discussions, proposals, timelines, decisions, and
status should be made open and easily visible to all.

## 5. Community Assets

a. The Project maintains its source code, documentation, GitHub organization
(https://github.com/e2bgateway), and other community assets for the benefit of the
community as a whole.

b. Any use of the Project's name, logo, or trademarks by Collaborators should be
reasonable and must not imply endorsement by the Project.

## 6. Intellectual Property Policy

a. Collaborators acknowledge that the copyright in all new contributions will be retained
by the copyright holder as independent works of authorship and that no contributor or
copyright holder will be required to assign copyrights to the Project.

b. Except as described in Section 6.c., all contributions to the Project are subject to
the following:

- All new inbound code contributions to the Project must be made using the Apache License,
  Version 2.0, available at http://www.apache.org/licenses/LICENSE-2.0 (the "Project
  License").
- All new inbound code contributions must also be accompanied by a Developer Certificate
  of Origin (http://developercertificate.org) sign-off in the source code system that is
  submitted through a TSC-approved contribution process which will bind the authorized
  contributor and, if not self-employed, their employer to the applicable license.
- All outbound code will be made available under the Project License.
- Documentation will be received and made available by the Project under the Project
  License.
- The Project may seek to integrate and contribute back to other open source projects
  ("Upstream Projects"). In such cases, the Project will conform to all license
  requirements of the Upstream Projects, including dependencies, leveraged by the Project.
  Upstream Project code contributions not stored within the Project's main code repository
  will comply with the contribution process and license terms for the applicable Upstream
  Project.

c. The TSC may approve the use of an alternative license or licenses for inbound or
outbound contributions on an exception basis. To request an exception, please describe the
contribution, the alternative open source license(s), and the justification for using an
alternative open source license for the Project. License exceptions must be approved by a
two-thirds vote of the entire TSC.

d. Contributed files should contain license information, such as SPDX short form
identifiers, indicating the open source license or licenses pertaining to the file.

## 7. Amendments

a. This charter may be amended by a two-thirds vote of the entire TSC.
