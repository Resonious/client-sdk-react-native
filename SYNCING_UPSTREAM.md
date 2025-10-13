# Syncing upstream

This a quick guide for how to sync @baillie/client-sdk-react-native with @livekit/client-sdk-react-native.

0. Sync @baillie/react-native-webrtc first.
1. Sync `main` of this fork with upstream.
2. Checkout `bg` and then run `git merge main`.
3. Fix conflicts.
  1. The name of this package in package.json ought to start with @baillie/ instead of @livekit/.
  2. To fix yarn.lock, run `git checkout --theirs yarn.lock`, then `yarn`.
4. Push.
