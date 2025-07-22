# Update Deployment Branch

This branch outlines the changes that will be included in the next update. Before triggering the expo-updates-deploy-to-production job, please ensure the following tasks are completed.

## To-Do

- [ ] Verify Version: Check the [base branch version ](https://github.com/ornikar/instructors-app/blob/native-release-tag-ci-owned-branch/%40ornikar/instructor-native-app/.env.production#L3). It should match the version currently released on the Google Play Store and Apple App Store.
- [ ] Review Pull Request Diffs: Carefully examine the changes included in the pull request.
- [ ] Local Testing: Run the code locally on both Android and iOS to confirm the fix is working as expected.

## Deploying Updates

To deploy the update, trigger the expo-updates-deploy-to-production job. Only members of the [Expo Updates Production Deployment Owners team ](https://github.com/orgs/ornikar/teams/expo-updates-production-deployment-owners)have permission to do so.

## Monitor Updates

https://expo.dev/accounts/ornikar-org/projects/instructor-native-app/channels/production

## Rollback

If issues arise after deployment, you can rollback the updates: https://docs.expo.dev/eas-update/rollbacks/
