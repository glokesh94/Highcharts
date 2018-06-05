Highcharts JS is a JavaScript charting library based on SVG, with fallbacks to VML and canvas for old browsers.

Official website: www.highcharts.com
Download page: www.highcharts.com/download
Licensing: www.highcharts.com/license
Support: www.highcharts.com/support
Issues: Repo guidelines

Download and install Highcharts
This is the working repo for Highcharts. If you simply want to include Highcharts into a project, use the distribution package instead, or read the download page. Please note that there are several ways to use Highcharts. For general installation instructions, see the docs.

Use our CDN
Instead of downloading, you can use our CDN to access files directly. See code.highcharts.com for details.

<script src="https://code.highcharts.com/highcharts.js"></script>

Generate API docs
Clone the repositories api-docs and highcharts-docstrap in the same parent folder as this highcharts repository. Do not forgett to install depending modules in this repositories by npm i. Finally you can run in this highcharts repository the doc generator with gulp jsdoc --watch, which also starts a new server with the generated API documentation.
