<script>
    let x=1;
    function circumference(r) {
        return (2 * r * Math.PI).toFixed(2);
    }
</script>

<input type=number, bind:value={x}>
<p>The circumference of a circle with radius {x}m is {circumference(x)}m</p>