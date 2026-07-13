The dataset is this https://www.youtube.com/watch?v=eRWzYPUJsvc 
and made it into 

https://github.com/user-attachments/assets/86cc90e3-bfaf-4e18-955b-33077523bfbe

and recreated the set into the path as the this <img width="1870" height="1030" alt="Open3D 7_9_2026 5_29_41 AM" src="https://github.com/user-attachments/assets/2f7ce71f-3975-4d37-a21c-34537b9042d3" />

and given the way and total recreation of the status Azerbaijan Grand Prix into this <img width="1920" height="991" alt="Open3D 11_19_2025 2_02_21 AM" src="https://github.com/user-attachments/assets/f0804006-7ffd-48c5-9210-c9877fea9b11" />
and made this into a more contrast on this and made this small mistake of the curves of track into<img width="1920" height="991" alt="Project suggestion options - Google Chrome 11_19_2025 12_45_14 AM" src="https://github.com/user-attachments/assets/8752875f-159f-4eac-a3c8-e1cfb9cd5c33" />
Project Summary
The following document contains a full Work Breakdown Structure (WBS) for the VROOM project, which is an application that can create a 3D reconstruction of the Monaco Formula 1 circuit based on video footage shot by an onboard monocular camera. The WBS adheres to a three-level scheme of work breakdown structure items: Data Ingestion & Preprocessing, Formula Analysis & Constraints, and Model Architecture & Implementation.

WBS Item	VROOM Equivalent	Status
Dataset / Problem	1920×1080 @ 50fps onboard video → 3D point cloud + camera trajectory	Completed
Raw Data Issue	Car body in frame, scale uncertainty, GPU memory constraints, dynamics of the scene	Resolved
Transformation Technique	Crop upper half, rescale, time subsampling, 0/1 confidence filtering	Completed
Key Formula	Pointmap prediction, global alignment energy, Umeyama similarity	Implemented
Constraints Implemented	FPS minimum, chunk size, overlap number, confidence percentile filtering	Tuned
Model Used	DUSt3R (ViT-Large) → MonST3R (with optical flow)	Running
