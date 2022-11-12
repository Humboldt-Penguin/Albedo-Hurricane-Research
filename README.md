Email: [z.kamal2021@gmail.com](mailto:z.kamal2021@gmail.com) or [zain.kamal@rutgers.edu](mailto:zain.kamal@rutgers.edu), I compulsively check both.

Special thanks to Professor Andrew Gerrard from NJIT for his guidance through this project and help in obtaining BBSO data.

---

**Final update: See the "Final Report" PDF.**

* We gave our [final presentation](https://www.youtube.com/watch?v=_kpkBVtLt3k) at the Governor's STEM Scholars symposium in May 2022. My students received an award for science communication :>

---

# Albedo/Hurricane Research (Ongoing)

## Background

Earth's albedo is an essential determinant of the earth's climate, since, in the broadest sense, changes in climate arise from the simultaneous evolution of the solar intensity, the Earth's reflectance, and greenhouse insulation. However, since the mid-1990's, the changing albedo was (and probably still is) the least understood of the three parameters (Goode et al. 2021).

## Research Summary

We expect global warming to increase the frequency of hurricanes, which would increase Earth's albedo (solar reflectance) because clouds are more reflective than most land/water. This would cause a sort of "self-regulating" decrease in global temperatures. However, a recent landmark study (Google "The Earth is Dimming") has observed an unprecedented _decrease_ in Earth's albedo over the past 20 years, which seems to contradict our model. Goode et al hypothesized that this is because of a warming of the eastern pacific and consequent reduction in low-lying cloud cover. Our research seeks to hone in on whether albedo measurements/observations over the past two decades reflect short-term anomalies or long term trends. This is signfificant because the latter would indicate a gap in our understanding of how cloud-cover affects global temperatures.

**In short, we're trying to quantify the correlation between cloud cover over the Northern Atlantic and Earth's albedo.**

## Results so far

As of now, Quantify_Cloud_Cover.ipynb can go through a folder of GOES satellite files (ranging over the lifespan of a hurricane, plus/minus 7 days) and plot the percent of the Northern Atlantic covered by clouds over time. We see decent agreement between Bands 3-18 (14.06-3.74 nanometer wavelengths). A preliminary summary of my results can be seen in the file "Quantifying Cloud Cover during Hurricane Sandy (Zain Kamal).pdf".

I am compiling the documentation I used and a detailed record of my methodology, and am happy to provide it upon request. I plan on doing a formal write-up of my results in May, and hope to present at the American Geophysical Union conference in Fall 2022.

---
# Mentorship

As a research team lead for the NJ Governor's STEM Scholars program, I'm mentoring a group of ten high schoolers through this research project. What this means is that I teach the students Python and data analysis skills from scratch and guide them through the process of recreating code I've previously written. As of February 2022, they've learned how to access data from the NOAA GOES satellites using FTP protocol, visualize it with NASA's Panoply software, and are currently learning the basics of Python and a few scientific libraries in preparation of recreating Quantify_Cloud_Cover.ipynb

Here are some of my pre-recorded video tutorials for my students:
* [Downloading GOES satellite cloud data with NOAA CLASS](https://www.youtube.com/watch?v=SBWWs-ZxDWw)
* [GSS Coding Lessons 1: Introduction to Python](https://www.youtube.com/watch?v=rflh9fBcy0M)
