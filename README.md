# OpenAnnotation

Contains vocabularies to be used by RDF ruby gem https://github.com/ruby-rdf/rdf/ to simplify coding when using OpenAnnotation data.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'rdf-open_annotation'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install rdf-open_annotation

## Usage

# @example Using these RDF vocabularies
# include RDF
# include rdf-open_annotation
#
# RDF::OpenAnnotation.Annotation #=> RDF::URI("http://www.w3.org/ns/oa#Annotation")
# RDF::OpenAnnotation.hasBody #=> RDF::URI("http://www.w3.org/ns/oa#hasBody")
# RDF::Content.chars #=> RDF::URI("http://www.w3.org/2011/content#chars")

## Contributing

1. Fork it ( https://github.com/[my-github-username]/open_annotation/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
