# phunks-bootstrap-css

Basic Phunky Themes using Bootstrap 5 Standards<br>
Used on phunkspotlight.xyz

**Import order is important, bootstrap then custom.**
Any overrides or custom features in custom.css please.<br>
Then, any additional CSS after that.


Ensure your index.html contains the following: <br>
<i>(Due to Markdown issues, please delete [remove me] from the start of the below tags)</i>

**Within HEAD:**
<code>
   <[remove me]link rel="preconnect" href="https://fonts.googleapis.com"> <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
</code>


**Within BODY:**
<code>
   <[remove me]script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
   </code>

**Example Usage in JS:**

import './theme/bootstrap.css'; <br>
import './theme/custom.css';
