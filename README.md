Colmar Academy - Codecademy Ready Capstone Project (Week 7)

General Decisions:
- most images are decoration so they get alt=""
- links have clear hover/active/focus settings
- use font awesome icons as a replacement for the images in the courses section for the mobile version
- set more media query breakpoints to smooth out the transition from desktop to mobile

Layout:
I identified the following patterns (for the desktop) that I style globally the same using classes:
- splitting content into two colums roughly 2:1 -> classes .wide and .narrow
- articles with images associated are of two types .split (using the columns approach) and .compound (with the image at 100% width on top) they have the two components .img-box and .txt-box

Color & Font choices:
I want to transport/express:
- campus athmosphere (nature and inspiring surroundings) -> green/beige/brown (+ link buttons shape resembles leaves)
- joy of learning and creating -> Playful (but readable) font
- respectability/reliability -> not too colorful

Colors:
light green #B7c68B
dark green #424a25
light beige #F4F0CB
dark beige #DED29E
dark brown #26210D

Left Open:
- I would ask the designer if she just overlooked the "for companies" entry in the mobile version. (I think it should be accessible on mobile too)
- 'Start here' is a bad name for a link concerning accessibility (also 'Read more')
- both versions of the images in the information section load every time
- compress resources
- poster image for video
