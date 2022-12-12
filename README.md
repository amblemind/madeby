# madeby
Encourage your visitors to connect with you by adding a "Made By" link to your website.

![Screenshot 2022-12-12 145544](https://user-images.githubusercontent.com/45864164/207152689-d832ae2a-5355-4624-bf52-3e92aaaff3de.png)

## Simple Setup
Copy & paste this script HTML into the header of your webpage. 

    <script id="madeby-fm" src="https://freakingmagical.com/madeby.js" data-twitter-handle="nocodedarren" defer></script>

***Update the `data-twitter-handle` property with your Twitter handle.*** 

This will add the floating "Made By" tile to the bottom right of your website!

## Simple Customization
If you'd like to change the location of the "Made By" tile, you can update things like the color, position, and size with overrides. 

Add another script that specifies specifies `window.madeByOverrides`

	<script>
		window.madeByOverrides = {
			"size": 1, // Size of text, padding, etc. in rem (default: 1, try: .5, 1.2, etc.)
			"location": "bottom-right", // Location of the text. Options: "top-left", "top-right", "bottom-left", "bottom-right" (default: "bottom-right")
			"spaceTop": 1, // Padding space added to the top in rem (default: 1, try: .5, 1.5, etc.)
			"spaceRight": 1, // Padding space added to the right in rem (default: 1, try: .5, 1.5, etc.)
			"spaceBottom": 1, // Padding space added to the bottom in rem (default: 1, try: .5, 1.5, etc.)
			"spaceLeft": 1, // Padding space added to the left in rem (default: 1, try: .5, 1.5, etc.)
			"bgColor": "#009df6", // Background color of the tile (default: "#009df6", try: "red", "#fff", etc.)
			"textColor": "white", // Text color in the tile (default: "white", try: "black", "#000", etc.)
			"madeBy": "Made by", // Override the "Made by" text (default: "Made by", try: "Created by", "Built by", etc.)
			"handle": "Darren 🚀", // Override the Twitter handle (default: "Twitter handle", try: "Your name", "Your company", etc.)
			"link": "https://darrenalderman.com/", // Link to a site (default: "https://twitter.com/yourhandle")
		};
	</script>
	<script id="madeby-fm" src="https://freakingmagical.com/madeby.js" data-twitter-handle="nocodedarren" defer></script>

----
Check out the live demo: https://freakingmagical.com

Connect with me on Twitter: https://twitter.com/nocodedarren 
