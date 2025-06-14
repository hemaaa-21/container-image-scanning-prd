# Product Requirements Document

Title: Vulnerability Scanner for Container Images

Background: Security teams need to scan container images to detect vulnerabilities. 
            Users need help understanding which images have problems and how severe those problems are.

Objective: Build a simple user interface that helps users scan thousands of container images, identify vulnerabilities, 
           and understand how severe they are so they can fix the most important issues first.

Goals:
- Help users view vulnerabilities in container images
- Help users decide which images need fixing
- Easy-to-understand interface.

User Stories:
- As a user, I want to know which images have vulnerabilities and their severity
- As a user, I want to prioritize fixing the most severe issues
- As a user, I have thousands of images and need a clear way to filter them

Requirements:
- Upload and scan container images
- Show list of vulnerabilities per image
- Display severity (Low/Medium/High/Critical)
- Search and filter images

Non-Functional Requirements:
- Should support thousands of images.
- Fast response time (<2s for filter or search).
- Secure upload and scanning.
- Responsive UI (works on desktop and mobile).

Constraints:
- Large number of images
- Performance must be good for large datasets

Out of Scope:
- Actual fixing of vulnerabilities
- In-depth scan customization by user