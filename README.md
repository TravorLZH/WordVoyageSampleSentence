# [Wordvoyage](http://wordvoyage.com/wv-vocabulary) Sample Sentence Fetcher

`Wordvoyage` is a website that provides lessons for us to study new vocabulary words. Each lesson normally contains 6 sections: Spelling, Pronunciation, Word Root, Games, Sentence Writing and Quiz, in which Sentence Writing costs a lot of time.

Sentence Writing section lets me write 2 sentences. One from audio and the other by my own. After doing several lessons. I discovered that the sentences are already displayed in `Unit Word Study List`. So, this program written in `Python 3` helps you fetch sentence from a saved `Unit Study List - Word Voyage.html`.

## Usage

Run `main.py` to generate a JSON file called `sentences.json`, then run `findsentence.py` to find sentence in the file by entering words.

## Few words for regex

I really appreciate `regex` because it helps me a lot on searching sentences and vocabulary words in an HTML Document. It really simplifies my program.