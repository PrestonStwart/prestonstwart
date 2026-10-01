PRESTON STEWART PORTFOLIO
How to finish and publish the site

1. ADD YOUR MEDIA (no code editing needed)
Drop files into these folders using these exact names. Each one replaces
its placeholder frame automatically.

  video/showreel.mp4        Showreel at the top of the page (16:9)
  video/showreel.jpg        Optional still shown before the reel plays
  video/project-01.mp4      Video projects 1 to 4 (16:9)
  video/project-02.mp4
  video/project-03.mp4
  video/project-04.mp4
  video/project-01.jpg      Optional cover stills for each project
  (and so on for 02 to 04)

  images/portrait.jpg       Your portrait in the About section (4:5)
  images/photo-01.jpg       3:2 landscape
  images/photo-02.jpg       4:5 portrait
  images/photo-03.jpg       3:2 landscape
  images/photo-04.jpg       1:1 square
  images/photo-05.jpg       3:2 landscape
  images/photo-06.jpg       4:5 portrait
  images/photo-07.jpg       4:5 portrait
  images/photo-08.jpg       3:2 landscape
  images/photo-09.jpg       3:2 landscape

Tips: export photos at about 2400px on the long edge (JPG, quality 80) so
the page loads fast. Export videos as H.264 MP4. Files over 100 MB will not
upload to GitHub, so keep each video under that or host long ones on
YouTube or Vimeo and link to them.

If a photo has a different shape than its frame, change the class on its
frame in index.html: r32 = 3:2, r45 = 4:5, r11 = 1:1, r169 = 16:9.

2. REPLACE THE BRACKETED TEXT
Open index.html in any text editor (VS Code is free) and search for "[".
Every bracketed item is a placeholder: project titles, roles, years,
runtimes, camera settings, graduation date, services, work history, and
social handles. When you fill one in, also delete class="fill" from that
tag so it shows in normal text color instead of gray.

3. PUBLISH IT FREE
Option A, Netlify Drop: go to app.netlify.com/drop and drag this whole
folder onto the page. You get a live link in about a minute.
Option B, GitHub Pages: create a repository, upload the contents of this
folder, then turn on Pages under Settings > Pages (branch: main, folder: /root).
