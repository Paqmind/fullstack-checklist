# CycleJS Ultimate

Ultimate CycleJS demo. Experimental fork of [React-Ultimate](https://github.com/Paqmind/react-ultimate).
This project aims to approach all common web app tasks. Wish me good luck ;)

Tech Stack:

- CycleJS, RxJS
- ES6, Babel
- ExpressJS
- SocketIO (undecided)
- your-validation-library (undecided)

Draft feature enumeration:

- [ ] Architecture
  - [ ] Folder structure
  - [ ] Absolute imports
  - [ ] Purely functional code ([Ramda](http://ramdajs.com))
  - [ ] Component approach
  - [ ] Frontend dataflow
  - [ ] Backend REST API
  - [ ] Frontend REST API
  - [ ] I18n, L10n
  - [ ] Validation
    - [ ] Validation rules sharing
  - [ ] Multiple environments / configuration management
  - [ ] Multiple frontend entry points
  - [ ] Frontend routing
  - [ ] Define frontend variables from backend / bundler
  - [ ] CORS support
  - [ ] GZIP support
  - [ ] DB pooling
  - [ ] AJAX
    - [ ] Request queue
    - [ ] Bad connection handling / retries
    - [ ] Progress indication
  - [ ] Notifications
  - [ ] Forms
    - [ ] Error messages
    - [ ] Debounce
    - [ ] Double submit prevention
  - [ ] Promises
  - [ ] URL bound and URL unbound pages
  - [ ] CRUD
    - [ ] Create
    - [ ] Detail
    - [ ] Edit
    - [ ] Remove
    - [ ] Inline edit
    - [ ] Drag & Drop example
  - [ ] Index
    - [ ] Filters
    - [ ] Sorts
    - [ ] Perpage
    - [ ] Pagination
    - [ ] Frontend-only filtering, sorting, perpage (whenever possible)
    - [ ] Example of infinite scroll
    - [ ] Example of masonry
  - [ ] Isomorphic app
  - [ ] Frontend DB (query language)
  - [ ] Optimistic updates
  - [ ] CSRF protection

- [ ] Bundling
  - [ ] Webpack
  - [ ] Bundle minification (prod)
  - [ ] Bundle uglification (prod)
  - [ ] Bundle vendor splitting (dev)
  - [ ] Source Maps (dev)
  - [ ] Auto inline assets (prod)
  - [ ] Cache management
  - [ ] Skip already minified files
  - [ ] Assets deduplication

- [ ] Development
  - [ ] Backend server auto-reload
  - [ ] Frontend live reload (dev)
  - [ ] Frontend hot reLoad (dev)

- [ ] Code Quality
  - [ ] Linting
  - [ ] Unit tests
  - [ ] Functional tests

- [ ] Undecided
  - [ ] CSS modules vs Local styles
  - [ ] Real time (suspend for now)

## Install

```
$ wget https://github.com/Paqmind/cycle-ultimate/archive/master.zip; unzip master.zip -d cycle-ultimate; rm master.zip
$ cd cycle-starter
$ npm install; bin/install
```

## Run

Production
```
$ npm run build [terminal #1]
$ npm run node  [terminal #2]
```

Development
```
$ npm run dev     [terminal #1]
$ npm run nodemon [terminal #2]
```

## Lint

```
$ npm run lint -s (mute node output)
```

## Test

All tests
```
$ npm test -s
```

Specific tests (`--` is an NPM syntax to pass arguments)
```
$ npm test -- --grep "api/robots POST" -s
```

Refer to [Mocha](https://github.com/mochajs/mocha) and [Chai](https://github.com/chaijs/chai)
for more details.
