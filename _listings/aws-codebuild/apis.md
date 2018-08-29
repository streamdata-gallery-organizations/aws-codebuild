---
name: AWS CodeBuild
x-slug: aws-codebuild
description: AWS CodeBuild is a fully managed build service that compiles source code,
  runs tests, and produces software packages that are ready to deploy. With CodeBuild,
  you don&rsquo;t need to provision, manage, and scale your own build servers. CodeBuild
  scales continuously and processes multiple builds concurrently, so your builds are
  not left waiting in a queue. You can get started quickly by using prepackaged build
  environments, or you can create custom build environments that use your own build
  tools. With CodeBuild, you are charged by the minute for the compute resources you
  use.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/code-build-console-icon.png
x-kinRank: "10"
x-alexaRank: "0"
tags: AWS CodeBuild
created: "2018-08-29"
modified: "2018-08-29"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codebuild/master/_listings/aws-codebuild/apis.md
specificationVersion: "0.14"
apis:
- name: AWS CodeBuild API - Batch Get Builds
  x-api-slug: actionbatchgetbuilds-get
  description: Gets information about one or more builds.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/code-build-console-icon.png
  humanURL: https://aws.amazon.com/codebuild/
  baseURL: :///
  tags: Amazon Web Services, SDK, Orchestration, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codebuild/master/_listings/aws-codebuild/actionbatchgetbuilds-get-openapi.md
- name: AWS CodeBuild API - Batch Get Projects
  x-api-slug: actionbatchgetprojects-get
  description: Gets information about one or more build projects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/code-build-console-icon.png
  humanURL: https://aws.amazon.com/codebuild/
  baseURL: :///
  tags: Amazon Web Services, SDK, Orchestration, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codebuild/master/_listings/aws-codebuild/actionbatchgetprojects-get-openapi.md
- name: AWS CodeBuild API - Create Project
  x-api-slug: actioncreateproject-get
  description: Creates a build project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/code-build-console-icon.png
  humanURL: https://aws.amazon.com/codebuild/
  baseURL: :///
  tags: Amazon Web Services, SDK, Orchestration, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codebuild/master/_listings/aws-codebuild/actioncreateproject-get-openapi.md
- name: AWS CodeBuild API - Delete Project
  x-api-slug: actiondeleteproject-get
  description: Deletes a build project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/code-build-console-icon.png
  humanURL: https://aws.amazon.com/codebuild/
  baseURL: :///
  tags: Amazon Web Services, SDK, Orchestration, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codebuild/master/_listings/aws-codebuild/actiondeleteproject-get-openapi.md
- name: AWS CodeBuild API - List Builds
  x-api-slug: actionlistbuilds-get
  description: Gets a list of build IDs, with each build ID representing a single
    build.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/code-build-console-icon.png
  humanURL: https://aws.amazon.com/codebuild/
  baseURL: :///
  tags: Amazon Web Services, SDK, Orchestration, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codebuild/master/_listings/aws-codebuild/actionlistbuilds-get-openapi.md
- name: AWS CodeBuild API - List Builds For Project
  x-api-slug: actionlistbuildsforproject-get
  description: Gets a list of build IDs for the specified build project, with each
    build ID representing a single build.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/code-build-console-icon.png
  humanURL: https://aws.amazon.com/codebuild/
  baseURL: :///
  tags: Amazon Web Services, SDK, Orchestration, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codebuild/master/_listings/aws-codebuild/actionlistbuildsforproject-get-openapi.md
- name: AWS CodeBuild API - List Curated Environment Images
  x-api-slug: actionlistcuratedenvironmentimages-get
  description: Gets information about Docker images that are managed by AWS CodeBuild.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/code-build-console-icon.png
  humanURL: https://aws.amazon.com/codebuild/
  baseURL: :///
  tags: Amazon Web Services, SDK, Orchestration, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codebuild/master/_listings/aws-codebuild/actionlistcuratedenvironmentimages-get-openapi.md
- name: AWS CodeBuild API - List Projects
  x-api-slug: actionlistprojects-get
  description: Gets a list of build project names, with each build project name representing
    a single build project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/code-build-console-icon.png
  humanURL: https://aws.amazon.com/codebuild/
  baseURL: :///
  tags: Amazon Web Services, SDK, Orchestration, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codebuild/master/_listings/aws-codebuild/actionlistprojects-get-openapi.md
- name: AWS CodeBuild API - Start Build
  x-api-slug: actionstartbuild-get
  description: Starts running a build.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/code-build-console-icon.png
  humanURL: https://aws.amazon.com/codebuild/
  baseURL: :///
  tags: Amazon Web Services, SDK, Orchestration, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codebuild/master/_listings/aws-codebuild/actionstartbuild-get-openapi.md
- name: AWS CodeBuild API - Stop Build
  x-api-slug: actionstopbuild-get
  description: Attempts to stop running a build.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/code-build-console-icon.png
  humanURL: https://aws.amazon.com/codebuild/
  baseURL: :///
  tags: Amazon Web Services, SDK, Orchestration, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codebuild/master/_listings/aws-codebuild/actionstopbuild-get-openapi.md
- name: AWS CodeBuild API - Update Project
  x-api-slug: actionupdateproject-get
  description: Changes the settings of an existing build project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/code-build-console-icon.png
  humanURL: https://aws.amazon.com/codebuild/
  baseURL: :///
  tags: Amazon Web Services, SDK, Orchestration, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codebuild/master/_listings/aws-codebuild/actionupdateproject-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.code.pipeline.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.codebuild.stack.network
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/reference/codebuild/index.html
- type: x-documentation
  url: http://docs.aws.amazon.com/codebuild/latest/APIReference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/codebuild/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/codebuild/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/codebuild/pricing/
- type: x-website
  url: https://aws.amazon.com/codebuild/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---