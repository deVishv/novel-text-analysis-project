# Novel Text Analysis with R

### about-this-project :information_source:

This is a R language based project on the book 'The Picture of Dorian Gray' by Oscar Wilde. The text from the novel is used to perform sentiment analysis over the chapters and find the most written words. The data found is 
plotted on line graph and bar graph. The charts help get insights into the emotional structure of the story and overall theme of the writing. 

### features :hammer_and_wrench:

+ Performs sentiment analysis with the Syuzhet R package

+ Plots graphs through ggplot2

+ Uses the downloaded book from [Project Gutenberg](https://www.gutenberg.org/ebooks/174)

### installation-and-usage :arrow_down:

1. Download a copy of the book from [here](https://www.gutenberg.org/ebooks/174) and save it somewhere while noting its path

2. Clone the repository using the following lines on terminal

   ```
   git clone https://github.com/deVishv/novel-text-analysis-project  
   ```

3. Edit the third line in chunk two as follows

   ```R
   novel = readLines("path/to/book.txt", encoding = "UTF-8")
   ```
4. Run all chunks in order

### roadmap :world_map:

- [ ] divide chapters with code instead of manually finding page numbers

- [ ] use the `gutenbergr` package for downloading text
      
### built by vishv kansagara
