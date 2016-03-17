# Description

To produce the flashcard files found here, the script cardmaker.rb is used.  The script first looks up kanji by grade level, using kanjidic2.xml.  That file gives kanji along with grade level, stroke count, English meaning, onyomi, and kunyomi.  To find word examples for a kanji, the script searches wordfreq_ck for several simple and frequent words containing that kanji.  The script then searches for definitions of these words using edict.txt.  An fodg file is created, which is then converted to odg and slightly hand-modified to address spelling and stylistic concerns.

# Copyright

The script `cardmaker.rb` is licensed under the GPL v3.0.  The resultant flashcard files (contained in `grade/` and `jlpt/`) are available under the [Creative Commons Share Alike-Attribution 3.0 License](http://creativecommons.org/licenses/by-sa/3.0/).



* `kanjidic2.xml`. Retrieved 2016-03-18. [http://www.csse.monash.edu.au/~jwb/kanjidic2/] [http://www.csse.monash.edu.au/~jwb/kanjidic2/kanjidic2.xml.gz]. Copyright by The Electronic Dictionary Research and Development Group. Available under [Creative Commons Share Alike-Attribution 3.0 License](http://creativecommons.org/licenses/by-sa/3.0/).

edict.txt:
- Retrieved 2011-02-21.
	- http://www.csse.monash.edu.au/~jwb/edict.html
	- http://ftp.monash.edu.au/pub/nihongo/edict.gz
- Copyright by the Electronic Dictionary Research and Development Group.
- Made available under Creative Commons Share Alike-Attribution 3.0 License.
	- http://creativecommons.org/licenses/by-sa/3.0/
	
wordfreq_ck:
- Retrieved 2011-02-21.
	- http://ftp.monash.edu.au/pub/nihongo/00INDEX.html
	- http://ftp.monash.edu.au/pub/nihongo/wordfreq_ck.gz
- File is in the public domain.
	- http://www.bcit-broadcast.com/monash/wordfreq.README

# See also

* <https://dperkins.org/arc/2011-03-22.kanji%20flashcards.html>
* <https://identi.ca/dper/>
* <https://twitter.com/dpp0>
