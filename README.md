# Suggested Practices


## JavaScript
1. **Don't repeat yourself.**
2. **Keep it simple, _"ese"_.**
3. **High cohesion, loose coupling.**
   * Build reusable components.
4. Clarity over elegance (and quickness).
5. Explicit is better than implicit.
6. Keep your code clean, indented, readable and self-documented.
7. Standardize along with your team your project files ([LIFT](https://github.com/johnpapa/angular-styleguide#lift)).
   * _e.g._: variable declaration comes first then function implementations, functions are sorted in alphabetical order in each file, add TODO and FIXME tags (via comments) where needed (FIXME has higher priority than TODO).
8. Use auto-descriptive names for your variables and functions.
9. Learn to use your tools.
10. If using a library or framework, apply the best practices on each use of it.
11. Avoid DOM manipulation from JS (_I’m talking to you, jquery!_).
12. Write your tests at the same time as you write the code.
   * _“You are responsible for everything you write”._
13. [Document your code](http://usejsdoc.org/).
14. **[Constantly check what experts have to say](https://github.com/bolshchikov/js-must-watch)**.
15. Become yourself an expert by doing!


## AngularJS
1. Apply [best practices](https://github.com/angular/angular.js/wiki/Best-Practices) on each use of the framework and avoid [common mistakes](https://www.airpair.com/angularjs/posts/top-10-mistakes-angularjs-developers-make) and [anti-patterns](https://github.com/angular/angular.js/wiki/Anti-Patterns).
2. Select or create with your team style guidelines and apply them [[1](https://github.com/johnpapa/angular-styleguide), [2](https://github.com/toddmotto/angularjs-styleguide)].
3. At function definition (controller, directive, filter, service) put first framework services and then custom ones (the `$`* comes first) and sort them all alphabetically.
4. Develop with performance in mind:
   * Avoid the use of `$scope.$watch` as much as possible.
   * Use `$timeout` wisely.
   * Use [one-time binding](https://docs.angularjs.org/guide/expression) as much as you can (`::`).
5. Discover your tools and learn to use its hidden power:
   * `$q` and [promises in general](http://www.dwmkerr.com/promises-in-angularjs-the-definitive-guide/).
   * `$http` / `$resource`
   * `ui.router`
6. Favor `$log.debug` over `console.log`.
