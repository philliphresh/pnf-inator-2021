
# Aren’t you a little old to be watching Phineas and Ferb?

Yes, yes I am. I love Phineas and Ferb. From the jokes to the songs to
the inators, everything about it brings me joy. Going through a recent
watch on Disney+ inspired me to analyze Phineas and Ferb data,
specifically, song data.

# Where did you get the data?

While making the plots (see below) was the more exciting part, gathering
the data was definitely the more challenging and time-consuming part of
this project. After looking around various websites, I ended up deciding
to web scrape from the [Phineas and Ferb Fandom
page](https://phineasandferb.fandom.com/wiki/Phineas_and_Ferb_Wiki). To
pull IMDB ratings, I obviously also had to scrape data from
[IMDb](https://www.imdb.com/title/tt0852863/episodes?season=1).

Since Fandom is a Wiki site, the webpages scraped were not always in a
consistent format and some assumptions needed to be made. The three
largest assumptions made were:

1.  The first episode to be listed in a song’s narrative description is
    the episode it first aired in.
2.  All the data taken from the Fandom Wiki is correct. For the most
    part I think this is a safe assumption but genres could be
    misclassified, episodes could be mislabeled, etc.
3.  Each episode paired would score the same IMDb rating if voted on
    together. This is probably not true but IMDb only takes ratings for
    episodes paired in a 22-ish minute airing.

# Whatchyu doin’?

The rest of this report is organized by questions I thought were
interesting or plots I thought might be cool.

## What are the most common genres?

The following plot shows the top most common song genres in Phineas and
Ferb and their prevalence among different seasons. Even though this is
probably the most basic question to ask about the songs, I thought it
was interesting because even Dan Povenmire himself might not have an
idea of just how many pop and rock songs there are (or how few jazz
songs). I also don’t mean to imply that there needs to be an equal
distribution of genres, I believe the song should fit the context of the
episode around it.

![](README_files/figure-gfm/unnamed-chunk-4-1.png)<!-- -->
