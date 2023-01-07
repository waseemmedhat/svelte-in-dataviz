<script>
	import { Highlight } from 'svelte-highlight';
	import xml from 'svelte-highlight/languages/xml';
	import 'svelte-highlight/styles/github.css';
</script>

<h2 class="center">Basics</h2>

<p class="mb center">
	<a href="https://svelte.dev/tutorial/basics">https://svelte.dev/tutorial/basics</a>
</p>

<p class="justify mb">
	This part goes over an introduction to what Svelte is, and how it is similar to and different
	(being a compiler) from other JS frameworks out there.
</p>

<p class="justify mb">
	What is most relevant about data visualization here is that you write your code as separate
	<i>components</i>, which are single files that encapsulate markup, styling, and logic for a
	particular part of your app or visualization.
</p>

<p class="justify mb">Using components, your high-level code would look like this:</p>

<Highlight
	language={xml}
	code={` 
        <VizContainer>
            <AxisBottom />
            <AxisLeft />
            <Marks />
        </VizContainer>
    `}
/>

<p class="justify mt mb">
	This way makes the code more declarative and, as a result, more self-explanatory without a ton of
	comments. It also makes each part of the project isolated in its own separate file (e.g., <code
		>VizContainer.svelte</code
	>, <code>AxisBottom.svelte</code>, etc.) which helps with both organization and debugging.
</p>
