## Title : debeyohiru_05_hidden1

## Difficulty : medium

We want to know debeyohiru's real name.
Answer the name you believe is their legal name.

For example, if their real name were Sanae Takaichi, the flag would be SWIMMER{Sanae Takaichi}.
Please answer in Latin alphabet; you do not need to consider Kanji or Hiragana.

Observations:
Since we got his portfolio website and the email address from previous challenges, at first I thought we had to use ghunt or sherlock for this challenge but there were not any visible results but then I remembered that sometimes developers leave their names in the source code so since this is a portfolio website I did `View Page Source` and there were still not visible results but I did managed to find the style.css and script.js files in the source. There were no visible results in style.css but when I went into script.js the first thing that shows up at the top of the source page is `@author Gotanno Tsubasa`.

## Flag : `SWIMMER{Gotanno Tsubasa}`
