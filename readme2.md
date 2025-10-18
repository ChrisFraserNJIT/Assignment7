# Module 7

## My GitHub Repository

![GitHub Repo](qr_codes/QRCode_20251018151300.png "My QR Code Link")

## My DockerHub Image

![Docker QR Image](qr_codes/QRCode_20251018151209.png "My QR Code Link")

## Key Experiences and challenges faced

Working with Docker for this project was a mix of frustrating and eye-opening. At first, I wasn’t sure how to get my Python scripts to run consistently in a container, and I kept running into errors where commands didn’t execute the way I expected. Figuring out the difference between ENTRYPOINT and command took some trial and error, but once I got it, everything became much more predictable.

One of the biggest challenges was trying to run multiple commands in one container. I had to figure out how to chain them properly and make sure they ran in the right order, which took some experimenting. Mapping the local qr_codes folder to the container so the outputs would show up on my machine was another small hurdle, but it worked eventually.

Overall, Docker has made me see how much easier it is to share and run projects across different systems without worrying about environment issues. Even though it was tricky at first, I now understand why containerization is so useful. My workflow feels cleaner, more organized, and I understand better how to move a project from development to something that can run anywhere.