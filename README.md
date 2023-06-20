# nasa-photo-wall

A photo wall of NASA's beautiful Astronomy Picture of the Day from the last 12 days.

<a href="https://nasa-photo-wall.netlify.app/" rel="nofollow">
    <img alt="Website" src="https://img.shields.io/static/v1?label=|&message=WEBSITE&color=cdf998&style=for-the-badge&logo=googlechrome&logo-color=white">
</a>

<img alt="Website Status" src="https://img.shields.io/website?style=flat-square&url=https%3A%2F%2Fnasa-photo-wall.netlify.app%2F"> <img alt="GitHub" src="https://img.shields.io/github/license/infinitesolargalaxy/nasa-photo-wall?style=flat-square">

| Desktop | Mobile |
|---|---|
| <img src="Desktop.PNG"> | <img src="Mobile.PNG"> |

## How It's Made:

**Tech used:** <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a>

Create a photo wall from NASA API: https://api.nasa.gov/planetary/apod

### Copyright
Because each photo is the intellectual property of the original photographer, I needed to ensure that due credit is given. Based on the documentations, I attribute the copyright to `copyright` property if present, and otherwise attribute to NASA.

## Optimizations
I used the `start_date` query parameter to obtain a range of photos in a single API call.

Additionally, the images displayed in the photowall are lower definition than the HD photos used in the poptrox in order to reduce the webpage's load time.

Some of the photos of the days are videos. But for optimization purposes, I made use of the video's still image. If I have time in the future, I will change the poptrox to have an iframe with the original video.

## Lessons Learned:
I made use of text-overflow and elipsis enforce a maximum length for the photo descriptions.
