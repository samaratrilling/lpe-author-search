# LPE Author Search

I'm applying to law school. I needed to quickly get the school affiliations of professors who've written articles
for the [Law & Political Economy Project's blog](https://lpeproject.org/), which pulls together anti-monopoly,
regulated industries, labor rights, and tech law.

# To run 
Edit keywords file to contain the list of schools you're looking for (or other keywords). This list is pretty snobby.
Edit urls file to contain all URLs you want to search (this bit could be made more DRY but I couldn't be bothered)
Run
```
./lpe-search.sh
```
Output will look like:
https://lpeproject.org/authors/page/1/: Yale
https://lpeproject.org/authors/page/1/: Yale
https://lpeproject.org/authors/page/1/: Harvard
https://lpeproject.org/authors/page/2/: Yale
https://lpeproject.org/authors/page/2/: Stanford
https://lpeproject.org/authors/page/2/: Michigan
https://lpeproject.org/authors/page/2/: Michigan
https://lpeproject.org/authors/page/2/: Yale
https://lpeproject.org/authors/page/3/: Harvard
https://lpeproject.org/authors/page/3/: Yale
https://lpeproject.org/authors/page/3/: Yale
