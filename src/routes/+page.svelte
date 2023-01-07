<h1 class="mb center">Svetle <small>in Dataviz</small></h1>

<h2 id="contents" class="mb center">Contents</h2>
<ul class="contents-list">
	<b> Project Info</b>
	<ul>
		<li><a href="about">About Project & Technologies Used Here</a></li>
	</ul>
	<b>1. Introduction</b>
	<ul>
		<li><a href="1a-basics">a. Basics</a></li>
		<option value="adding-data">b. Adding data</option>
		<option value="dynamic-attributes">c. Dynamic attributes</option>
		<option value="styling">d. Styling</option>
		<option value="nested-components">e. Nested components</option>
		<option value="html-tags">f. HTML tags</option>
		<option value="making-an-app">g. Making an app</option>
	</ul>
	<!-- <optgroup label="2. Reactivity">
		<option value="reactive-assignments">a. Assignments</option>
		<option value="reactive-declarations">b. Declarations</option>
		<option value="reactive-statements">c. Statements</option>
		<option value="updating-arrays-and-objects">d. Updating arrays and objects</option>
	</optgroup>
	<optgroup label="3. Props">
		<option value="declaring-props">a. Declaring props</option>
		<option value="default-values">b. Default values</option>
		<option value="spread-props">c. Spread props</option>
	</optgroup>
	<optgroup label="4. Logic">
		<option value="if-blocks">a. If blocks</option>
		<option value="else-blocks">b. Else blocks</option>
		<option value="else-if-blocks">c. Else-if blocks</option>
		<option value="each-blocks">d. Each blocks</option>
		<option value="keyed-each-blocks">e. Keyed each blocks</option>
		<option value="await-blocks">f. Await blocks</option>
	</optgroup>
	<optgroup label="5. Events">
		<option value="dom-events">a. DOM events</option>
		<option value="inline-handlers">b. Inline handlers</option>
		<option value="event-modifiers">c. Event modifiers</option>
		<option value="component-events">d. Component events</option>
		<option value="event-forwarding">e. Event forwarding</option>
		<option value="dom-event-forwarding">f. DOM event forwarding</option>
	</optgroup>
	<optgroup label="6. Bindings">
		<option value="text-inputs">a. Text inputs</option>
		<option value="numeric-inputs">b. Numeric inputs</option>
		<option value="checkbox-inputs">c. Checkbox inputs</option>
		<option value="group-inputs">d. Group inputs</option>
		<option value="textarea-inputs">e. Textarea inputs</option>
		<option value="select-bindings">f. Select bindings</option>
		<option value="multiple-select-bindings">g. Select multiple</option>
		<option value="contenteditable-bindings">h. Contenteditable bindings</option>
		<option value="each-block-bindings">i. Each block bindings</option>
		<option value="media-elements">j. Media elements</option>
		<option value="dimensions">k. Dimensions</option>
		<option value="bind-this">l. This</option>
		<option value="component-bindings">m. Component bindings</option>
		<option value="component-this">n. Binding to component instances</option>
	</optgroup>
	<optgroup label="7. Lifecycle">
		<option value="onmount">a. onMount</option>
		<option value="ondestroy">b. onDestroy</option>
		<option value="update">c. beforeUpdate and afterUpdate</option>
		<option value="tick">d. tick</option>
	</optgroup>
	<optgroup label="8. Stores">
		<option value="writable-stores">a. Writable stores</option>
		<option value="auto-subscriptions">b. Auto-subscriptions</option>
		<option value="readable-stores">c. Readable stores</option>
		<option value="derived-stores">d. Derived stores</option>
		<option value="custom-stores">e. Custom stores</option>
		<option value="store-bindings">f. Store bindings</option>
	</optgroup>
	<optgroup label="9. Motion">
		<option value="tweened">a. Tweened</option>
		<option value="spring">b. Spring</option>
	</optgroup>
	<optgroup label="10. Transitions">
		<option value="transition">a. The transition directive</option>
		<option value="adding-parameters-to-transitions">b. Adding parameters</option>
		<option value="in-and-out">c. In and out</option>
		<option value="custom-css-transitions">d. Custom CSS transitions</option>
		<option value="custom-js-transitions">e. Custom JS transitions</option>
		<option value="transition-events">f. Transition events</option>
		<option value="local-transitions">g. Local transitions</option>
		<option value="deferred-transitions">h. Deferred transitions</option>
		<option value="key-blocks">i. Key blocks</option>
	</optgroup>
	<optgroup label="11. Animations">
		<option value="animate">a. The animate directive</option>
	</optgroup>
	<optgroup label="12. Actions">
		<option value="actions">a. The use directive</option>
		<option value="adding-parameters-to-actions">b. Adding parameters</option>
	</optgroup>
	<optgroup label="13. Advanced styling">
		<option value="classes">a. The class directive</option>
		<option value="class-shorthand">b. Shorthand class directive</option>
		<option value="inline-styles">c. Inline styles</option>
		<option value="style-directive">d. The style directive</option>
	</optgroup>
	<optgroup label="14. Component composition">
		<option value="slots">a. Slots</option>
		<option value="slot-fallbacks">b. Slot fallbacks</option>
		<option value="named-slots">c. Named slots</option>
		<option value="optional-slots">d. Checking for slot content</option>
		<option value="slot-props">e. Slot props</option>
	</optgroup>
	<optgroup label="15. Context API">
		<option value="context-api">a. setContext and getContext</option>
	</optgroup>
	<optgroup label="16. Special elements">
		<option value="svelte-self">a. &lt;svelte:self&gt;</option>
		<option value="svelte-component">b. &lt;svelte:component&gt;</option>
		<option value="svelte-element">c. &lt;svelte:element&gt;</option>
		<option value="svelte-window">d. &lt;svelte:window&gt;</option>
		<option value="svelte-window-bindings">e. &lt;svelte:window&gt; bindings</option>
		<option value="svelte-body">f. &lt;svelte:body&gt;</option>
		<option value="svelte-head">g. &lt;svelte:head&gt;</option>
		<option value="svelte-options">h. &lt;svelte:options&gt;</option>
		<option value="svelte-fragment">i. &lt;svelte:fragment&gt;</option>
	</optgroup>
	<optgroup label="17. Module context">
		<option value="sharing-code">a. Sharing code</option>
		<option value="module-exports">b. Exports</option>
	</optgroup>
	<optgroup label="18. Debugging"> <option value="debug">a. The @debug tag</option></optgroup>
	<optgroup label="19. Next steps">
		<option value="congratulations">a. Congratulations!</option>
	</optgroup> -->
</ul>

<style>
	ul {
		margin-bottom: 1rem;
		padding-left: 1rem;
	}
</style>
