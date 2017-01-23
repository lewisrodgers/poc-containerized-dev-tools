## Usage
In a terminal, navigate to `app/frontend` folder where `docker-compose.yaml` exists and build the image.

```bash
$ docker-compose build
```

Start the container to kick-off the build tasks and start the test runner.

```bash
$ docker-compose up
```

Make a change to a `js` or `html` file in the `src` folder and the container will re-run it's tasks.

## Configuration
This image includes the following items and the nice thing is you didn't have to install and configure any of it.

__Frameworks__
- [Angular (1.x)](https://angularjs.org/)
    - [Angular UI Router](https://ui-router.github.io/ng1/)
- [Angular Material](https://material.angularjs.org)
- [Moment](https://momentjs.com/)

__Build management system__
- [ngBoilerplate](https://github.com/ngbp/ngbp) (customized)
    - Coffee script/lint and changelog related configuration have been omitted.
    - Karma has been configured to launch PhantomJS instead of Firefox.
- [Grunt](http://gruntjs.com/)
- [Bower](https://bower.io/)
- [Karma](http://karma-runner.github.io/1.0/index.html)
    - [Jasmine](https://jasmine.github.io/)
    - [PhantomJS](http://phantomjs.org/)
