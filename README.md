# DESCRIPTION

To produce the flashcard files found here, the script cardmaker.rb is used.  The script first looks up kanji by grade level, using kanjidic2.xml.  That file gives kanji along with grade level, stroke count, English meaning, onyomi, and kunyomi.  To find word examples for a kanji, the script searches wordfreq_ck for several simple and frequent words containing that kanji.  The script then searches for definitions of these words using edict.txt.  An fodg file is created, which is then converted to odg and slightly hand-modified to address spelling and stylistic concerns.

# COPYRIGHT

The flashcard files and generating script I made are available under the [Creative Commons Share Alike-Attribution 3.0 License](http://creativecommons.org/licenses/by-sa/3.0/).  For attribution, include my name and the links listed below.  The flashcard files depend on edict and kanjidic -- see license information below.

Files by Douglas P Perkins:
* blankcard.fodg
* cardmaker.rb
* flashcards.1.odg
* flashcards.2.odg
* flashcards.3.odg
* flashcards.4.odg
* flashcards.5.odg
* flashcards.6.odg

Pages for citing this work:
* https://dperkins.org/kanji/
* https://identi.ca/dper/

Below is information on the dictionary files providing raw data for the flashcards.  Several of these files require attribution for reuse -- see their respective websites for details.

* kanjidic2.xml:
:* Retrieved 2011-02-21.
::* <http://www.csse.monash.edu.au/~jwb/kanjidic2/>
::* <http://www.csse.monash.edu.au/~jwb/kanjidic2/kanjidic2.xml.gz>
:* Copyright by The Electronic Dictionary Research and Development Group.
:* Available under Creative Commons Share Alike-Attribution 3.0 License.
::* <http://creativecommons.org/licenses/by-sa/3.0/>

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
