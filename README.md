# fake-image snippets for Atom

[![apm](https://img.shields.io/apm/dm/fake-image-snippets.svg?style=flat-square)](https://atom.io/packages/fake-image-snippets)

This is snippets for set `<img>` placeholder with [fakeimg](https://fakeimg.pl/) quickly.

## Install

Search `fake-image-snippets` on package manager or `apm install fake-image-snippets`

## Usage

![FakeImg Usage](./fakeimg.gif)

## Documentation

There support two snippets now:
- `fakeImg`: Add normal fakeimg.pl link on placeholder, ex: `<img src="http://fakeimg.pl/350x200/bdd9d2/3f232a/?text=Fake-Image">`
- `fakeImgS`: Add square image by default, ex: `<img src="http://fakeimg.pl/350x350/bdd9d2/3f232a/?text=Fake-Image">`
- `sfakeImgS`: Just add url, ex: `http://fakeimg.pl/200x200/000000,128/000`

This snippet tabs through some options (default):

- horizontal size 350
- vertical size 200
- background color bdd9d2
- text color 3f232a
- sample text Fake-Imag

following are other options you can set:

- `font=lobster`
- `font_size=14`
- `retina=1`

More detail you can see [fakeimg](https://fakeimg.pl/)

## Example

`<img src="http://fakeimg.pl/350x200/bdd9d2/3f232a/?text=Fake-Image">`

![Example image](http://fakeimg.pl/350x200/bdd9d2/3f232a/?text=Fake-Image)

## Contributing

- Fork it!
- Create your feature branch: `git checkout -b my-new-feature`
- Commit your changes: `git commit -m 'Add some feature'`
- Push to the branch: `git push origin my-new-feature`
- Submit a pull request
