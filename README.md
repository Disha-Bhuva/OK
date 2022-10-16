## 🤠 Inspiration
Nothing gives you more thrill than a Gunfight. So we created a **real-time PvP** game. we are inspired by Pokemon go to make an amazing experience.

## 🏇 What it does

It uses AR to show some virtual covers like pliers to save yourself from the bullets, Aim at the enemy and fire, both players get 100 HP who loses all the HP first loses and victory goes to our pro cowboy.

## 💣 How we built it

AR is a tool that is actively changing the experience of all big and small games, We have used ``Firebase`` to store AR anchors in a real-time database We used YOLO: Real-Time Object Detection
 to detect the body moments, We also used Firebase ML kits to identify the head so we can give different damage to a different body part

## 💥 Challenges we ran into

Assigning different damage for different hitboxes was challenging like a headshot. There were concurrency issue like if we call the shoot function quickly one after another, we can end up with inconsistent state like different HP, to prevent this we added a cooldown time for the next fire button call and showed it as reloading 
time 😅.

## 🐎 Accomplishments that we're proud of

We are really happy that we used YOLO for real-time time, It was a bit difficult to make it work but in the end, it was satisfying, we achieved real-time updates of the state for both players and made a PvP game.

## 🔫What we learned

We learned about YOLO and firebase Object detection
We  learned to use two object detection mechanisms parallel on a device and we managed to identify and handle concurrency issue.

## 🐴What's next for west gunfight

We are planning to add some team-based games with this like instead of 1 vs 1 we can have a team vs a team with some different types of guns to select from.
