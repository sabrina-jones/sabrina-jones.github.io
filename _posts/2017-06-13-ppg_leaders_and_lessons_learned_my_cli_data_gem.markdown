---
layout: post
title:  "PPG Leaders and Lessons Learned: My CLI Data Gem"
date:   2017-06-13 14:48:59 +0000
---


I created my ruby gem, or library, "ppg_leaders" using the command "bundle gem ppg_leaders" this generated all of the initial files. 

The gemspec should be completed first, lesson learned. When testing my code, I came across a few errors. These errors related to "TODO" were a bit puzzling. I was able to trace them to the gemsepc file, after I added the appropriate values, I was able to proceed. The ppg_leaders.gemspec file is also where I worked to require dependencies for my project. These dependencies were helpful when scrapping the three websites that I used to complete the gem. 
 
The coding of the gem was not as difficult as I thought it would be initially. It was the process of running into errors with the file system, understanding those errors and then resolving them that was at times challenging. I would say that the biggest roadblock that I faced was, scrapping the website that I initially wanted to use to create my ppg_leaders rubygem. There was not an identifier unique enough for me to grab the exact data that I was looking for from the website. After spending hours trying to scrape a page that was not designed for me to retrieve the information that I required for my design, I looked for a better page. The lesson, don't spend valuable coding time on retrieving data from a page when it is simply not possible, find a better way!

After a few more hours and a few more lines of code, the ppg_leaders-cli-app was working as I had designed. The users is shown a list and asked to pick a player that they would like to learn more about. 
 
I've found that I learn the greatest lessons by making what seem to be great mistakes. I am not exactly sure what I did wrong but my initial gem files did not include the license or code of conduct. While I could continue to code my project, I wanted to figure out why I didn't have those files. Enter http://bundler.io/man/bundle-gem.1.html, the doc that helped me fix my problem. 
 
The options I needed were "--mit" for the liscence and "--coc" for the code of conduct So the commands would be bundle gem ppg_leaders --mit and bundle gem ppg_leaders --coc respectively. Problem solved.
Lastly, I published my cli gem to rubygems, success. 


 


