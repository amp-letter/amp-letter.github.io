# AMP Letter

## Signing the letter as an individual

The letter uses Jekyll to combine and sort signatures.  Please [create a file](https://github.com/amp-letter/amp-letter.github.io/new/master/_data/supporting) called your-name.yml in `/_data/supporting`, using the following template:

```
sortName: {Your family name (just for sorting, not displayed)}
displayName: {How your full name should be displayed}
url: {URL of your website, profile or AMP-related statement}
```

For example:

```
sortName: Stevenson
displayName: Alice Stevenson
url: https://example.com/amp-letter
```

You'll be inserted into the list in order of `sortName`.

### What URL should I use?

The best thing to do is to post a statement of your reasons for signing the letter, with a link to ampletter.org, and then link to that statement in your signature.  This will help us to verify that you are a legitimate owner of that URL.

Otherwise, link to a personal website, professional profile or social media profile.  If signing as an individual, please don't link to a business.

## Signing as an organisation

To sign as an organisation, please ensure you are a legal representative of the organisation, and the organisation is a legal entity in its own right.  If you are signing as a corporation, please link to a post explaining your AMP stance (this avoids businesses using the letter as advertising).  Create a file in `/_data/orgs`, with the keys `name`, `representativeName` and `url`.

## Translations

If you want to translate the letter, please find a few independent native speakers to review your translation.  It's likely that none of the maintainers of the letter understand the language in question so we'll need a reasonably large group of native speakers to confirm it's an accurate translation.
