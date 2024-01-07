<!--

@license Apache-2.0

Copyright (c) 2022 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->


<details>
  <summary>
    About stdlib...
  </summary>
  <p>We believe in a future in which the web is a preferred environment for numerical computation. To help realize this future, we've built stdlib. stdlib is a standard library, with an emphasis on numerical and scientific computation, written in JavaScript (and C) for execution in browsers and in Node.js.</p>
  <p>The library is fully decomposable, being architected in such a way that you can swap out and mix and match APIs and functionality to cater to your exact preferences and use cases.</p>
  <p>When you use stdlib, you can be absolutely certain that you are using the most thorough, rigorous, well-written, studied, documented, tested, measured, and high-quality code out there.</p>
  <p>To join us in bringing numerical computing to the web, get started by checking us out on <a href="https://github.com/stdlib-js/stdlib">GitHub</a>, and please consider <a href="https://opencollective.com/stdlib">financially supporting stdlib</a>. We greatly appreciate your continued support!</p>
</details>

# Tools

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Error tools.

<section class="installation">

## Installation

```bash
npm install @stdlib/error-tools
```

Alternatively,

-   To load the package in a website via a `script` tag without installation and bundlers, use the [ES Module][es-module] available on the [`esm` branch][esm-url].
-   If you are using Deno, visit the [`deno` branch][deno-url].
-   For use in Observable, or in browser/node environments, use the [Universal Module Definition (UMD)][umd] build available on the [`umd` branch][umd-url].

The [branches.md][branches-url] file summarizes the available branches and displays a diagram illustrating their relationships.

</section>

<section class="usage">

## Usage

```javascript
var tools = require( '@stdlib/error-tools' );
```

#### tools

Namespace containing error tools.

```javascript
var o = tools;
// returns {...}
```

The namespace contains the following:

<!-- <toc pattern="*"> -->

<div class="namespace-toc">

-   <span class="signature">[`database()`][@stdlib/error/tools/database]</span><span class="delimiter">: </span><span class="description">standard library error code database.</span>
-   <span class="signature">[`fmtprodmsgFactory( [options] )`][@stdlib/error/tools/fmtprodmsg-factory]</span><span class="delimiter">: </span><span class="description">return a `function` which formats an error message for production.</span>
-   <span class="signature">[`fmtprodmsg( code, ...args )`][@stdlib/error/tools/fmtprodmsg]</span><span class="delimiter">: </span><span class="description">format an error message for production.</span>
-   <span class="signature">[`id2msg( id )`][@stdlib/error/tools/id2msg]</span><span class="delimiter">: </span><span class="description">return an error message corresponding to a provided two-character error identifier.</span>
-   <span class="signature">[`id2pkg( id )`][@stdlib/error/tools/id2pkg]</span><span class="delimiter">: </span><span class="description">return the package name associated with a specified error identifier prefix.</span>
-   <span class="signature">[`msg2id( msg )`][@stdlib/error/tools/msg2id]</span><span class="delimiter">: </span><span class="description">return a two-character error identifier corresponding to a provided error message.</span>
-   <span class="signature">[`pkg2id( pkg )`][@stdlib/error/tools/pkg2id]</span><span class="delimiter">: </span><span class="description">return the error identifier prefix associated with a specified package name.</span>

</div>

<!-- </toc> -->

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- TODO: better examples -->

<!-- eslint no-undef: "error" -->

```javascript
var objectKeys = require( '@stdlib/utils-keys' );
var tools = require( '@stdlib/error-tools' );

console.log( objectKeys( tools ) );
```

</section>

<!-- /.examples -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2024. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/error-tools.svg
[npm-url]: https://npmjs.org/package/@stdlib/error-tools

[test-image]: https://github.com/stdlib-js/error-tools/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/error-tools/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/error-tools/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/error-tools?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/error-tools.svg
[dependencies-url]: https://david-dm.org/stdlib-js/error-tools/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/error-tools/tree/deno
[umd-url]: https://github.com/stdlib-js/error-tools/tree/umd
[esm-url]: https://github.com/stdlib-js/error-tools/tree/esm
[branches-url]: https://github.com/stdlib-js/error-tools/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/error-tools/main/LICENSE

<!-- <toc-links> -->

[@stdlib/error/tools/database]: https://github.com/stdlib-js/error-tools-database

[@stdlib/error/tools/fmtprodmsg-factory]: https://github.com/stdlib-js/error-tools-fmtprodmsg-factory

[@stdlib/error/tools/fmtprodmsg]: https://github.com/stdlib-js/error-tools-fmtprodmsg

[@stdlib/error/tools/id2msg]: https://github.com/stdlib-js/error-tools-id2msg

[@stdlib/error/tools/id2pkg]: https://github.com/stdlib-js/error-tools-id2pkg

[@stdlib/error/tools/msg2id]: https://github.com/stdlib-js/error-tools-msg2id

[@stdlib/error/tools/pkg2id]: https://github.com/stdlib-js/error-tools-pkg2id

<!-- </toc-links> -->

</section>

<!-- /.links -->
