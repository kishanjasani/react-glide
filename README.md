# react-glide

## Installation

```sh
$ npm install react-glide
```

## Usage

```javascript
import Glide from 'react-glide';
```

```javascript
const images = [
  'http://path/to/image/url',
  'http://path/to/image/url2',
  'http://path/to/image/url3'
];

<Glide
  images={images}
  width={500}
  autoPlay={true}
  autoPlaySpeed={1000}
  infinite={true}
/>
```

## Options

| option      | type      | description                           |
|------------ |-----------|---------------------------------------|
|`images`     |array      | the images to be displayed by component |
|`width`      |integer    | the width of the carousel container     |
|`autoPlay`   |bool       | enables or disables autoPlay feature     |
|`autoPlaySpeed` |integer    | the rate of change between slides, defined in ms   |
|`infinite` |bool    | carousel will loop infinitely   |


## Development

Install dependencies:

```sh
$ npm install
```

Run the example app at http://localhost:3000:

```sh
$ npm start
```

Run tests:

```sh
$ npm test
```

## License
?
