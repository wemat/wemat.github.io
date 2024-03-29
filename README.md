# Projects from Scratch 👨‍💻

I like data, programming and solving problems. Learning by doing is my preferred approach. So, here are a few selected projects that I worked on. The scope of the projects varies from *small* (1 day or less) to *medium* (1-3 weeks) and *large* (several months). 

If you have ideas for cool projects, I am up for collaberation. Contact me at: wemat.web@gmail.com

## 1. Sports Analytics 🏃‍♂️
- Scope: Medium
- Tech: Rest API, Python with Dash, Plotly, Pandas and Requests
- Code: <a href="https://github.com/wemat/StravaDash">Github StavaDash</a>
- The App: <a href="https://sport-analytics-wemat.herokuapp.com">Dash Sports Analytics</a>

I use Strava when I go for a run or mountain biking. In this project, I connected to Strava's Rest API and developed a dashboard with Dash. My opinion of Dash? In Power BI (I've worked with it a lot) you can click together a nice looking dashboard fairly quickly. With Dash it takes a while to set up something seemingly simple (like this project here). There is no GUI. Everything has to be coded. But then again, in Power BI, as soon as the requirements are a bit non-standard, it can become punishing. With Dash we have all the power of python and it's great libraries. So even complex machine-learning use-cases can be combined with Dash seamlessly. 

At the beginning of the project I wanted to get an overview: <a href="https://github.com/wemat/StravaAnalytics/blob/main/analytics/strava_api.ipynb">Here</a> is a jupyter notebook with the explanatory data analysis.

<div style="padding:75% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/793594012?h=d7958a4103&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen style="position:absolute;top:0;left:0;width:100%;height:100%;" title="Bildschirmaufnahme 2023-01-28 um 09.45.40.mov"></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

<!--div style="padding-bottom:65%; position:relative; display:block; width: 100%">
  <iframe width="100%" height="100%"
    src="https://sport-analytics-wemat.herokuapp.com"
    frameborder="0" allowfullscreen="" style="position:absolute; top:0; left: 0">
  </iframe>
</div-->


## 2. 🏭 Real Time Production Dashboard in Power BI 
- Scope: Small
- Tech: Python, Power BI

This is a mockup for a real time dashboard that shows the output rate of a machine. I used python to push the data to the REST API of Power BI. 
The data is generated in real time by a simple simulation of a machine's output. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/gaC_FTTJbC0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


## 3. 🔥 Pytorch Implementation of the Paper *Attention is all you need*
<img src="https://pbs.twimg.com/media/DCYHlQCUMAAsLhG?format=jpg&name=small" style="width:512px;height:384px;" alt="Dwight's Attention">

- Scope: Medium
- Tech: Python with Pytorch
- Commentated Code:  <a href="https://www.kaggle.com/code/soupmonster/attention-is-all-you-need-pytorch">Kaggle Notebook</a> 

Have you ever wondered how language translation tools such as Deepl got so damn good in the last few years? In my opinion *Attention is all you need* is THE game changer that made this possible. The paper, written in 2017 had a significant impact on NLP and deep learning and paved the way for later breakthroughs such as BERT or GPT-3. The model of 2017 is sometimes refered to as the original transformer.

To test my implementation I used a dataset with ~135k French-English sentence pairs and trained my transformer to translate from French to English. Check the Kaggle notebook to get an intuition about how that works!

## 4. Django Web Application: Website and Reservation Tool  ⛷
Scope: Large\
Tech: Django, Python, MySQL, Bootstrap, HTML, CSS

I developed <a href="https://www.tuoretta.ch/">this</a>  website for a holiday appartment (in Ardez,Lower-Engadin) where users can create an account and make reservations. I created a calendar widget from scratch which shows the availability to website visitors. Logged in users also see the concrete bookings in the calendar.


## 5. 🛸 Mars Lander 
- Scope: Medium-Large
- Tech: Python with Numpy and Matplotlib
- Code:  <a href="https://github.com/wemat/MarsLander/blob/main/mars_lander.py">Github MarsLander</a> 

I love <a href="https://www.codingame.com/start">CodinGame</a>. (find me on CG: wemat) Soon after I began programming this site really pushed me to learn more. By now I solved two "very hard-", a bunch of "hard-" and altogether around 40 puzzles. Even though I am not a professional developer it is a lot of fun to implement an algorithm from scratch. :)

One really interesting puzzle is the *Mars Lander*. The goal of this puzzle is to safely land a spaceship on Mars. 
To solve this I programmed a <a href="https://en.wikipedia.org/wiki/Genetic_algorithm">genetic algorithm</a>. But first I had to create a physics simulation of the rockets trajectory. It took me several weeks to make it work and I still have to optimize the algorithm's speed to crack all the tests on CG. :) 

The snippet bellow shows the iterations (generations) of the genetic algorithm. I visualized it with Matplotlib. 

<div style="padding:75% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/775979072?h=ec9eaf3a97&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen style="position:absolute;top:0;left:0;width:75%;height:75%;" title="GeneticAlgo.mov"></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

