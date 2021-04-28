<!-- Loads <model-viewer> for old browsers like IE11: -->
<script nomodule="" src="https://unpkg.com/@google/model-viewer/dist/model-viewer-legacy.js">
  </script>

  <!-- The following libraries and polyfills are recommended to maximize browser support -->  
  <!-- REQUIRED: Web Components polyfill to support Edge and Firefox < 63 -->
  <script src="https://unpkg.com/@webcomponents/webcomponentsjs/webcomponents-loader.js"></script>

  <!-- OPTIONAL: Intersection Observer polyfill for better performance in Safari and IE11 -->
  <script src="https://unpkg.com/intersection-observer/intersection-observer.js"></script>

  <!-- OPTIONAL: Resize Observer polyfill improves resize behavior in non-Chrome browsers -->
  <script src="https://unpkg.com/resize-observer-polyfill/dist/ResizeObserver.js"></script>

  <!-- OPTIONAL: Fullscreen polyfill is required for experimental AR features in Canary -->
  <!--<script src="https://unpkg.com/fullscreen-polyfill/dist/fullscreen.polyfill.js"></script>-->

  <!-- OPTIONAL: Include prismatic.js for Magic Leap support -->
  <!--<script src="https://unpkg.com/@magicleap/prismatic/prismatic.min.js"></script>-->

<script>
  <h3 style="text-align: center;" markdown="1"><b>EXPERIENCE:</b> 3D & 4D on Mobile Device
  <br><br> 
  <h3 style="text-align: center;" markdown="1"><b>EDUCATION:</b><a href="https://helloagainproducts.com/faq/?utm_source=FAQ&utm_medium=marketing&utm_campaign=XR-NOW&utm_content=point%20of%20purchase" onclick="getOutboundLink('https://helloagainproducts.com/faq/?utm_source=FAQ&utm_medium=marketing&utm_campaign=XR-NOW&utm_content=point%20of%20purchase'); return false;"</b><b> FAQs</b></a> 
  <br><br>
  <h3 style="text-align: center;" markdown="1"><b>ENLIGHTENMENT:</b><a href="https://helloagainproducts.com/wp-content/uploads/2021/03/HELLO-AGAIN-LAUNCH.mp4?utm_source=Why%20Us&utm_medium=Video&utm_campaign=XR-NOW&utm_content=PoP" onclick="getOutboundLink('https://helloagainproducts.com/wp-content/uploads/2021/03/HELLO-AGAIN-LAUNCH.mp4?utm_source=Why%20Us&utm_medium=Video&utm_campaign=XR-NOW&utm_content=PoP'); return false;"</b> <b> WHY</a> 
  <br><br>
  <h3 style="text-align: center;" markdown="1"><b>ENGAGE:</b><a href="https://helloagainproducts.com/locations/?utm_source=Where%20to%20Buy&utm_medium=marketing&utm_campaign=XR-NOW&utm_content=PoP" onclick="getOutboundLink('https://helloagainproducts.com/locations/?utm_source=Where%20to%20Buy&utm_medium=marketing&utm_campaign=XR-NOW&utm_content=PoP'); return false;"</b><b> WHERE</b></a> 
  <br><br>
/**
* Function that registers a click on an outbound link in Analytics.
* This function takes a valid URL string as an argument, and uses that URL string
* as the event label. Setting the transport method to 'beacon' lets the hit be sent
* using 'navigator.sendBeacon' in browser that support it.
*/
var getOutboundLink = function(url) {
  gtag('event', 'click', {
    'event_category': 'outbound',
    'event_label': url,
    'transport_type': 'beacon',
    'event_callback': function(){document.location = url;}
  });
}
</script>


<!-- Loads <model-viewer> for modern browsers: -->
 <script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.js">
  </script>
<script nomodule="" src="https://unpkg.com/@google/model-viewer/dist/model-viewer-legacy.js"></script>
<script src="{{ "/assets/js/scale.fix.js" | relative_url }}"></script>

<!-- Loads <model-viewer> for modern browsers: -->
 <script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.js">
  </script>
<script nomodule="" src="https://unpkg.com/@google/model-viewer/dist/model-viewer-legacy.js"></script>

