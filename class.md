# Miss Kiki's Class
* name: Miss Kiki's Class
* description: Create a fast-paced maze game by programming a student to move through the crowded halls to collect assignments without being interrupted by a teacher!
* infoUrl: skillmap/educator-info/class-map-info
* backgroundurl: /static/skillmap/backgrounds/class-comp.png
* bannerurl: /static/skillmap/class/class.gif
* primarycolor: #fa924a
* secondarycolor: #833d17
* tertiarycolor: #1d005d
* strokecolor: #1d005d
* highlightcolor: #f8ffcf
* completednodecolor: #543b28

## class
* name: Miss Kiki's Class
* layout: manual

### class1
* name: Trapped in the Halls
* type: tutorial
* description: Add a student to the halls of the school, then keep an eye on them as they move around!
* url: /test/skillmap/class/class1
* tags: easy, sprites, movement
* imageUrl: /static/skillmap/class/class1.gif
* next: class2
* position: 0 -1

### class2
* name: Escape Miss Kiki
* type: tutorial
* description: Try not to run into the teacher or she'll steal your time!
* url: /test/skillmap/class/class2
* tags: easy, enemies, overlaps, timer
* imageUrl: /static/skillmap/class/class2.gif
* next: class3
* position: 1 -2

### class3
* name: Finish Your Homework
* type: tutorial
* description: Add a feature that lets you win the game when you collect all your assignments. 
* url: /test/skillmap/class/class3
* tags: easy, overlap, score, timer
* imageUrl: /static/skillmap/class/class3.gif
* next: class4
* position: 3 -2


### class4
* name: Get Animated!
* type: tutorial
* description: Animate your student so they appear to move when they walk.
* url: /test/skillmap/class/class4
* tags: easy, animation
* imageUrl: /static/skillmap/class/class4.gif
* next: class-finish
* position: 4 -2

### class-finish
* kind: completion
* type: certificate
* url: /static/skillmap/certificates/class-cert.pdf
* imageUrl: /static/skillmap/certificates/class-cert.png
* position: 4 -1
* actions:
    * map: [Try Space Explorer](/skillmap/space)
    * editor: [Mod this project](/)
* rewards:
    * certificate: /static/skillmap/certificates/class-cert.pdf
    * completion-badge: /static/badges/class-rockstar.png

