# iSight   
## Overview
**iSight** is an iOS application designed to help users understand how people with visual impairments perceive the world.  
It uses on-device Apple technologies to simulate common vision conditions in real time, promoting empathy, awareness, and inclusive design.

The app is fully offline, privacy-first, and built to feel like a native iOS accessibility tool rather than a filter application.

---

## Key Features
- **Real-Time Vision Simulation**
  - Myopia (nearsightedness) simulation using distance-based blur
  - Adjustable severity for experiential learning
  - Optional eye floater simulation for realism

- **Empathy & Awareness**
  - Educational explanations of vision conditions
  - Guidance on respectful interaction with visually impaired individuals
  - Focus on inclusive behavior and accessibility awareness

- **Modern iOS Architecture**
  - SwiftUI-based UI
  - Modular, reusable components

- **Privacy-First**
  - Fully on-device processing
  - No backend or cloud dependency
  - No user data collection

---

## Technologies Used
- **Language:** Swift  
- **Frameworks:** SwiftUI, ARKit (Scene Depth), Core Image, AVFoundation  
- **APIs & Tools:** Combine, Core Graphics, SF Symbols  
- **Development:** Xcode, Git, GitHub  
- **Design:** Apple Human Interface Guidelines (HIG), Accessibility best practices  

---

## How It Works
- The app uses the iPhone camera and ARKit’s scene depth data to estimate object distance.
- Core Image filters apply distance-based blur so nearby objects remain clear while distant objects become progressively blurry.
- Additional perceptual effects (contrast reduction, optional floaters) enhance realism while remaining educational.

> Note: Depth-based effects are most accurate on LiDAR-equipped iPhones.  
> On non-LiDAR devices, the app gracefully falls back to a simplified simulation.

---

## Running the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/am4352/iSight/tree/anuj
