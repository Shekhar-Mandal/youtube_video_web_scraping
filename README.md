# youtube_video_web_scraping  
This project uses **Selenium** and **NumPy** to automatically extract key details — **video titles, views, and durations** — from the recommended video list on a YouTube video page.  

---

## 🚀 Features  
✅ Extracts the **title** of each recommended video  
✅ Retrieves **view count** and **duration** of each video  
✅ Handles missing data gracefully using **NumPy NaN values**  
✅ Prints and stores the extracted information in Python lists  

---

## 🧠 How It Works  
The script loops through the first 30 recommended videos (or fewer, if available) and uses **XPath** to locate and extract:  
- Video **title**  
- **Views** count  
- **Duration**  

If any data is missing (for example, an element can’t be found), it automatically appends `np.nan` instead of crashing.

---

Shekhar Mandal
