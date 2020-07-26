---
layout: post
title:      "A Space for Space"
date:       2020-07-26 16:37:33 +0000
permalink:  a_space_for_space
---


Recently I had an idea for a project I wanted to undertake. As the comet NEOWISE was high in the sky I wanted to find the best time to view it and where it would be in the sky but try as I might I couldn't find a proper source for my location that had up to date information. As I searched further I grew increasingly annoyed that there wasn't some simple way to find astronomical information without directly searching extensively for it. Finally, I found a proper source and with that discovery an idea formed. If the information is so hard to find why not make it easier on future me and anyone else who wishes to use it? So this week I made a scraper with an API to harvest the information on that webpage to bundle into a neat package for use in other projects. Maybe I'm the only one to use it but it's satisfying work. Utilizing Nokogiri as well as open_uri I used Ruby to put together a function that takes the information and gleans the proper information such as rising time and set time of the celestial body as well as apparent magnitude to ensure that visual viewing is possible. I left some room for future additions such as other bodies not visible by naked eye for future use but for now this little API is my favorite project.
