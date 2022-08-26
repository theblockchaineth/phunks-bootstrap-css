# phunks-bootstrap-css

Basic Phunky Themes using Bootstrap 5 Standards
Used on phunkspotlight.xyz

Import order is important, bootstrap then custom.
Any overrides or custom features in custom.css please.
Then, any additional CSS after that.


Ensure your index.html contains the following

<code>


<head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
</head>


<body>    
    < Any of your content >
    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p"
      crossorigin="anonymous"
    ></script>
</body>


</code>


Example Usage in JS:

import './theme/bootstrap.css';
import './theme/custom.css';