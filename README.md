# PICO-URP-Fork
PICO's fork of Unity's Universal Rendering Pipeline (URP) official staging branch (2022.3.14f1) to add performance optimization and customization features for XR headsets.

# Blog post
For more details on how to use the package, visit:
https://developer.picoxr.com/news/urp-fork/

# Main Updates
<img width="554" alt="img_v3_02go_111519a2-335c-4328-b102-65b6769150hu" src="https://github.com/user-attachments/assets/e3486f49-6a6c-4431-940a-f6ceeffd214a">

## Bloom

![image](https://github.com/user-attachments/assets/b7bd344e-3863-4942-8ba5-2b77c790eec8)

## Shadow

![image](https://github.com/user-attachments/assets/1de540a8-9ff8-4961-a557-715b411e5f2a)

## Adaptive Resolution Bug Fix
We fixed issues where max adaptive resolution scale was being clamped to 1.0 resulting in a default eye texture resolution. With this fix, developers can increase image quality using adaptive resolution feature by allowing max adaptive resolution scale > 1.

## Shadergraph Multiview Bug Fix

![image](https://github.com/user-attachments/assets/2ed1d537-bb0b-45a0-8753-8212758bd36c)
