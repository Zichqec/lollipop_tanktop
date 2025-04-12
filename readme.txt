Freeshell "Lollipop Tanktop" v1.0.1

—————————— Terms ——————————
This freeshell is free to use for your own ghost projects, with the following terms.

You must:
	• Mention in your ghost's readme that you are using my freeshell. I can be credited as "Zichqec", with the following link: https://ukagaka.zichqec.com/
	• Keep this readme file as-is. (Exception: the file can be renamed if needed, such as if combining this shell with another freeshell.)
	
You may:
	• Modify the shell, including recoloring, drawing new expressions, combining expressions, scaling the images, mirroring the images, etc. (If the shell is drawn in a pixel style, please take care when scaling. They'll look best if you keep the pixels sharp!)
	• Modify the settings files in any way you need.
	• Combine this shell with other freeshells.
	• Use this shell to create a thumbnail image for your ghost, or a preview image for use on the ghost's release page, etc.
	
You must not:
	• Use this freeshell to create commercial works.
	• Distribute any version of this freeshell on its own.
	• Use this shell for works outside the realm of ukagaka.
	• Modify the shell to be discriminatory or political, or use it in a work that contains these elements.
	• Modify the shell to add nudity or sexual elements.
	• Use AI tools to modify the artwork in this shell.

It is not required to notify me that you have used this shell, but I'd love to see what you've made!


—————————— Customization ——————————
layers.psd has been included to help with customization. This file includes 9 different color options and 9 different tattoo options. Just pick the options you want, and export the pieces overtop of the defaults! All the layer folders should be labeled the same as the folder structure the shell uses.

Feel free to create your own custom color scheme or draw your own tattoos, as well!

And of course, you can keep the default settings if you prefer them.


—————————— Surface numbering scheme ——————————
This shell follows the recommended surfaces listed on Ukadoc. 0-9 should roughly match up with the standard 0-9 that you'll find there. https://ukagakadreamteam.github.io/ukadoc/manual/descript_shell_surfaces.html#caption_standarddef

In addition, there are alternate eyes and arms that can be controlled by adding additional digits. The ones column is the expression, the tens column is the eyes, and the hundreds column is the arm. For example, surface142 is the surprised expression (2), with eyes looking down (4), and the arm in the "close" position (1).

000 - "Bite" arm (lollipop in mouth - note that the mouths are slightly different for these surfaces)
100 - "Close" arm (lollipop overlaps face - this is what blush_alt.png is for)
200 - "Up" arm
300 - "Splayed" arm (same position as "up" arm, but with fingers outstretched)
400 - "Down" arm

	00 - Eyes looking right
	20 - Eyes looking left
	30 - Eyes looking forward/at the user
	40 - Eyes looking down
	50 - Eyes looking up/rolling
	60 - Eyes closed
	70 - Eyes squeezed shut
	
		0-9 - The recommended expressions listed on Ukadoc

Note that there are a few expressions that are duplicates of each other because they can be made in multiple ways. I've decided to leave them in since they may be useful in some edge cases (automation, etc.).

There are also a group of "special expressions". In this shell, surfaces 80-85 are a "skeptical" expression, with the eyes pointing in various directions. Surfaces 90-95 are the same expressions as 80-85, but with a smile instead of a frown.
(I ran out of space in my numbering scheme, hence these ones using a different system... The eyes go in the same order they do with the normal surfaces, just controlled with the ones column instead of the tens column.)

Surfaces 86-89 are completely unique expressions that do not fit any numbering scheme.
Surfaces 96-99 are empty, if you want to make a few custom expression combinations you may be able to slot them here! If that's not enough space, you'll have to overwrite other expressions or pick a different range of numbers.


All surfaces have the following "never" animations that can be called with \i[] tags:

\i[10] - Stop the talking animation (for narration, etc.)
\i[11] - Blush
\i[12] - Sweat drops

Note that the blush and sweat drops are automatically applied to some expressions, making it redundant to use these tags with those surfaces.


—————————— Collisions ——————————
The following collisions are included by default:

Head - top of the head, specifically following the hairline
Face - The area of the face other than the hair
Tattoo - A section of the right side arm (it should be large enough to suit any of the tattoo options, but you may want to adjust it if you pick a smaller tattoo)
Lollipop - The lollipop on any surfaces other than the "bite" arms