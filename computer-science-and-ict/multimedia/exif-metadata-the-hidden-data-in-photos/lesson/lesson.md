# EXIF Metadata — the Hidden Data in Photos

## Do it first

Take one photo — on a phone if you have one, or imagine the last photo you took. The picture shows a scene. But the file knows much more than the scene: it was written by a particular device, at a particular moment, with particular settings — and if the phone knew where it was, the file knows that too, in numbers. Write down everything you think the file might secretly carry. Keep your list — the lesson names the hidden block, shows what is really inside it, and how a stranger reads it from a photo you send.

## Sub lesson 1 — What EXIF records

A digital photo is two things in one file: the picture, and a written record about the picture. The record is called **EXIF** data (Exchangeable Image File Format), and the camera or phone writes it automatically, at the moment of the shot, without asking. It names the **device** — make and model of the camera or phone. It stamps the **date and time**. It keeps the **settings**: exposure time, aperture, flash fired or not, sensitivity. It records the image's dimensions and orientation. And when the device's location service is on, it stores the **GPS coordinates** — latitude and longitude — of the exact spot where the photo was taken.

None of this shows in the picture. A photo of a birthday cake looks innocent; its EXIF may say which phone took it, on what day at what minute, and at which house. France's SNT book makes you open this block yourself — in the photography theme you extract a photo's EXIF, and in the localisation theme you hunt a mystery photo's location from the coordinates hiding inside it.

In your mind's eye: one photo shown twice: the picture on the left, and on the right its EXIF record as a list — device, date, settings, GPS numbers.

[Picture 46305 — one photo shown twice: the picture on the left, and on the right its EXIF record as a list — device, date, settings, GPS numbers]

## Sub lesson 2 — Reading EXIF and finding where a photo was taken

Reading EXIF needs no special power: a photo's **properties** on any computer show part of it, and small tools — the book uses a few lines of Python — print the whole block, including the GPS numbers stored as degrees, minutes and seconds to convert into decimal coordinates. Those two numbers go straight onto a map: latitude for the north–south position, longitude for east–west. The mystery photo is solved.

So the practical rule cuts both ways. EXIF is useful: it sorts your photos by date, maps your travels, proves when a shot was taken. And it is a leak: post an original photo of your home and you may publish your address with it. Many social platforms strip EXIF on upload; sending the original file — by email or messaging — usually keeps it. The book's habit is the right one: know the block exists, read it before you share, and strip the location (most phones offer "remove location" when sharing) when the place is private.

In your mind's eye: a pair of GPS numbers from an EXIF block being placed as a pin on a map.

[Picture 46306 — a pair of GPS numbers from an EXIF block being placed as a pin on a map]

## Say it to your companion

Tell your companion, in your own words: a photo file carries EXIF data — device, date, settings and often GPS coordinates — written automatically at the shot; anyone can read it, put the coordinates on a map, and learn where the photo was taken; so check it before sharing originals. Read the EXIF list of one imaginary photo aloud as you say it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book’s exact words.

## Do It Yourself

1. Show it, don't just say it: list the main kinds of data an EXIF block holds and say when they are written. Do this with a real example of your own — with a real photo’s properties if a device is available, or with the printed EXIF record in the lesson — and write or say how you know it is right.
2. Show it, don't just say it: explain why EXIF coordinates can reveal where a photo was taken. Do this with a real example of your own — with a real photo’s properties if a device is available, or with the printed EXIF record in the lesson — and write or say how you know it is right.
3. Show it, don't just say it: read a photo’s GPS numbers from its EXIF and place them on a map. Do this with a real example of your own — with a real photo’s properties if a device is available, or with the printed EXIF record in the lesson — and write or say how you know it is right.
4. Show it, don't just say it: say how to share a photo without giving away its location. Do this with a real example of your own — with a real photo’s properties if a device is available, or with the printed EXIF record in the lesson — and write or say how you know it is right.
