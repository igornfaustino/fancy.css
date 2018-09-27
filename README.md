# Fancy.css

Just a simple library to make easier to build fancy web stuffs

## How to help develop

This library is written on SASS, the easiest way to setup everything is using docker.

To start the compiler just type:

```bash
$ docker-compose up
```

Now you are ready to go. Just type your scss code inside the `scss` folder, and everything will be compiled into the fancy.css file.

### folder structure

This project uses the follow struct

```bash
root/
   - src/
       - fancy.css # main compiled file
       - scss/
            - fancy.scss # main scss file (import everything here)
            - base/
```

### css structure

We will use the `BEM` ideal to make all the css class. For more information just follow [this](http://getbem.com/introduction/)
