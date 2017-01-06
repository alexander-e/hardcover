# Hardcover

_Hardcover_ is a theme for [Hugo](http://gohugo.io).

It is a combination of the [Paperback](https://github.com/damiencaselli/paperback) and [Academic](https://github.com/gcushen/hugo-academic) Hugo themes built to suit my needs.
It has the same reading experience with high contrast colors as the Paperback theme, while incorporating the features of the Academic theme that are relevant to someone in academia.

## Installation

Instructions on how to install a theme can be found in the [Hugo documentation](http://gohugo.io/themes/installing/).

## Configuration

A few parameters can be adjusted in the site config:

```toml
[Params]
Author = "Author Name"

# Social accounts
#  Set to true if you want to add social links
SocialLinks = true
#  Give the relevant account names
Github = "auth"
ORCiD = "0000-0000-0000-0000"
ResearchGate = "Author_Name"
LinkedIn = "author_name"
GoogleScholar = ""

# Enable the Arvo font?
fancyfont = "true"

# Navigation Links
#   To link a homepage widget, specify the URL as a hash `#` followed by the filename of the
#     desired widget in your `content/home/` folder.
#   The weight parameter defines the order that the links will appear in.

```

## Publication list

Next to an __about me__ section, a __blog__ section and a __contact__ section, there is also a __scientific output__ section.
In this section, a (chronological) list of your _scientific output_ is generated.
Currently, four types of scientific outputs are supported by four content types:
1. journal articles (journal),
2. articles in conference proceedings (proceeding),
3. posters and presentations (talk) and
4. work in progress (wip).