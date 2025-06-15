# 🎬 Order in Chaos : Video Frame Sorting

> Reconstruct the story — one frame at a time.
---
![gif](https://github.com/njack-muffin/Order-in-Chaos/blob/main/shuffling.gif)
## 🧠 About the Challenge

In this machine learning competition, your task is to **sort shuffled video frames** back into their correct chronological order.  
It's a unique challenge that blends **computer vision**, **temporal modeling**, and **sequence learning**.

Think you can teach a machine to understand time or sequence?

You are allowed to participate as an **individual** or as a **team**.

---

## 🔍 Problem Statement

Given a set of shuffled frames extracted from a video:

- **Input**: N unordered image frames from a single video.
- **Output**: The correct chronological sequence of those frames (as indices or filenames).

---

## 🗂 Dataset

- 📦 **Dataset Format**: 
  - `Feature Templates/`: A folder with some provided features
  - `Randomized Images/`: A folder with images (e.g., 001.jpg, 002.jpg, ...)
  - `Readme.txt`: Some important information. 

- 📥 **Download Dataset**:  &nbsp; [**Link1**](https://cciitpatna-my.sharepoint.com/:u:/g/personal/soumabho_2401ai09_iitp_ac_in/EUbHrz0ZwIFAnhw8MV75Wm0BAAF4JdNnu3Zi2rk5SMxNHQ?e=FCiWRy) &nbsp;  &nbsp; [**Link2**](https://drive.google.com/file/d/1R40CC6V86XvLf6XgKB6x3FmfcUNRroSW/view?usp=sharing)  &nbsp; &nbsp; (Choose any one)

---

## 🗂 Submission

- Provide us your solution using this form - [**Link to Submission Form**](https://docs.google.com/forms/d/e/1FAIpQLSeHFyql46rP1GfWDuaYgJWfcAYkYPExFIEpkjB-uoy4UEXrkw/viewform?usp=dialog)

## 🧪 Evaluation Metric

Submissions are evaluated using:

 **Length of longest sub-sequence of ordered frames**<br><br>
 For example : <br>
If the correct sequence is [1, 2, 3, 4, 5]
- Suppose, if you have predicted [1, 3, 4, 5, 2], your Score : 4 as length of [1, 3, 4, 5] <br>
- Suppose, if you have predicted [3, 2, 4, 5, 1], your Score : 3 as length of [2, 4, 5] <br>

**Special points will be accordingly awarded if you do not use feature templates**<br>

---
