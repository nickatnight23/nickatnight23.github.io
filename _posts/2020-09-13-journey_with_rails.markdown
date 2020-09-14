---
layout: post
title:      "Journey with Rails"
date:       2020-09-14 01:02:45 +0000
permalink:  journey_with_rails
---



My project is a shoe app where anyone can create a shoe and then review a shoe. I love shoes and I thought that having a designated site to discuss all kinds of shoes would be cool.
I would like to say that I have a love/hate relationship with this project. I had to take additional time in rails. I spent the extra time reading documentation, watching tutorials, and just getting my hands on as much information as possible to learn and understand how rails function. Here are a couple of things that I struggled with while working on this project.

First, I struggled with the DESTROY action. I had issues implementing it in my app. I was confused on how to add the destroy action to my views. I learned that you had to add the method and delete action to the views page to get it to work.

***<%=link_to 'Destroy', shoe_path(rw.id), method: :delete %>***


I was finally able to get the destroy action to work and delete an object. What helped was reaching out to my cohort and other people I met in the Ruby community because being stuck on one error for days is rough. I find for me what helps the best is if someone has the time to get in a zoom session with you especially if you have a hard time explaining what the error is. Sometimes you explain one error and then that leads into another error, so it is just a lot easier when you both are looking at the code at the same time. It makes explaining the issue a lot easier and it allows what you are learning to sink in better.

A second issue that I had while trying to complete my project was getting my shoes to be able to be viewed on the show page, as well as use the scope method to display the shoes being put in order by rating.  I learned that I had to create a separate views page that would be used for just seeing all the shoes that were rated.
This is the method that I used to calculate the average for a shoe

***def avg_rating

**self.reviews.average(:stars)
end***
**
Overall, working on this project was a great learning experience. It opened my eyes to the fact that Rails can do a lot and that it is important to understand the basics, so that later it will be a lot easier to understand complicated concepts.
