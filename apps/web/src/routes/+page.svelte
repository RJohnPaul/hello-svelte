<script>
    // JavaScript code
    // You can write your JavaScript code here
</script>

<style>
    /* CSS styles */
    body {
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        background: linear-gradient(1deg, #000000, #3333ff);
        margin: 0;
        padding: 0;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
    }

    .container {
        text-align: center;
        padding: 50px;
        border-radius: 20px;
        background: linear-gradient(135deg, #000000, #3333ff); /* Apply the same gradient */
        backdrop-filter: blur(10px);
        box-shadow: 0 0 20px rgba(0, 0, 0, 0.2);
        border: 1px solid rgba(255, 255, 255, 0.2);
    }

    h1 {
        color: #fff;
        font-size: 3em;
        margin-bottom: 20px;
        text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.4);
    }

    p {
        color: #fff;
        font-size: 1.2em;
        margin-bottom: 30px;
        text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.4);
    }

    .btn {
        padding: 15px 30px;
        margin: 0 10px;
        background: linear-gradient(135deg, #ff3399, #ff00cc);
        color: #fff;
        border: none;
        border-radius: 30px;
        font-size: 1.1em;
        cursor: pointer;
        box-shadow: 0 5px 15px rgba(255, 51, 153, 0.4);
        transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .btn:hover {
        transform: translateY(-3px);
        box-shadow: 0 8px 20px rgba(255, 51, 153, 0.6);
    }

    .btn:active {
        transform: translateY(0);
        box-shadow: 0 3px 10px rgba(255, 51, 153, 0.6);
    }

    /* Additional Styles */
    .btn-github {
        background: #24292e; /* GitHub's color */
    }

    .btn-svelte {
        background: #ff3e00; /* Svelte's color */
    }
</style>
<body>
	<div class="container">
		<!-- Your Svelte component will be mounted here -->
		<h1>Hello, Svelte!</h1>
		<p>This is a Svelte starter project.</p>
		
		<!-- GitHub Button -->
		<button class="btn btn-github" on:click={() => window.location.href='https://github.com/RJohnPaul'}>GitHub</button>
		
		<!-- Svelte Button -->
		<button class="btn btn-svelte" on:click={() => window.location.href='https://svelte.dev'}>Svelte</button>
	</div>
</body>
