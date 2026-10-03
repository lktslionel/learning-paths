# Week 2 – Single-Room Scanner (Practice)

**Time:** 4 hours  
**Type:** Practice  
**Goal:** Ship a working single-room capture + USDZ export flow inside HomeTwin.

---

## Schedule

| Block              | Duration | Activity |
|--------------------|----------|----------|
| Project Setup      | 30 m     | Create HomeTwin Xcode project |
| Core Implementation| 2 h      | RoomCaptureView + export |
| Testing & Polish   | 1 h      | Real-device testing |
| Documentation      | 30 m     | Code comments + notes |

---

## Required Resources

1. Sample project (use as reference)  
   https://developer.apple.com/documentation/roomplan/create_a_3d_model_of_an_interior_room_by_guiding_the_user_through_an_ar_experience

2. RoomPlan API reference  
   https://developer.apple.com/documentation/roomplan

3. WWDC22 session (re-watch key parts if needed)  
   https://developer.apple.com/videos/play/wwdc2022/10127/

---

## Tasks

1. Create a new iOS App project named **HomeTwin** (SwiftUI).
2. Add the necessary Info.plist entries (Camera + AR).
3. Implement a scanning screen using `RoomCaptureView`.
4. On scan completion:
   - Receive `CapturedRoom`
   - Show a simple preview
   - Export to USDZ (parametric option)
5. Add a “Share USDZ” button.
6. Test on a real LiDAR device with at least two different rooms.

---

## Success Criteria
- [ ] App launches and shows the RoomPlan coaching UI
- [ ] Successful scan produces a valid USDZ file
- [ ] File can be opened in Quick Look / Files app
- [ ] Basic error handling for scan cancellation / failure

---

## Deliverable
Working single-room scanner committed to your repo + short demo video or screenshots.