# Barba.js 101
Working files for Barba.js 101 - Free Online Course by [Petr Tichy](https://ihatetomatoes.net/), [@ihatetomatoes](https://twitter.com/ihatetomatoes).

![Barba.js 101](/assets/img_barbajs-101.png)

## Related Links
[Barba.js 101](https://ihatetomatoes.net/get-barba-101)


Previous transition for home.

      {
        //setting transition name to home.
        name: 'home',
          // creating a hook
          beforeOnce(){
            console.log('running hook beforeOnce')
          },
          // this is a hook that's called once. It happens once on the page load.
          once(){
            // with css plugin, this won't work.
            console.log('running hook once')
          },
          // another hook
          afterOnce(){
            console.log('running hook afterOnce')
          },
      }, # barba-js-gsap
