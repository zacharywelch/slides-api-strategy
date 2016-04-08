# slides-api-strategy

Building an Effective API Strategy

Designed with [reveal.js](http://lab.hakim.se/reveal-js/#/).

#### More reading:
- [APIs: A Strategy Guide](http://shop.oreilly.com/product/0636920021223.do)

## Usage

1. Clone the slides-api-strategy repository
   ```sh
   $ git clone git@cagit.careerbuilder.com:zwelch/slides-api-strategy.git
   ```

2. Open index.html in a browser

### Full setup

Some reveal.js features, like external Markdown and speaker notes, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/)

2. Install [Grunt](http://gruntjs.com/getting-started#installing-the-cli)

4. Clone the slides-api-strategy repository
   ```sh
   $ git clone git@cagit.careerbuilder.com:zwelch/slides-api-strategy.git
   ```

5. Navigate to the slides-api-strategy folder
   ```sh
   $ cd slides-api-strategy
   ```

6. Install dependencies
   ```sh
   $ npm install
   ```

7. Serve the presentation and monitor source files for changes
   ```sh
   $ grunt serve
   ```

8. Open <http://localhost:8000> to view your presentation

   You can change the port by using `grunt serve --port 8001`.
