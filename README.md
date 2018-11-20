
## Full Documentation

[npm package](https://www.npmjs.com/package/vertical-timeline-component-for-react)

[![Vertical-Timeline-Component-React.gif](https://i.postimg.cc/3wZYZ0Kq/Vertical-Timeline-Component-React.gif)](https://postimg.cc/1g4kmtV0)

## Install

```code
$ npm i vertical-timeline-component-for-react
```


## Usage

```code|lang-jsx
---
import { Timeline, TimelineItem }  from 'vertical-timeline-component-for-react';

...

<Timeline lineColor={'#ddd'}>
  <TimelineItem
    key={'001'}
    date="11/2010 – Present"
    className="custom--class"
    style={{color: '#e86971'}}
  >
    <h3>Title, Company</h3>
    <h4>Subtitle</h4>
    <p>Est incididunt sint eu minim dolore mollit velit velit commodo ex nulla exercitation. Veniam velit adipisicing anim excepteur nostrud magna nostrud aliqua dolor. Sunt aute est duis ut nulla officia irure reprehenderit laborum fugiat dolore in elit. Adipisicing do qui duis Lorem est.</p>
    <p>Est incididunt sint eu minim dolore mollit velit velit commodo ex nulla exercitation. Veniam velit adipisicing anim excepteur nostrud magna nostrud aliqua dolor. Sunt aute est duis ut nulla officia irure reprehenderit laborum fugiat dolore in elit. Adipisicing do qui duis Lorem est.</p>
    <p>Est incididunt sint eu minim dolore mollit velit velit commodo ex nulla exercitation. Veniam velit adipisicing anim excepteur nostrud magna nostrud aliqua dolor. Sunt aute est duis ut nulla officia irure reprehenderit laborum fugiat dolore in elit. Adipisicing do qui duis Lorem est.</p>
  </TimelineItem>
  <TimelineItem
    key={'002'}
    date="04/2009 – 11/2010"
    className="custom--class"
    dateInnerStyle={{background: '#61b8ff', color: '#000'}}
    bodyContainerStyle={{background: '#ddd', padding: '20px', borderRadius: '8px', boxShadow: '0.5rem 0.5rem 2rem 0 rgba(0, 0, 0, 0.2)' }}
  >
    <h3 style={{color: '#61b8ff'}}>Title, Company</h3>
    <h4 style={{color: '#61b8ff'}}>Subtitle</h4>
    <p>Est incididunt sint eu minim dolore mollit velit velit commodo ex nulla exercitation. Veniam velit adipisicing anim excepteur nostrud magna nostrud aliqua dolor. Sunt aute est duis ut nulla officia irure reprehenderit laborum fugiat dolore in elit. Adipisicing do qui duis Lorem est.</p>
    <p>Est incididunt sint eu minim dolore mollit velit velit commodo ex nulla exercitation. Veniam velit adipisicing anim excepteur nostrud magna nostrud aliqua dolor. Sunt aute est duis ut nulla officia irure reprehenderit laborum fugiat dolore in elit. Adipisicing do qui duis Lorem est.</p>
  </TimelineItem>
  <TimelineItem
    key={'003'}
    date="11/2008 – 04/2009"
    className="custom--class"
    dateInnerStyle={{background: '#f7d286'}}
  >
    <h3>Title, Company</h3>
    <h4>Subtitle</h4>
    <p>Est incididunt sint eu minim dolore mollit velit velit commodo ex nulla exercitation. Veniam velit adipisicing anim excepteur nostrud magna nostrud aliqua dolor. Sunt aute est duis ut nulla officia irure reprehenderit laborum fugiat dolore in elit. Adipisicing do qui duis Lorem est.</p>
    <p>Est incididunt sint eu minim dolore mollit velit velit commodo ex nulla exercitation. Veniam velit adipisicing anim excepteur nostrud magna nostrud aliqua dolor. Sunt aute est duis ut nulla officia irure reprehenderit laborum fugiat dolore in elit. Adipisicing do qui duis Lorem est.</p>
    <p>Est incididunt sint eu minim dolore mollit velit velit commodo ex nulla exercitation. Veniam velit adipisicing anim excepteur nostrud magna nostrud aliqua dolor. Sunt aute est duis ut nulla officia irure reprehenderit laborum fugiat dolore in elit. Adipisicing do qui duis Lorem est.</p>
  </TimelineItem>
  <TimelineItem
    key={'004'}
    date="08/2008 – 11/2008"
    className="custom--class"
    dateInnerStyle={{background: '#76bb7f'}}
  >
    <h3>Title, Company</h3>
    <h4>Subtitle</h4>
    <p>Est incididunt sint eu minim dolore mollit velit velit commodo ex nulla exercitation. Veniam velit adipisicing anim excepteur nostrud magna nostrud aliqua dolor. Sunt aute est duis ut nulla officia irure reprehenderit laborum fugiat dolore in elit. Adipisicing do qui duis Lorem est.</p>
    <p>Est incididunt sint eu minim dolore mollit velit velit commodo ex nulla exercitation. Veniam velit adipisicing anim excepteur nostrud magna nostrud aliqua dolor. Sunt aute est duis ut nulla officia irure reprehenderit laborum fugiat dolore in elit. Adipisicing do qui duis Lorem est.</p>
  </TimelineItem>
</Timeline>
```


## Timeline Props

### `animate={ Boolean }`

Enable or disable animations on elements (default: true).

### `className={ String }`

Add extra class name to root div element.

### `lineColor={ String }`

Choose your timeline color (default: `'#000'`).

## TimelineItem Props

### `className={ String }`

Add extra class name to root div element.

### `style={ Object }`

Add extra style to root div element.
You can change color of timeline points by adding color to style prop.

### `date={ String }`

Date of the element.

### `dateStyle={ Object }`

Add extra style to `'timeline-item-date'` span element.

### `dateInnerStyle={ Object }`

Add extra style to `'timeline-item-dateinner'` time element.

### `bodyContainerStyle={ Object }`

Add extra style to `'body-container'` div element.

### `visibilitySensorProps={ Object }`

Custom props pass to VisibilitySensor component (default: { partialVisibility: true, offset: { bottom: 50 } }).
*See [react-visibility-sensor](https://github.com/joshwnj/react-visibility-sensor) for more information.*


## Showcase

* [(Veysi YILDIZ)](https://www.linkedin.com/in/veysiyildiz/).

## TODO 
add tests

## License

*vertical-timeline-component-for-react* is available under MIT. See LICENSE for more details.