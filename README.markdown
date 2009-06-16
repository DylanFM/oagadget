# Open Australia Gmail gadget

This is a little Gmail gadget for Open Australia. For now, once you've set your postcode, the gadget will get the most recent debates for your representative.

*This has been developed using Safari 4 and hasn't been tested in any other browsers yet.*

## Requirements

To use this gadget you must be using Gmail. It wouldn't be hard to move this to another Open Social container, like iGoogle for example, but for now this is just for Gmail.

## Installation

These are taken from the [Open Social page for the Gmail container](http://wiki.opensocial.org/index.php?title=Gmail).

> 1. Go to the 'Labs' tab under Gmail Settings.
> 2. Enable the 'Add any gadget by URL' experiment and click 'Save Changes.'
> 3. Now you'll have a 'Gadgets' tab under Settings.
> 4. Enter the URL of an OpenSocial gadget spec and click 'Add'.

### Not&ndash;so&ndash;edge version

For a more stable version of the gadget, use this spec: [http://dylanfm.github.com/oagadget/spec.xml](http://dylanfm.github.com/oagadget/spec.xml).

### Edge version

A more unstable version of this gadget's spec is the most recent version of the file "spec.xml" above. To get a URL which can be used for the gadget installation:

1. Click "spec.xml" above.
2. Towards the right at the top of the spec's contents there should be a link to "raw".
3. Copy the "raw" link's target and use that as the URL to the spec.

This is handy for development. Gmail caches the specs for 1 hour. The URL for the edge spec changes whenever changes are made, so the caching isn't an issue and development is swifter than it could be. You can also use any version of the gadget you want this way too.
