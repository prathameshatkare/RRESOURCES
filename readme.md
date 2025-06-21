<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

</head>
<body>
    <h1>Resources </h1>
    <table>
        <thead>
            <tr>
                <th>Resource Type</th>
                <th>Title</th>
                <th>Link</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>YouTube Playlists</td>
                <td>YouTube Python Playlist</td>
                <td><a href="https://www.youtube.com/playlist?list=PLsyeobzWxl7poL9JTVyndKe62ieoN-MZ3">Watch here</a></td>
            </tr>
            <tr>
                <td>Book</td>
                <td>Think Python (PDF)</td>
                <td><a href="https://greenteapress.com/wp/think-python-2e/">Download PDF</a></td>
            </tr>
            <tr>
                <td>Book</td>
                <td>Automate the Boring Stuff with Python</td>
                <td><a href="https://automatetheboringstuff.com/">Read here</a></td>
            </tr>
            <tr>
                <td>Blog</td>
                <td>Best Free Resources to Learn Python</td>
                <td><a href="https://medium.com/@Coursesteach/best-free-resources-to-learn-python-ba9def93c9ed">Read here</a></td>
            </tr>
            <tr>
                <td>GitHub</td>
                <td>GitHub Courses</td>
                <td><a href="https://github.com/SkalskiP/courses?tab=readme-ov-file">Explore here</a></td>
            </tr>
            <tr>
                <td>Syllabus</td>
                <td>Harkirat Cohort Syllabus</td>
                <td><a href="https://quickest-juniper-f9c.notion.site/Cohort-2-0-FullStack-Open-Source-6b6c2a9f1282499aba4782b88bf7e204">View here</a></td>
            </tr>
            <tr>
                <td>Projects</td>
                <td>Build Your Own X</td>
                <td><a href="https://github.com/codecrafters-io/build-your-own-x">View projects</a></td>
            </tr>
            <tr>
                <td>GitHub</td>
                <td>Awesome Remote Jobs</td>
                <td><a href="https://github.com/lukasz-madon/awesome-remote-job">Explore here</a></td>
            </tr>
            <tr>
                <td>GitHub</td>
                <td>Awesome Backend Resources</td>
                <td><a href="https://github.com/zhashkevych/awesome-backend">Explore here</a></td>
            </tr>
            <tr>
                <td>Documentation</td>
                <td>Django Documentation</td>
                <td><a href="https://django-book-new.readthedocs.io/en/latest/chapter02.html">Read here</a></td>
            </tr>
            <tr>
                <td>Projects</td>
                <td>Python Beginner Projects</td>
                <td><a href="https://github.com/Mrinank-Bhowmick/python-beginner-projects">View projects</a></td>
            </tr>
            <tr>
                <td>Assignments</td>
                <td>Assignments Repository</td>
                <td><a href="https://github.com/chandankushwahaa/100xdevs_2.0/tree/main/0-1/week01/assignments">View assignments</a></td>
            </tr>
             <tr>
                <td>MY REPO</td>
                <td>MY LEARNINNG</td>
                <td><a href="https://github.com/prathameshatkare/chai-aur-python">Read here</a></td>
            </tr>
             <tr>
                <td>Github</td>
                <td>MY company wise trending projects</td>
                <td><a href="https://github.com/nishant-Tiwari24/company-wise-projects">Read here</a></td>
            </tr>
            <tr>
                <td>Github</td>
                <td>JOB link</td>
                <td><a href="https://www.linkedin.com/posts/himabindu-krovvidi_career-jobsearch-tech-activity-7259006441515094016-iZib?utm_source=share&utm_medium=member_desktop">Read here</a></td>
            </tr>
             <tr>
                <td>notion</td>
                <td>complete roadmap</td>
                <td><a href="https://sajalb.notion.site/Complete-Full-Stack-Development-Roadmap-0-1-to-1-100-3548cab15c0a404c8c177fd2c3312374">Read here</a></td>
            </tr>
        </tbody>
    </table>
</body>
</html>
Wah bhai — sahi sawal!
Ye jo **"pattern pakadna seekho"** bolte hain na — asal me log uska matlab batate nahi.
Chal — main tujhe bilkul apne doston ko samjhata hoon waise bataata hoon ki **DSA me pattern kaise pakda jata hai**.
Aaj se ye cheez dimag me set kar le.

---

## 📌 Pehle ye samajh:

DSA problems ki **limited categories hoti hain** —
Har problem **us category me aati hai**, bas uska chehra alag hota hai.

Jese:

* **Search problems** → Binary search lagta hai kya?
* **Sorting problems**
* **Subarray problems** → Kadane’s, sliding window
* **Greedy problems**
* **DP problems** → overlapping subproblems dikh raha hai kya?
* **Graph problems** → connected components, shortest path
* **Binary search on answer problems** → *Aggressive Cows*, *Painters Partition*
* etc.

## 📌 Pattern pakadne ka tareeka:

### 1️⃣ **Problem me chhupa hua keyword dhoondo**

Jese:

| Agar problem me likha ho                | Soch lo                 |
| :-------------------------------------- | :---------------------- |
| **maximum sum subarray**                | Kadane's                |
| **maximum distance minimize**           | Binary search on answer |
| **sorted array + searching**            | Binary search           |
| **minimum coins / min steps**           | Greedy / DP             |
| **number of ways / count combinations** | DP                      |
| **shortest path / graph traversal**     | BFS / DFS               |
| **k elements / kth largest / nearest**  | Heap / Priority Queue   |
| **overlapping subproblem**              | DP                      |
| **sorted subsequence**                  | Two pointer / DP        |

---

### 2️⃣ **Brute force socho pehle**

Agar **O(N²)** ka brute force lag raha hai —
tab socho:

* Can we pre-calculate something?
* Kya previous result use ho sakta hai (DP)?
* Kya sorting ya binary search laga sakte hain?

Har problem ko brute force se karne ka socho —
fir optimize karne ka tareeka hi pattern hai.

---

### 3️⃣ **Similar problem yaad kar**

Agar pehle kabhi kiya hai:

* Kadane’s
* Two pointer
* Sliding window
* Binary search on answer
* DFS / BFS

To dekh ki ye problem uske jaise lag rahi hai kya.

**Jaise Aggressive Cows**

> Maximum minimum distance nikalna
> Binary search on answer me aata hai
> (kyuki range hoti hai answer ki)

---

### 4️⃣ **Constraints dekh**

Agar N ≤ 10^5
→ O(N log N) tak chalega
Agar N ≤ 10^9
→ O(log N) wala binary search hi chalega

Constraints bhi pattern hint dete hain.

---

## 📌 Ye karne ki aadat bana:

1. Problem padho
2. Brute force socho
3. Category identify karne ki koshish kar
4. Pehle ki koi similar problem yaad laao
5. Dry run 2-3 example pe karke dekh
6. Fir code likho

---

## 📌 5 Din ka kaam bata raha hoon:

**5 din ke liye ek kaam kar**

* Leetcode pe “easy” tag ki 50 problems uthaa
* Har problem solve karne ke baad likh:

  * Ye problem kis category me aayi?
  * Kya pattern tha?
  * Next time aayi to kya approach sochunga?

**50 problem ke baad tera dimaag automatic pattern pakadne lagega**
Promise.

---

## 📌 Final baat:

DSA me **patterns seekhne ka ek hi shortcut hai**:

> **Har problem solve karne ke baad apne se puchhna — is problem me kya pattern tha?**

Agar tu chahe to main 8-10 famous patterns ka ready list bana ke de sakta hoon jo har contest me repeat hote hain.

**Bol de — bana doon?** ⚡🔥

