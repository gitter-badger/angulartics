<a name="0.16.1"></a>
### 0.16.1 (2014-08-19)

#### Features
* **analytics-if** - Analytics call will only be made if the `analytic-if` condition passes. Example: `<button analytics-on analytics-if="user.isLoggedIn">` 
* Better buffering
* Support for multiple providers

<a name="v0.15.20"></a>
### v0.15.20 (2014-07-09)

#### Bug Fixes

* **kissmetrics:** changing kissmetrics plugin to use global window object ([d505801](https://github.com/luisfarzati/angulartics/commit/d50580181c5cbb752c2bcb1d8334c65452aac9a2), closes [#161](https://github.com/luisfarzati/angulartics/issues/161))

#### Features

* **bower** add all vendor scripts to bower to enable automatic dependency injections via wiredep and similar tools [7cbcef1](https://github.com/luisfarzati/angulartics/commit/0108263228fe24c294c5cd120122bb6570a090a2)
