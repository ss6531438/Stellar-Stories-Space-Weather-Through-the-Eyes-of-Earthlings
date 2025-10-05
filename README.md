# Stellar-Stories-Space-Weather-Through-the-Eyes-of-Earthlings
Overview

This project is a single-page storytelling website designed to provide an interactive and cinematic experience for users exploring three chapters: Aurora, CME (Coronal Mass Ejection), and Tricky Tech. Each chapter features an image thumbnail that, when clicked, plays a local video in the same page. The homepage also includes a looping background video to enhance visual engagement.

Features

Three chapters with descriptive images: Aurora, CME, Tricky Tech.

Local video playback on chapter selection.

Cinematic background video with dark overlay for text readability.

Responsive design for desktop and mobile browsers.

Smooth hover effects and transitions for chapters.

Close video button to hide the video player.


storytelling-website/
│
├── index.html                # Main HTML file
├── images/                   # Chapter thumbnails
│   ├── aurora.jpg
│   ├── cme.jpg
│   └── trickytech.jpg
└── videos/                   # Local videos
    ├── aurora.mp4
    ├── cme.mp4
    ├── trickytech.mp4
    └── bg.mp4                # Background video for homepage


Installation Instructions

Clone or download this repository to your local machine.

Ensure the folder structure is maintained as above.

Place your videos in the videos/ folder and images in the images/ folder.

Open index.html in a modern browser (Chrome, Edge, Firefox, etc.).

Click on any chapter image to play the corresponding video.

Usage

Playing a chapter video: Click on a chapter thumbnail; the video will appear below the chapter container and autoplay.

Closing a video: Click the Close Video button to hide the video player.

The background video plays continuously and loops automatically, creating a cinematic atmosphere.

Technologies Used

HTML5 – Page structure and video embedding

CSS3 – Styling, hover effects, responsive layout, and overlay effects

JavaScript – Handling video playback, close button functionality, and smooth scrolling

Customization

To replace videos, update the video files in the videos/ folder and ensure the src in index.html matches the new filenames.

To change chapter images, replace the images in the images/ folder and update the <img> src attributes if necessary.

CSS can be adjusted to change colors, shadows, transitions, and layouts to match your visual preferences.

Browser Compatibility

Fully compatible with Chrome, Edge, and Firefox.

Works on modern mobile browsers; background video may not autoplay on some mobile devices due to browser restrictions (muted autoplay required).

Future Enhancements

Add animated transitions when switching between videos.

Implement lightbox-style popup for chapter videos for a more cinematic effect.

Include background music or ambient sounds for immersive storytelling.

Optionally, host videos on cloud storage (e.g., YouTube or Google Drive) for faster streaming.
