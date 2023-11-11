## Background

I faced problems when researching companies on the Glassdoor with the box message "Add your review or salary to continue using Glassdoor". The box was impossible to close and even if I could hide it using the AdBlock extension, the website itself was unscrollable.
Using the browser's inspector I can write a simple script that can hide the box and allow scrolling, but I wanted to automate the process.

## Solution

1. Install the Google Chrome extension [User JavaScript and CSS](https://chrome.google.com/webstore/detail/user-javascript-and-css/nbhcbdghjpllgmfilhnhkllmkecfmpld)
2. Add a new site (rule) in the extension
  - Set URL: `https://www.glassdoor.*/`
  - Copy the script from the [JS file](https://raw.githubusercontent.com/dmmax/hide-glassdoor-overlap-blocks/main/hide-blocks-on-load.js)
  - Paste the copied script to the left text box "JS"
  - Click on the button "Save" or use the combination `Ctrl/Cmd + S`
3. Go to the glassdoor, you should not see the overlapping box anymore

## Video how to configure the extension 

https://github.com/dmmax/hide-glassdoor-overlap-blocks/assets/6257813/6556e126-8c4b-4f17-b2c1-1ba836dd051a

## Note/Contribution

If at one point, the code does not work anymore - most likely the Glassdoor developers changed the DOM structure. Feel free to contribute a solution or create an issue and I will fix it.
