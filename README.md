# Learning Vue.js

Notes and code written while working my way through the [Vue Js 2, the Complete Guide Udemy Cource](https://www.udemy.com/vuejs-2-the-complete-guide).

## Resources

* [Official Vue.js Guide](https://vuejs.org/v2/guide/)

## Notes

### Directives

* v-on:\<event\>="\<method\>"
* v-bind:\<attribute\>="\<data/method\>"
* v-model="\<data\>"
* v-html="\<data/method\>
* v-once

### Methods

Methods can be created in a few different ways when creating a new Vue object.

    methods: {
        increase: function() {
          // Example call from HTML: v-on:click="increase"
        },
        increase: function(event) {
          // Example call from HTML: v-on:click="increase"
        },
        increase: function(step, event) {
          // Example call from HTML: v-on:click="increase(2, $event)"
        },
        // All of the above variants can also be written without the function keyword:
        increase() {
          // Example call from HTML: v-on:click="increase"
        }
    }
