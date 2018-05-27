# Processing

The IP policy needs to be processed to HTML using Pandoc and the pandoc-crossref filter.

The relevant code is:

````
pandoc -N --toc --toc-depth=1 --filter ~/Library/Haskell/bin/pandoc-crossref --template ip_policy_template.html -o ip_policy.html ip_policy_v1_2.md
````
