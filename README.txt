
MOCKUP-LEARING
==============

A collection of single-file HTML mockups for learning technical topics visually.
Every file is self-contained: just double-click the .html file to open it in any
browser. No install, no server and no internet connection needed.


FOLDERS
-------

docker learing mockups/
    docker-explained.html
    Beginner guide to Docker. Covers images vs containers, VM vs container,
    the Docker workflow, a simulated terminal (pull / run / ps / stop / rm),
    Dockerfile line by line, ports and volumes, Docker Compose, a command
    cheat sheet, a quiz and a learning roadmap.

nextjs learing mockups/
    nextjs-explained.html
    Beginner guide to Next.js (App Router). Covers what Next.js is, setup,
    a clickable folder-structure explorer, routing (URL to file), special
    files, Server vs Client Components, rendering modes (SSG, ISR, SSR, CSR),
    data fetching and API routes, commands and deploy options, a quiz and a
    learning roadmap.

http learing mockups/
    http-explained.html
    Beginner guide to HTTP, HTTPS and status codes. Covers client/server
    request and response, URL anatomy, HTTP methods, HTTP vs HTTPS and the
    TLS handshake, a status code explorer (1xx to 5xx), a request simulator,
    headers and cookies, a cheat sheet, a quiz and a learning roadmap.

networking learing mockups/
    networking-explained.html
    Beginner guide to Computer Networking and WiFi. Covers what the field is
    called (LAN, WLAN, WAN), a clickable home network map (modem, router,
    switch, access point), hardware vs software, how WiFi works with a signal
    demo, IP/MAC/DHCP, a DNS lookup animation, OSI layers, TCP vs UDP and
    ports, a simulated terminal (ipconfig / ping / nslookup / tracert), a WiFi
    troubleshooting checklist, a cheat sheet, a quiz and a learning roadmap.

playwright learing mockups/
    playwright-python-explained.html
    Beginner guide to Playwright with Python. Covers what Playwright is,
    setup, a first script (browser / context / page), locators, actions and
    reading data, a live script-vs-fake-browser simulator, auto-waiting,
    pytest tests with expect(), codegen / inspector / trace viewer, sync vs
    async API, a searchable cheat sheet, a quiz and a learning roadmap.

full-stack learing mockups/
    full-stack-explained.html
    Beginner guide to how a full-stack web app fits together. Covers what
    "full stack" means, a clickable layered map (client, frontend, API,
    backend, database, infra), an animated request-lifecycle flow, generic
    frontend and backend responsibilities, API communication basics, SQL vs
    NoSQL data storage, auth and security fundamentals, deployment and CI/CD
    concepts, the testing pyramid, monolith vs microservices vs serverless
    patterns, a glossary cheat sheet, a quiz and a learning roadmap. Stays
    tool-agnostic and links out to the http, networking, docker and
    playwright mockups in this collection for deeper dives.

object-storage learing mockups/
    object-storage-explained.html
    Beginner guide to object storage using Amazon S3 and Cloudflare R2. Covers
    buckets, objects and keys, a clickable client-to-bucket-to-CDN flow for
    serving real website assets (images, video, uploads, backups), public vs
    private access and presigned URLs, a simulated bucket explorer (create
    bucket, upload/list/delete objects, toggle public/private, generate a
    presigned URL), a factual S3 vs R2 comparison (API compatibility, pricing
    model and egress fees, typical use cases), common access-control and cost
    pitfalls, a cheat sheet, a quiz and a learning roadmap. Links out to the
    http and full-stack mockups in this collection for CDN/caching and
    architecture deep dives.

bmad/
    bmad-guide-mockup.html
    Visual guide mockup for BMAD (agent and skill workflow).

meta_pixel_tag/
    meta-pixel-flow.html
    Visual flow mockup explaining how the Meta Pixel tag works.


HOW TO USE
----------

1. Open a folder.
2. Double-click the .html file (it opens in your default browser).
3. Scroll through the sections, click the interactive demos, and take the quiz.

Progress checkboxes in the roadmap sections are saved in your browser
(localStorage), so they stay ticked when you come back.


TECH
----

Plain HTML, CSS and vanilla JavaScript in a single file per topic.
No frameworks, no build step, no dependencies.


ADDING A NEW MOCKUP
-------------------

1. Create a new folder named after the topic, e.g. "python learing mockups".
2. Put a single self-contained .html file inside it.
3. Add a short entry for it in the FOLDERS section of this README.


AUTHOR
------

kodetomates-dev (KodeToMates)
