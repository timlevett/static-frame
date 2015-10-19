## Static UW-Frame

This is the static part of uw-frame. We broke is out from the maven build to make is usable by other programmers, like .NET, and PHP.

## build

```sh
bower install
lessc css/angular.less css/angular.css

# If you don't have http-server installed
npm install -g http-server

http-server
```