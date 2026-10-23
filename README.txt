PCDAVID.com starter site

Files:
- index.html: storefront website
- inventory.json: PC listings (currently one dummy listing to replace/delete)
- pcs/: future PC photo folders

To add a PC, add another object to the JSON array in inventory.json. Keep commas between objects.
To mark a PC sold, change its sold value to true.
For photos, make a folder under pcs/ and add paths such as pcs/your-pc-name/front.jpg to that PC's photos array.

Important: index.html and inventory.json must be in the same repository root for this version.
