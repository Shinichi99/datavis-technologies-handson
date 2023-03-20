The circumference of a sphere with radius {radius}m is {computeCircumference(radius)}m.
  
  <script>
    const radius = 2.5;
  
    function computeCircumference(radius) {
      const circumference = 2 * Math.PI * radius;
      return circumference.toFixed(2);
    }
  </script>