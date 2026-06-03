## Android permissions "ask every time" issue

### Summary

When you request camera permissions, but select "only this time", even though app settings show that the permission must be requested every time, the permission is always granted and never asks again.

### How to reproduce
1. `bun install`
2. `npx expo run:android`
3. Go to camera tab
4. Grant permissions "only this time"
5. Swipe app closed
6. Reopen
7. Go to camera tab
8. Camera shows up

### Expected behavior
On second open, you should need to grant permissions again.
