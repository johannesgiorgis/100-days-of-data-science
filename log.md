# 100 Days Of Data Science - Log

### Day 1: Wednesday, March 20th, 2019

**Today's Progress**: I worked through _Chi-squared tests_ and _Multi category chi-squared tests_ missions within DataQuest's Data Scientist _Probability and Statistics_ step.

**Thoughts**: After working through implementing the chi-square by hand (not necessarily the most complicated), I was provided with the correct function to use [`scipy.stats.chisquare`](http://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.mstats.chisquare.html). This reminded me of a statement I keep hearing repeatedly - we don't necessarily need to know the full details of the various algorithms to use them thanks to libraries like `scipy` - we just need to know WHEN and HOW to use them correctly.

**Link(s) to work**: No links. But will be starting on a guided project tomorrow which will utilize my learnings from today.

### Day 2: Thursday, March 21st, 2019

**Today's Progress**: I completed the _Guided Project: Winning Jeopardy_ where I applied the Chi-Squared test to come up with a winning strategy for Jeopardy.

**Thoughts**: It was interesting to see the application of Chi-Squared test in a real world setting. No breakthroughs in winning Jeopardies but definitely starting to see and understand where this tool can be used. I'll need to do some more reading, apply it to my own project and write a blog about it.

**Link(s) to work**: 
1. [Winning Jeopardy Notebook](https://nbviewer.jupyter.org/github/johannesgiorgis/dataquest/blob/master/data_science_path/projects/project16_winning_jeopardy/project16_winning_jeopardy.ipynb)

### Day 3: Friday, March 22nd, 2019

**Today's Progress**: After a false start on DataQuest's Data Engineering path (_Introduction to Postgres_) due to some technical issues with the website, I worked through the _Introduction to Spark_ mission of the Data Scientist path. I installed and set up Spark on my computer and verified PySpark worked via CLI and Jupyter Notebook.

**Thoughts**: It was great revising my Spark knowledge and getting the chance to use PySpark again. Also `findspark` is a nifty python package for finding the SPARK_HOME environment variable without you having to explicitly call it in your scripts. I look forward to diving deeper into Spark and building applications and pipelines with it.

**Link(s) to work**: 
1. [Verify Spark Installation via Jupyter Notebook](https://nbviewer.jupyter.org/github/johannesgiorgis/dataquest/blob/master/data_science_path/verify_spark_installation/test_spark_installation.ipynb)

### Day 4: Saturday, March 23rd, 2019

**Today's Progress**: I finished up DataQuest's _Spark and Map-Reduce_ mission.

**Thoughts**: The course was a good overview of Spark's capabilities, covering transformations and actions, Spark DataFrames and Spark SQL. I'll plan on getting some more hands on experience by using Spark on some larger datasets as part of a Data Science Challenge.

**Link(s) to work**: 
1. [DataQuest's Spark & MapReduce Mission](https://app.dataquest.io/course/spark-map-reduce)

### Day 5: Sunday, March 24th, 2019

**Today's Progress**: I worked through the second Data Science Challenges, figuring out how to navigate through multiple pages of PacktPub's All Products pages. I also worked through DataQuest's _Creating Postgres Tables_ course.

**Thoughts**: Figuring out web scraping can be very tedious yet very rewarding once you get it working. Also diving deeper into how to create tables in Psotgres and optimizing for space by choosing the right datasets was a very interesting/valuable lesson.

**Link(s) to work**: 
1. [Data Science Challenges 2: Web Scraping](https://github.com/johannesgiorgis/ds_challenges/tree/master/02_web_scraping)

### Day 6: Monday, March 25th, 2019

**Today's Progress**: I  worked through DataQuest's _Managing Created Tables_ and _Loading and Extracting Data with Tables_ missions.

**Thoughts**: There are so many options when it comes to extracting and loading data into a Postgres DB depending on your purposes and goals - you can do it via python code or SQL, use `INSERT` or `COPY` operations, etc. I look forward to applying these learnings in a hands on projects soon.

**Link(s) to work**: None for today.

### Day 7: Tuesday, March 26th, 2019

**Today's Progress**: I  worked through the remainder of DataQuest's _Postgres for Data Engineers_ course. I started working on the Guided Project, which entails building a Postgres Database from a CSV file.

**Thoughts**: Finally having gone through the learning material, it is exciting to get to apply that to building a database from real world data. Also achieved 14% of the Data Engineer path in 5 days! Yay for consistency! Most of the stuff I covered so far wasn't totally new to me, but still looking forward to finishing up this track and start building end to end data pipeline projects.

**Link(s) to work**: None for today.


### Day 8: Wednesday, March 27th, 2019

**Today's Progress**: I  worked through DataQuest's _Optimizing Postgres Databases_ course, where I learned more about Postgres internal systems and tables.

**Thoughts**: Working through this was a bit of a drag but it was very useful material none the less.

**Link(s) to work**: None for today.


### Day 9: Thursday, March 28th, 2019

**Today's Progress**: I  worked through DataQuest's _Debugging Postgres Queries_ course and started working on the _Using an Index_ course. The first course covers the `EXPLAIN` command and how to interpret the results to evalute the performance of our query. The Index course expanded on this by introducing the use of an Index to further optimize our queries.

**Thoughts**: I was already familiar with the `EXPLAIN` command, so this was good review within the context of Postgres.

**Link(s) to work**: None for today.


### Day 10: Friday, March 29th, 2019

**Today's Progress**: I  finished the _Using an Index_ course I started yesterday as well as the _Advanced Indexing_ course.

**Thoughts**: I dived deeper into further optimizing Postgres queries via Indexing and Multi Column indexing, partial indexing, etc. I enjoy simplifying and speeding up my code when I develop so it's great to learn about the tools that help you achieve something similar with your SQL queries.

**Link(s) to work**: None for today.


### Day 11: Sunday, March 31st, 2019

**Today's Progress**: Yesterday I broke my streak - I only did 30 minutes of the _Vacuuming Postgres Databases_ course, so I didn't log it. Today, I went back to the first guided project - _Storing Storm Data_ and worked through that, building my first database/table from a csv file, which combined all the lessons so far - creating and managing users, creating table schemas with appropriate data types and of course, inserting data from csv files.

**Thoughts**: It was great putting all the learnings so far towards a practical project that solved a problem. I definitely feel pretty comfortable working with Postgres and look forward to using it in future projects with python.

**Link(s) to work**: [Storing Storm Data Project](https://nbviewer.jupyter.org/github/johannesgiorgis/dataquest/blob/master/data_engineer_path/projects/project01_storing_storm_data/project01_storing_storm_data.ipynb)


### Day 12: Monday, April 1st, 2019

**Today's Progress**: I worked through _Optimizing Dataframe Memory Footprint_, learning about how Pandas represents values in a data set under the hood, and how to reduce a Dataframe's memory footprint.

**Thoughts**: So far, I have worked with relatively small datasets and Pandas. Understanding what happens under the hood has been eye opening. I look forward to using these learnings when I use Pandas with large datasets.

**Link(s) to work**: None for today.


### Day 13: Tuesday, April 2nd, 2019

**Today's Progress**: I started working on the _Practice Optimizing Dataframes and Processing in Chunks_ project.

**Thoughts**: Today, I got the opportunity to putting my learnings in optimizing DataFrames to practice.

**Link(s) to work**: [Practice Optimizing Dataframes and Processing in Chunks](https://nbviewer.jupyter.org/github/johannesgiorgis/dataquest/blob/master/data_engineer_path/projects/project02_practice_optimizing_dataframes_and_processing_in_chunks/project02_practice_optimizing_dataframes_and_processing_in_chunks.ipynb)


### Day 14: Wednesday, April 3rd, 2019

**Today's Progress**: I completed the _Practice Optimizing Dataframes and Processing in Chunks_ project.

**Thoughts**: Seeing the memory reduction and optimization of datatypes in a dataframe was pretty satisfying. I achieved a **69%** reduction in memory usage by optimizing the column's datatypes - either witching to a more efficient subtype (float64 -> float32) or switching string columns to more appropriate data types (category, float, etc). I can see how useful this would be when we are looking to explore with very large datasets that won't fit fully in memory.

**Link(s) to work**: [Practice Optimizing Dataframes and Processing in Chunks](https://nbviewer.jupyter.org/github/johannesgiorgis/dataquest/blob/master/data_engineer_path/projects/project02_practice_optimizing_dataframes_and_processing_in_chunks/project02_practice_optimizing_dataframes_and_processing_in_chunks.ipynb)


### Day 15: Friday, April 5th, 2019

**Today's Progress**: I completed the _CPU Bound Programs_ course.

**Thoughts**: This course covered time and space complexity, profiling and refactoring. Most of the concepts were review for me, yet being applied in new contexts. Lots of great resources to follow up on.

**Link(s) to work**: None for today.