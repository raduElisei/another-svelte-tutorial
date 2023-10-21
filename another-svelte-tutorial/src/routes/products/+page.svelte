<script>
	export let productId = 100;
</script>

<a href="/">Home</a>
<h1>Product list</h1>

<li>
	<h3><a href="/products/1">Product 1</a></h3>
	<h3><a href="/products/2">Product 2</a></h3>
	<h3><a href="/products/{productId}">Product {productId}</a></h3>
</li>
