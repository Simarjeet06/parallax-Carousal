# 🎅 Christmas in New York — Parallax Carousel (SwiftUI)

A simple yet immersive **Parallax Carousel** built with **SwiftUI**, inspired by my Pinterest feed that was full of cozy *Christmas in New York* photos.  
I wanted to capture that “postcard scrolling” feeling — soft motion, depth, and a little bit of magic ✨  

---

## 🗽 Inspiration

It all started when my Pinterest feed was overflowing with pictures of **New York during Christmas** — glowing streets, ice rinks, and window lights.  
I wondered: *What if I could recreate that same atmosphere inside an iOS app?*  
That led me to experiment with **parallax motion**, **3D rotation**, and **scroll-based depth effects** in SwiftUI.

---

## 🌟 Features

- 🎠 **3D Parallax Carousel** — uses `GeometryReader` and `rotation3DEffect` to simulate depth.  
- 🧊 **Smooth scroll transitions** — powered by `scrollTransition(.interactive)` for natural zoom focus.  
- ❄️ **Gentle snowfall animation** — built using `TimelineView` and custom particle logic.  
- 🖼️ **Postcard-style cards** — subtle shadows, gradient borders, and material overlays.  
- 💨 **Optimized performance** — uses `.compositingGroup()` and `.drawingGroup()` for GPU rendering.

---

## 🧠 What I Learnt

- How **`GeometryReader`** helps track each card’s position in a scroll view.  
- How **`rotation3DEffect`** and **offset** can fake “depth” with just a few lines of code.  
- The difference between **`compositingGroup`** and **`drawingGroup`**, and why GPU rendering feels smoother.  
- How small details (like snow speed, shadow radius, and material intensity) dramatically affect perceived motion.  
- That inspiration can come from anywhere — even a Pinterest feed.  

---

## 🧩 Tech Stack

- **Language:** Swift  
- **Framework:** SwiftUI  
- **Animation:** GeometryReader + ScrollTransition + TimelineView  
- **Rendering:** Metal GPU (via `.drawingGroup()`)



---

## 🚀 Getting Started

1. Clone this repository  
   ```bash
   git clone https://github.com/<your-username>/Christmas-ParallaxCarousel.git



