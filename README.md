## Background

I faced problems when researching companies on the Glassdoor with the box message "Add your review or salary to continue using Glassdoor". The box was impossible to close and even if I could hide it using the AdBlock extension, the website itself was unscrollable.
Using the browser's inspector I can write a simple script that can hide the box and allow scrolling, but I wanted to automate the process.

## Solution

1. Install the [Custom Style Script extension](https://chrome.google.com/webstore/detail/custom-style-script/ecjfaoeopefafjpdgnfcjnhinpbldjij)
2. Configure a new script in the extension
  1. Set URL: `https://www.glassdoor.com`
  2. Set Script Link: https://github.com/dmmax/hide-glassdoor-overlap-blocks/blob/main/hide-blocks-on-load.js. Or you can add the code manually 
  3. Click on the "Plus" button
3. Go to the glassdoor, you should not see the overlapping box anymore

## Video how to configure the extension 

https://github.com/dmmax/hide-glassdoor-overlap-blocks/assets/6257813/c2f9bc83-e97e-47c1-bf45-eff57d93c6da

## Note

If at one point they will change 