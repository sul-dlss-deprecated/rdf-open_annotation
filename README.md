# DEPRECATED

This gem is deprecated;  rdf-vocab gem (https://github.com/ruby-rdf/rdf-vocab, included in the linkeddata gem) now contains RDF::Vocab::OA, RDF::Vocab::DCMIType and RDF::Vocab::CNT.

# rdf-open_annotation

[![Dependency Status](https://gemnasium.com/sul-dlss/rdf-open_annotation.svg)](https://gemnasium.com/sul-dlss/rdf-open_annotation) [![Gem Version](https://badge.fury.io/rb/rdf-open_annotation.svg)](http://badge.fury.io/rb/rdf-open_annotation)

Contains vocabularies to be used by RDF ruby gem https://github.com/ruby-rdf/rdf/ to simplify coding when using OpenAnnotation data.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'rdf-vocab'  # (was rdf-open_annotation)
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install rdf-vocab  # (was rdf-open_annotation)

## Usage

    require 'rdf/vocab'

    RDF::Vocab::OA.Annotation #=> RDF::URI("http://www.w3.org/ns/oa#Annotation")
    RDF::Vocab::OA.hasBody #=> RDF::URI("http://www.w3.org/ns/oa#hasBody")
    RDF::Vocab::CNT.chars #=> RDF::URI("http://www.w3.org/2011/content#chars")
    RDF::Vocab::DCMIType.Text #=> RDF::URI("http://purl.org/dc/dcmitype/Text")

# DEPRECATED

This gem is deprecated;  rdf-vocab gem (https://github.com/ruby-rdf/rdf-vocab, included in the linkeddata gem) now contains RDF::Vocab::OA, RDF::Vocab::DCMIType and RDF::Vocab::CNT.
