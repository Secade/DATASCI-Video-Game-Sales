![Image](games.jpg)

# Video Game Sales

Outline:
- Talk about the impact of video games and how its sales has become dominant around the world
- Explain why we are studying this topic
- Explain the datasets used
- Breeze through some cleaning processes
- Show 10 Research questions
- Quickly answer and explain the questions
- Concluding Remarks


## Motivation

Video games has served the purpose as a way to escape the real world and into an imaginary world where people can focus on something they truly enjoy. It has become something allows us to de-stress and have fun while playing. It has also allowed friends and strangers to interact or play with each other creating stronger bonds no matter where you are in the world. This is more evident especially during these times of quarantine where people cannot simply meet each other. These video games gave a platform to people to continue to interact with each other and enjoy everyones presence even if it is just online. Video games has also lead to thousands of jobs around the world from game developers, to professional e-sport atheletes, and to livestreamers. Video games has opened countless opportunities for people to experience.

Over the past few decades, video games have slowly taken over the world by storm. From the introduction of the first commercially successful video game "Pong" to the present day cloud gaming services. The gaming industry has been alive for only around 49 years but it has become one of the largest profitable markets in the world. According to the Visual Capitalist, in 2020, the gaming industry was estimated to have earned a revenue of $165 billion. Gaming has become the biggest entertainment market by beating markets like television, film box office, and digital music. Through innovation and constant increase in popularity, it is said that its revenue forecast will hit $291 billion by 2027. It has been a couple of years now that the gaming industry has dominated the world market and has become a more accepted aspect of life for a majority of people around the world.

The visualization below (Made by Pelham Smithers) shows the rise of revenue earned by the gaming industry over the 49 year life span. It shows how different consoles affected the market by gaining pieces of it over the years. It also shows important releases made over the decades.

![Image](timeline.jpg)

The speed of how fast the gaming industry has grown has peaked the interest of our group hence we wanted to dwell deeper into the video game sales. We wanted to find out the different players or factors that come into play when it comes to high successful sales. We want to be able to find certain trends within the video game sales. We also want to find out who are the top conteders in their own category. Through this, we might be able to see what can make a successful game.

## Datasets Used

Before we dive into exploring the data regarding video game sales, we want to explain first the data set that we used. A data set is basically a file that contains thousands of information regarding a certain topic. For this research, we looked through a free public data set library website called Kaggle which allows people to download data sets provided by other people. After a bit of searching, we found a particularly good data set simply called Video Game Sales 2019. It contained all the information we needed. It had over 55,000+ games and had information like the game's genre, publisher, sales numbers, and esrb rating. 

The way the author (Abdulshaheed Alqunber) collected this data is through an automated trick called web scrapping wherein you write a certain script that will go through a specific website and collect information from it. The author based his web scrapping script of GregorUT's script which utilizes the Python library called "BeautifulSoup" which is a web scrapping library. They wanted to collect data from a verified source which is why they chose to scrape the data from VGChartz.com which is a public website that holds statistics on thousands of games from their release dates, to genres, and to their sales. So with that, they developed the script that went through the entire website and collected the data they needed. This is how the data that you will see later in the database was collected. This entire process may seem a bit sketchy but the authors made sure that what they are doing is legal and allowed by the website owners.

After getting the Video Game Sales 2019 dataset, we thought if we could possibly get a more updated database since the 2019 version is 2 years old already. The first thing that we did is to try to use the web scrapping script that the authors published in order to scrape the information ourselves. However, after thinkering and setting up the scripts, they didn't seem to run as intended. The script kept crashing and we noticed that the problem was related to the proxy server that we needed to use in order to connect to the site. After multiple failed attempts to find a working proxy, we decided to look for a more updated dataset in Kaggle. Thankfully, we were able to find a more recent version. The data set is called Video Game Sales 2020 which was based off the 2019 but was published by a different author. This version collected its data on July 7, 2020. We were happy with this update already. The biggest difference between the two datasets is that the 2020 version lacks the ESRB Ratings for the games. ESRB Ratings are essentially age-restriction labels placed by the ESRB Organization. This rating helps identify what age group can play said game. 

https://www.grandviewresearch.com/industry-analysis/video-game-market
https://www.reuters.com/article/sponsored/popularity-of-gaming
https://www.visualcapitalist.com/50-years-gaming-history-revenue-stream/
---- Don't Mind These, To Be Deleted later ----

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/Secade/DATASCI-Video-Game-Sales/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Secade/DATASCI-Video-Game-Sales/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.


TEST
