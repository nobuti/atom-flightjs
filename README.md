# FlightJS Snippets for [Atom](http://atom.io)
![atom-flighjs](https://cloud.githubusercontent.com/assets/1366843/11929963/aad9c4a2-a7df-11e5-8da5-bf588d6ba620.gif)

## Install

Go to `Atom > Preferences...` then search for **FlightJS Snippets** in Packages tab.

## Development

```sh
$ cd ~/.atom/packages
$ git clone https://github.com/nobuti/atom-flightjs.git
$ cd atom-flightjs
$ apm install
$ apm link
```

## Usage

Tab triggers exist for all of the snippets, usually you should start typping `flight`.

- Component and Mixin API (tab trigger: flight)
  - Component (AMD)
  - Component (CommonJS)
  - Component (Standalone)
  - Mixin (AMD)
  - Mixin (CommonJS)
  - Mixin (Standalone)

- Test API
  - describeComponent
  - describeMixin

- Component API
  - attachTo

- Advice API
  - this.before
  - this.after
  - this.around

- Base API
  - this.attributes
  - this.select
  - this.on
  - this.off
  - this.trigger


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

Check [Release](https://github.com/nobuti/atom-flightjs/releases) list.

## License

[MIT License](https://opensource.org/licenses/MIT) © Buti
