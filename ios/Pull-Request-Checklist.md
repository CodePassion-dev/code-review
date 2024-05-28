# PR Templete / Checklist:

Please complete this template before creating the pull request.

- [ ] Story / Defect ID | Title / One line description.
- [ ] Details description about pull request.
- [ ] UI design / Figma link.
- [ ] Test data / environment used for testing the changes.
- [ ] UI screenshots for new added / modified code.
- [ ] Testing video after code changes (if possible).
- [ ] Unit Tests passed screenshot.
- [ ] List out any dependencies / future updates needed.
- [ ] Note to reviewers if needed.
- [ ] Self review code in local before commit & push?
- [ ] SwiftLint checked / corrected?

# Examples Of A Pull Request Description:

### ABC-123 | Add Login Screen v2.0

Added new Login Screen v2.0, tested on both iPhone and iPad, landscape and portrait. Dark Mode and Light Mode will provide different looks, please check attached screenshots and captured videos.

Design Link: https://figma.com/

Test Data: dev1_1234 / password - DEV1 environment.

Screenshots:

![](https://cdn.dribbble.com/users/308682/screenshots/15247701/media/719a98526d1ab8cd2b5f27bb5b3e1eef.jpg?resize=400x0)
![](https://mir-s3-cdn-cf.behance.net/projects/404/5f3481157906697.Y3JvcCwxNTM0LDEyMDAsMzQsMA.jpg)

Dev Testing video:

Unit Tests:

Dependencies / future updates needed:

- Need to confirm button title is `Login` or `Sign In`?
- Need to confirm error message text for network failed case.
- Move text to CMS, hardcoded string currently.

Note to reviewers:

- DEV1 environment is not working stable, need to test again when issue resolved.
- ADA is not working correctly on iPad 9.7, need to discuss on it.

- [x] Self review code in local before commit & push.
- [x] SwiftLint checked / corrected.

# Notes:

- The reviewers only start to review the Pull Request when all the items on the checklist has been marked as completed.
- Reach out to Dev Lead / Default Reviewers for any suggestion / blocking / optimize the pull request.
- Don't feel bad when the PR has been marked as Need Work, we ...
- Reply `Done` to each comments that has been addressed, that's would be easier for everyone to follow the pull request status.
