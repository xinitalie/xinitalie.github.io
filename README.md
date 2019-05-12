# XIN ITALIE
## Photography Website

The site is available at https://xinitalie.github.io

### Before changing ANYTHING
1. open Terminal app
2. type in: cd xinitalie.github.io
3. type in: before_edits.sh

### How To:
#### 1. Add and Delete Photos
1. open finder window and to to folder: /xinitalie.github.io/
2. add/ remove any photos from the folder: /assets/photos/
	* photos are sorted alphabetically (numbers before letters) then numerically
		- ex. 1apples, 2bananas, apples, banana, banana1, banana2, carrots
3. DO NOT DELETE/RENAME THE SOCIAL MEDIA LOGOS
##### * From Gallery
1. all photos in /assets/photos/gallery will appear on your homepage
	* adding or deleting from the folder will automatically update the page
##### * From Travel Destination
1. photos in /assets/photos/your_destination will appear on the destination's page
	* adding or deleting from the folder will automatically update the page
#### 2. Add a Travel Destination
1. add new file in the folder: \_destinations
2. file called destination_name.md
	* destination_name should match a folder in /assets/photos
	* destination_name should be all lowercase
	* copy a pre-made destination file and change date and place
		- place must be all lowercase
		- date on destination page goes: yymmdd
		- no spaces, dashes, stars. only numbers for date. must be in order yymmdd
#### 3. Edit About Page
1. go to /about.html
2. to edit picture, photo must be in folder: /assets/photos
	* photo must be called profile_pic.jpg
3. anything in between the \<p\>\</p\> will appear next to the picture on the left.

### After changing EVERYTHING
1. open Terminal app
2. type in: cd xinitalie.github.io
3. type in: after_edits.sh
4. when you see " Branch 'master' set up to track remote branch 'master' from 'origin'. ", you can quit Terminal.
