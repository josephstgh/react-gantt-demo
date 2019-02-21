Gantt chart for React.JS
===================

This is a react gantt chart demo app that is made with the help of dhtmlxGantt. The demo includes implementation of time scale zooming and processing of changes that users can make in gantt chart. 

More features can be added due to rich functionality of dhtmlxGantt: https://dhtmlx.com/docs/products/dhtmlxGantt/#product-features

### How to start

 - clone the repository or download files
 - install dependencies
~~~ 
npm install 
~~~

 - run server
~~~
npm start
~~~

### Issue

After start-up, click on `Show` button which should hide the chart which works correctly.
However, if click on 'Show` button again, it does not show the chart even though it is supposed to be.

I have added new state `display` in `App.js` to maintain the state and pass down to `Gantt.js` as props.


###  Related resources

- Read full tutorial here: https://dhtmlx.com/blog/create-react-gantt-chart-component-dhtmlxgantt/
- Learn about dhtmlxGantt here: https://dhtmlx.com/docs/products/dhtmlxGantt/
- Learn about React here: https://facebook.github.io/react/