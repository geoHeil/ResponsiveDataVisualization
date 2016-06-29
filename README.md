# Responsive Data visualization

Tracking my progress through [Learning Responsive Data Visualization](https://www.amazon.com/Learning-Responsive-Visualization-Christoph-Korner/dp/178588378X/ref=sr_1_1_twi_pap_1?ie=UTF8&qid=1466692325&sr=8-1&keywords=Learning+Responsive+Data+Visualization) 
Based on [Angular 2 starter kit](https://github.com/AngularClass/angular2-webpack-starter)

### Quick start
**Make sure you have Node version >= 5.0 and NPM >= 3**

```bash
# clone my repo
# --depth 1 removes all but one .git commit history
git clone --depth 1 https://github.com/geoHeil/ResponsiveDataVisualization.git

# change directory to our repo
cd ResponsiveDataVisualization

# install the repo with npm
npm install

# start the server
npm start

# use Hot Module Replacement
npm run server:dev:hmr
```
go to [http://0.0.0.0:3000](http://0.0.0.0:3000) or [http://localhost:3000](http://localhost:3000) in your browser

# Problems

  - During my initial steps I try to get everything working together following https://github.com/theAlgorithmist/D3BarChart 
  - However, the bar chart cannot be loaded due to: `TypeError: Cannot read property 'style' of null`
  - As you can see from the log statement the graph is not null, but does not have a 'style' property
  - How to render [http://stackoverflow.duapp.com/questions/35633335/how-to-make-third-party-libraries-play-nice-with-angular-2s-renderer](http://stackoverflow.duapp.com/questions/35633335/how-to-make-third-party-libraries-play-nice-with-angular-2s-renderer)
  and this [https://github.com/angular/angular/issues/4973](https://github.com/angular/angular/issues/4973)