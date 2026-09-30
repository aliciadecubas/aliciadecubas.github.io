# Alicia de Cubas Portfolio

A lightweight static portfolio site. Edit the HTML directly; no build tools or JavaScript setup are required.

## Pages

- `index.html` — introduction and featured projects
- `about.html` — background, interests, and working style
- `cv.html` — experience, education, and skills; use **Print / Save as PDF** to export it
- `contact.html` — email and social links

## Personalize it

1. Search the HTML files for square-bracketed text such as `[Project name]` and replace it with your details.
2. In `index.html`, replace each `<div class="video-slot">...</div>` with a video element. For example:

	 ```html
	 <video class="project-video" controls playsinline preload="metadata">
		 <source src="videos/project-one.mp4" type="video/mp4">
	 </video>
	 ```

	 Put the matching video file in a `videos` folder beside `index.html`. Keep the `project-video` class so the clip stays responsive.
3. Replace `your@email.com` in `contact.html` with your public contact email.
4. Update the project cards, skills, CV entries, and social links so they reflect your own experience. Duplicate a `<article class="project">` in `index.html` to feature another project.

The layout and animations adapt to mobile screens and respect reduced-motion settings. The CV page has a print stylesheet for exporting a clean PDF.