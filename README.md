Ruby Natural Language Processing Resources
=======

A collection of Natural Language Processing (NLP) Ruby libraries, tools and software. Suggestions and contributions are welcome.

### Categories

* [APIs](#apis)
* [Bitext Alignment](#bitext-alignment)
* [Classification](#classification)
* [Date and Time](#date-and-time)
* [Error Correction](#error-correction)
* [Full-Text Search](#full-text-search)
* [Keyword Ranking](#keyword-ranking)
* [Language Detection](#language-detection)
* [Machine Learning](#machine-learning)
* [Machine Translation](#machine-translation)
* [Miscellaneous](#miscellaneous)
* [Multipurpose Tools](#multipurpose-tools)
* [Ngrams](#ngrams)
* [Parsers](#parsers)
* [Part-of-Speech Taggers](#part-of-speech-taggers)
* [Readability](#readability)
* [Regular Expressions](#regular-expressions)
* [Ruby NLP Presentations](#ruby-nlp-presentations)
* [Sentence Segmentation](#sentence-segmentation)
* [Stemmers](#stemmers)
* [Stop Words](#stop-words)
* [Summarization](#summarization)
* [Text Extraction](#text-extraction)
* [Text Similarity](#text-similarity)
* [Tokenizers](#tokenizers)
* [Word Count](#word-count)

## APIs

Client libraries to various 3rd party NLP API services.

* [alchemy_api](https://github.com/dbalatero/alchemy_api) - provides a client API library for AlchemyAPI's NLP services
* [aylien_textapi_ruby](https://github.com/AYLIEN/aylien_textapi_ruby) - AYLIEN's officially supported Ruby client library for accessing Text API
* [napi-ruby](https://github.com/Maluuba/napi-ruby) - a simple Ruby wrapper for the Maluuba nAPI
* [poliqarpr](https://github.com/apohllo/poliqarpr) - Ruby client for Poliqarp text corpus server
* [wlapi](https://github.com/arbox/wlapi) - Ruby based API for the project Wortschatz Leipzig

## Bitext Alignment

Bitext alignment is the process of aligning two parallel documents on a segment by segment basis. In other words, if you have one document in English and its translation in Spanish, bitext alignment is the process of matching each segment from document A with its corresponding translation in document B.

* [alignment](https://github.com/bloomrain/alignment) - alignment functions for corpus linguistics (Gale-Church implementation)

## Classification

Classification aims to assign a document or piece of text to one or more classes or categories making it easier to manage or sort.

* [Classifier](https://github.com/cardmagic/classifier) - a general module to allow Bayesian and other types of classifications
* [Latent Dirichlet Allocation](https://github.com/ealdent/lda-ruby) - used to automatically cluster documents into topics
* [liblinear-ruby-swig](https://github.com/tomz/liblinear-ruby-swig) - Ruby interface to LIBLINEAR (much more efficient than LIBSVM for text classification and other large linear classifications)
* [linnaeus](https://github.com/djcp/linnaeus) - a redis-backed Bayesian classifier
* [maxent_string_classifier](https://github.com/mccraigmccraig/maxent_string_classifier) - a JRuby maximum entropy classifier for string data, based on the OpenNLP Maxent framework
* [nbayes](https://github.com/oasic/nbayes) - a full-featured, Ruby implementation of Naive Bayes
* [stuff-classifier](https://github.com/alexandru/stuff-classifier) - a library for classifying text into multiple categories

## Date and Time

* [Chronic](https://github.com/mojombo/chronic) - a pure Ruby natural language date parser
* [Chronic Between](https://github.com/jrobertson/chronic_between) - a simple Ruby natural language parser for date and time ranges
* [Chronic Duration](https://github.com/hpoydar/chronic_duration) - a simple Ruby natural language parser for elapsed time
* [Kronic](https://github.com/xaviershay/kronic) - a dirt simple library for parsing and formatting human readable dates
* [Nickel](https://github.com/iainbeeston/nickel) - extracts date, time, and message information from naturally worded text
* [Tickle](https://github.com/yb66/tickle) - a natural language parser for recurring events.

## Error Correction

* [Chat Correct](https://github.com/diasks2/chat_correct) -  shows the errors and error types when a correct English sentence is diffed with an incorrect English sentence
* [gingerice](https://github.com/subosito/gingerice) - Ruby wrapper for correcting spelling and grammar mistakes based on the context of complete sentences

## Full-Text Search

* [ferret](https://github.com/jkraemer/ferret) - an information retrieval library in the same vein as Apache Lucene
* [ranguba](http://ranguba.org/) - a project to provide a full-text search system built on Groonga

## Keyword Ranking

* [graph-rank](https://github.com/louismullie/graph-rank) - Ruby implementation of the PageRank and TextRank algorithms
* [highscore](https://github.com/domnikl/highscore) - find and rank keywords in text

## Language Detection

* [Detect Language API Client](https://github.com/detectlanguage/detectlanguage-ruby) - detects language of given text and returns detected language codes and scores
* [whatlanguage](https://github.com/peterc/whatlanguage) - a language detection library for Ruby that uses bloom filters for speed

## Machine Learning

* [Decision Tree](https://github.com/igrigorik/decisiontree) - a ruby library which implements ID3 (information gain) algorithm for decision tree learning
* [rb-libsvm](https://github.com/febeling/rb-libsvm) - implementation of SVM, a machine learning and classification algorithm
* [RubyFann](https://github.com/tangledpath/ruby-fann) - a ruby gem that binds to FANN (Fast Artificial Neural Network) from within a ruby/rails environment

## Machine Translation

* [microsoft_translator](https://github.com/ikayzo/microsoft_translator) - Ruby client for the microsoft translator API 
* [Google API Client](https://github.com/google/google-api-ruby-client) - Google API Ruby Client 

## Miscellaneous

* [gibber](https://github.com/timonv/gibber) - Gibber replaces text with nonsensical latin with a maximum size difference of +/- 30%
* [hiatus](https://github.com/ahanba/hiatus) - a localization QA tool
* [Naturally](https://github.com/dogweather/naturally) - Natural (version number) sorting with support for legal document numbering, college course codes, and Unicode
* [rwordnet](https://github.com/doches/rwordnet) - a pure Ruby interface to the WordNet lexical/semantic database
* [twitter-text](https://github.com/twitter/twitter-text/tree/master/rb) - gem that provides text processing routines for Twitter Tweets

## Multipurpose Tools

The following are libraries that integrate multiple NLP tools or functionality.

* [nlp](https://github.com/knife/nlp) - NLP tools for the Polish language
* [NlpToolz](https://github.com/LeFnord/nlp_toolz) - Basic NLP tools, mostly based on OpenNLP, at this time sentence finder, tokenizer and POS tagger implemented, plus Berkeley Parser
* [Open NLP (Ruby bindings)](https://github.com/louismullie/open-nlp)
* [Stanford Core NLP (Ruby bindings)](https://github.com/louismullie/stanford-core-nlp)
* [Treat](https://github.com/louismullie/treat) - natural language processing framework for Ruby

## Ngrams

* [N-Gram](https://github.com/reddavis/N-Gram) - N-Gram generator in Ruby
* [ngram](https://github.com/tkellen/ruby-ngram) - break words and phrases into ngrams

## Parsers

A natural language parser is a program that works out the grammatical structure of sentences, for instance, which groups of words go together (as "phrases") and which words are the subject or object of a verb.

* [linkparser](https://github.com/ged/linkparser) - a Ruby binding for the Abiword version of CMU's Link Grammar, a syntactic parser of English

## Part-of-Speech Taggers

* [engtagger](https://github.com/yohasebe/engtagger) - English Part-of-Speech Tagger Library; a Ruby port of Lingua::EN::Tagger
* [rbtagger](http://rbtagger.rubyforge.org/) - a simple ruby rule-based part of speech tagger
* [TreeTagger for Ruby](https://github.com/LeFnord/rstt) - Ruby based wrapper for the TreeTagger by Helmut Schmid

## Readability

* [lingua](https://github.com/dbalatero/lingua) - Lingua::EN::Readability is a Ruby module which calculates statistics on English text

## Regular Expressions

* [CommonRegexRuby](https://github.com/talyssonoc/CommonRegexRuby) - find a lot of kinds of common information in a string
* [regexp-examples](https://github.com/tom-lord/regexp-examples) - generate strings that match a given regular expression
* [verbal_expressions](https://github.com/ryan-endacott/verbal_expressions) - make difficult regular expressions easy

## Ruby NLP Presentations

* *Natural Language Processing with Ruby* [[video ArrrrCamp 2014](https://www.youtube.com/watch?v=5u86qVh8r0M) | [video Ruby Conf India](https://www.youtube.com/watch?v=oFmy_QBQ5DU)] - [Konstantin Tennhard](https://github.com/t6d) (2014)
* *How to parse 'go' - Natural Language Processing in Ruby* [[slides](http://www.slideshare.net/TomCartwright/natual-language-processing-in-ruby)] - [Tom Cartwright](https://github.com/tomcartwrightuk) (2013)
* *Natural Language Processing in Ruby* [[slides](https://speakerdeck.com/brandonblack/natural-language-processing-in-ruby) | [video](http://confreaks.tv/videos/railsconf2013-natural-language-processing-with-ruby)] - [Brandon Black](https://github.com/brandonblack) (2013)

## Sentence Segmentation

Sentence segmentation (aka sentence boundary disambiguation, sentence boundary detection) is the problem in natural language processing of deciding where sentences begin and end. Sentence segmentation is the foundation of many common NLP tasks (machine translation, bitext alignment, summarization, etc.).

* [Pragmatic Segmenter](https://github.com/diasks2/pragmatic_segmenter)
* [Punkt Segmenter](https://github.com/lfcipriani/punkt-segmenter)
* [TactfulTokenizer](https://github.com/zencephalon/Tactful_Tokenizer)
* [Scapel](https://github.com/louismullie/scalpel)
* [SRX English](https://github.com/apohllo/srx-english)

## Stemmers

Stemming is the term used in linguistic morphology and information retrieval to describe the process for reducing inflected (or sometimes derived) words to their word stem, base or root form.

* [Ruby-Stemmer](https://github.com/aurelian/ruby-stemmer) - Ruby-Stemmer exposes the SnowBall API to Ruby
* [uea-stemmer](https://github.com/ealdent/uea-stemmer) - a conservative stemmer for search and indexing

## Stop Words

* [clarifier](https://github.com/meducation/clarifier)
* [stopwords](https://github.com/brez/stopwords) - really just a list of stopwords with some helpers
* [Stopwords Filter](https://github.com/brenes/stopwords-filter) - a very simple and naive implementation of a stopwords filter that remove a list of banned words (stopwords) from a sentence

## Summarization

Automatic summarization is the process of reducing a text document with a computer program in order to create a summary that retains the most important points of the original document.

* [ots](https://github.com/deepfryed/ots) - Ruby bindings to open text summarizer
* [summarize](https://github.com/ssoper/summarize) - Ruby C wrapper for Open Text Summarizer

## Text Extraction

* [Ruby Readability](https://github.com/cantino/ruby-readability) - a tool for extracting the primary readable content of a webpage
* [Yomu](https://github.com/Erol/yomu) - a library for extracting text and metadata from files and documents using the Apache Tika content analysis toolkit

## Text Similarity

* [FuzzyMatch](https://github.com/seamusabshere/fuzzy_match) - find a needle in a haystack based on string similarity and regular expression rules
* [fuzzy-string-match](https://github.com/kiyoka/fuzzy-string-match) - fuzzy string matching library for ruby
* [Going the Distance](https://github.com/schneems/going_the_distance) - contains scripts that do various distance calculations
* [hotwater](https://github.com/colinsurprenant/hotwater) - Fast Ruby FFI string edit distance algorithms
* [levenshtein-ffi](https://github.com/dbalatero/levenshtein-ffi) - fast string edit distance computation, using the Damerau-Levenshtein algorithm
* [tf-idf-similarity](https://github.com/jpmckinney/tf-idf-similarity) - calculate the similarity between texts using tf*idf

## Tokenizers

* [Jieba](https://github.com/mimosa/jieba-jruby) - Chinese tokenizer and segmenter (jRuby)
* [MeCab](https://github.com/markburns/mecab) - Japanese morphological analyzer [[MeCab Heroku buildpack](https://github.com/diasks2/heroku-buildpack-mecab)]
* [NLP Pure](https://github.com/parhamr/nlp-pure) - natural language processing algorithms implemented in pure Ruby with minimal dependencies
* [rseg](https://github.com/yzhang/rseg) - a Chinese Word Segmentation (中文分词) routine in pure Ruby
* [thailang4r](https://github.com/veer66/thailang4r) - Thai tokenizer
* [tiny_segmenter](https://github.com/6/tiny_segmenter) - Ruby port of TinySegmenter.js for tokenizing Japanese text
* [tokenizer](https://github.com/arbox/tokenizer) - a simple multilingual tokenizer 

## Word Count

* [wc](https://github.com/thesp0nge/wc) - a rubygem to count word occurrences in a given text
* [word_count](https://github.com/AtelierConvivialite/word_count) - a word counter for String and Hash in Ruby
* [Word Count Analyzer](https://github.com/diasks2/word_count_analyzer) - analyzes a string for potential areas of the text that might cause word count discrepancies depending on the tool used
* [WordsCounted](https://github.com/abitdodgy/words_counted) - a highly customisable Ruby text analyser
