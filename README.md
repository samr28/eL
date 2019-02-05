# eL

## Inspiration
As students, we both ride electric longboards to all of our classes because of how convenient and fun they are. One of the problems with these boards is that there aren't many lighting solutions available which leaves riders at risk of being hit at night. If a car can't see the rider, how can they avoid hitting them? To solve this issue, we created our own smart lighting system for electric longboards called "eL".

## What it does
eL includes a strip of LEDs and a small control box. The control box mounts to the handle that most electronic skateboards already have. The device is battery powered and can be controlled by the companion phone app.

It uses an accelerometer to tell when the rider is slowing down or leaning to turn. It then uses this data to display either a brake light or a turn signal. The companion app also allows users to select fun effects to customize their board.

## How we built it
We started by putting all of our components onto a breadboard and connecting them with jumpers. Once we had that built out, we started working on the Arduino code. We then decided to break down the software side of the system into two main parts:

- Microcontroller - hosts REST endpoints
- Android app - gets/sends data to the microcontroller via the REST endpoints

We then split up and Maxwell worked on the software side while Sam started soldering components together. A few hours later, eL was up and running!

## Challenges we ran into
- Battery issue: we needed 5v to power the LEDs and microcontroller but the lithium polymer batteries were 3.7v. Unfortunately, we were unable to source hardware to step this up to 5v so we ended up using 3 AA batteries in series (4.5v)

## Accomplishments that we're proud of
We were able to build a very complete and polished project. We believe that this project could make traveling on electric skateboards much safer. We also believe that this will promote the use of electric skateboards which are clean and practical mode of transportation. We will be looking into developing that project further and potentially turning it into a product.

## What we learned
- Some new soldering techniques
- Android studio/app development
- RESTful APIs

## What's next for eL
- Add GPS to allow users to track rides
- Additional lighting effects
- Case solution for boards without handles
- Share ride data with friends
- Power with rechargeable battery
- Brake for non-electric longboards
- Fine tune algorithm for more accurate brake/turn detection
pursue possibility of creating this into a product for a startup
