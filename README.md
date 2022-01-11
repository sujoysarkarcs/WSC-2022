# Heuristically Annotated Sanskrit Named Entity Recognition Dataset
Data for the paper titled: "Pre-annotation Based Approach for Development of a Sanskrit Named Entity Recognition Dataset".

## Description
The selected corpus is Śrīmad-Bhāgavatam. The heuristic works based on string-matching algorithms. The key idea is to compare transliterated Sanskrit text with an English translation and identify words of similar forms as likely named entities (NE). A gazetteer is applied to
further classify the NEs into semantic classes. The gazetteer used is curated from Monier-Williams Sanskrit English Dictionary.

### Data
- Gazetteer: a list of names prepared from Monier-Williams Sanskrit English Dictionary. For each name the the tag is prepared automatically based on the description of the name in the dictionary.
- Web scrapped: The data for Śrīmad-Bhāgavatam along with translation scrapped form www.vedabase.io
- Gold annotation: 1000 verses manually annotaed with there named entity category: Person, Location, Misc
- Heuristic annotation: The NEs are identified automatically based on the heuristic discussed in the paper.
