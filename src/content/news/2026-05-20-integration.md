---
title: "Progress of Integration (Continuously updating)"
date: "2026-05-20"
author: "Derui Tang"
summary: Recording the progress of the whole project's integration. This news will be continuously updated as the situation may change.
latest: true
---

# After testing the BLE module of the S1 team, we are going to test the whole project while integrating.

This progress will be recorded in the following table.

| Date | Author | Description |
| :--- | :--- | :--- |
| May 5 | Derui Tang | Asked the programmers to provide the final product of S1 team's BLE module, but was told that there were still a lot of bugs. |
| May 6 | Derui Tang | Derui Tang tried to help the programmers develop BLE connection on HarmonyOS, but he finally found that the development tools do not support the low-level HarmonyOS we are currently using. Derui Tang asked for other students' help in the WeChat course group. |
| May 7 | Derui Tang | Told programmers of S1, S2, and M1 to return to development on Windows first and produce a working version on Windows. In addition, Derui Tang asked for Mentor Zhang's help with the HarmonyOS problem after class and got some possible solutions. |
| May 10 | Derui Tang | Derui Tang was continuously communicating with S2 and M1 to clarify our implementation details for the last 3 days. He also found some mistakes in the data transport format between S2 and V2. Besides those, he collected over 30 statistical samples using the Windows version and asked V1 to develop their AI application. |
| May 11 | Derui Tang | Derui Tang got the HarmonyOS device offered by Mentor Zhang. He tried to use the device to test the connection with the BLE device for the whole day, but could not resolve it because the BLE device was not allowed to connect to HarmonyOS. He consulted the BLE device manufacturer and was told that the product does not support HarmonyOS. He decided to return to development on Android and confirmed with Mentor Zhang. |
| May 13 | Derui Tang | Derui Tang was continuously communicating with S2 and M2 to clarify our implementation details. He also found some mistakes in the data transport format between S2 and V2. |
| May 14 | Derui Tang | M1's PM informed Derui Tang that one version of the application was completed. Derui Tang had no Android device, so he asked Mofan Xu to test the app according to M1's test cases. |
| May 16 | Derui Tang | The web side of M2 has passed the Alpha and Beta tests. However, the data provided by V1's AI was still missing. It is known that there were a few mistakes in the implementation between S2 and V1. I asked Zhiqi Zhang from S2 and Mofan Xu from S1 to communicate with V1 and waited for their response. |
| May 20 | Derui Tang | To better secure the sensors, Derui Tang decided to buy a few Velcro straps on Taobao. |
| May 21 | Derui Tang | The Phase 2 requirements were released. Our S1 team is responsible for confirming the workflow of data collection and providing raw standard data for V1's AI system. |
| May 22 | Derui Tang | Since the Android version had not been fully developed, Derui Tang tried to collect raw data using the earlier Windows version. As V1's AI needed clean session data, Derui Tang modified the code logic of the Windows collector, adding start and end options for data collection while the sensors were connected. Derui Tang spent 1.5h collecting 25 groups of clean raw walking data and sent them to Yanbo Qiao from V1, who then forwarded them to their team's programmer. We hoped this data would be helpful for developing the AI. Derui Tang also chatted with Yiding Wang about the workflow of data collection. Yiding Wang recommended that they complete the workflow through M1, which was in line with our expectations. I called Mofan Xu, our programmer, to keep in touch with Yiding Wang to complete the merge of the sensor and app sides. |
| May 23 | Derui Tang | Derui Tang spent 3h in total collecting 20 groups of squat data. As the sensors were not sensitive enough, it took Derui Tang considerable time to deal with the sensor connections. Finally he obtained those groups of data and sent them to Yanbo Qiao from V1, but was sadly told that their team's programmer was busy with his own business. Yanbo Qiao actively took on the task of building the AI system, and we hope the development of the AI for walking and squat can be completed soon. |
| May 25 | Derui Tang | Derui Tang was busy with CCPC on May 24 and returned to the DSD work today. Fortunately, the Velcro straps arrived today and greatly helped with securing the sensors and collecting data. He first spent a total of 2h collecting 26 groups of clean stair climbing data, and sent them to Yanbo Qiao, who informed him that the fitted curve system had been successfully built. He then asked Mofan Xu about the progress of merging our app by S1 and M1, but was sadly told that the current product provided by M1 only supported the frontend and could only connect to one sensor. Derui Tang was also told that M1 had lost contact with their backend programmer, so the app might not be fully developed before May 27. Derui Tang decided to let Mofan Xu keep testing the sensor connection code written by our team, and to try testing the backend-only Android app we developed with S2 a few days ago. |
| June 09 | Derui Tang | Derui Tang published one version of integration testing code on Github. |
