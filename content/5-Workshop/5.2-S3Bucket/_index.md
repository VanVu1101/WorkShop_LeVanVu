---
title: "S3 Bucket"
date: 2026-04-17
weight: 1
chapter: false
pre: " <b> 5.2. </b> "
---

#### S3 Configuration Report

This section documents the completed Amazon S3 setup for the internship management system.

Completed tasks:

- Created an S3 bucket named `my-app-uploads-2026-tri`.
- Established the following folder structure within the bucket:
  - `student-profile/`
  - `student-profile/2/`
  - `student-profile/3/`
  - `weekly-report-templates/1/`

Implementation details:

1. Logged into AWS Management Console and navigated to Amazon S3.
2. Chose **Create bucket** and entered the bucket name `my-app-uploads-2026-tri`.
3. Selected the appropriate AWS Region and kept the default settings suitable for the workshop.
4. Applied standard internal **Block Public Access** settings to maintain security.
5. Created the main folders `student-profile/` and `weekly-report-templates/`.
6. Added child folders `student-profile/2/`, `student-profile/3/`, and `weekly-report-templates/1/` to support data organization.

Business purpose:

- `student-profile/`:
  - Stores student profile images and related media files.
  - Supports upload and retrieval of student profile data.
- `weekly-report-templates/`:
  - Stores weekly report template files used by the web application.
  - Supports download and reuse of report templates.

Results:

- Bucket `my-app-uploads-2026-tri` was successfully created and verified.
- The folder structure is now clearly organized and ready for application use.
- The S3 environment is prepared for file upload and data storage workflows.
- The structure can be expanded later with additional prefixes as the system grows.

#### Reference images

- S3 bucket overview.

![S3 bucket overview](/images/s3.png)

- `student-profile/` folder and the `2/`, `3/` subfolders.

![S3 student-profile folder](/images/s3-1.jpg)

- `weekly-report-templates/` folder and the `1/` subfolder.

![S3 weekly-report-templates folder](/images/s3-2.jpg)

- Full bucket folder structure.

![S3 folder structure](/images/s3-3.jpg)
![S3 uploads hình ảnh file ... lên aws s3](/images/3-4s3.jpg)
